# HỆ THỐNG AI MINH HỌA THUẬT TOÁN 
# MÔN CẤU TRÚC DỮ LIỆU VÀ GIẢI THUẬT
Sử dụng Python kết hợp với streamlit để xây dựng hệ thống

# 1. Kiến trúc hệ thống
  1.1 Data Structures (Backend): Các class Python thuần (Node, LinkedList, BST) xử lý logic.

  1.2 State Capture (Snapshot): Mỗi khi thuật toán chạy 1 bước, ta lưu lại trạng thái đồ thị và lời giải thích vào st.session_state.

  1.3 Visualization (Frontend): Sử dụng thư viện Graphviz (tích hợp sẵn trong Streamlit) để vẽ cấu trúc dữ liệu từ trạng thái hiện tại.

  1.4 AI Explanation: Tạo một hàm giả lập (hoặc kết nối API OpenAI) để sinh ra lời giải thích dựa trên hành động hiện tại.
#2. Cài đặt môi trường 
    Cài đặt thư viện
        pip install streamlit graphviz

# 3. Cấu trúc mã nguồn
      VizDSA/
      ├── logic.py           # Xử lý thuật toán thuần túy
      ├── visualization.py   # Xử lý vẽ hình và tạo text AI
      └── app.py             # Giao diện chính (File chạy)
# 4. Hướng dẫn vận hành
