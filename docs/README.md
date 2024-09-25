======================================== Ô ĂN QUAN ============================================
=========================                                   ===================================

1. Các thành phần chính trong chương trình:

    assets/
    Thư mục chứa tất cả tài nguyên không mã hóa của game như hình ảnh, âm thanh và âm nhạc.
        images/: Thư mục này chứa các sprite sheet, character designs, và các hình nền khác.
        sounds/: Lưu trữ các tệp âm thanh ngắn như hiệu ứng và tiếng động nhỏ lẻ.
        music/: Thư mục dành cho các bài hát hoặc soundtrack chính thức của game.

    src/
        main.py: Tệp chính chứa game loop và logic gameplay cơ bản.
        game_loop.py: Cung cấp vòng lặp game và cập nhật trạng thái.
        graphics.py: Xử lý đồ họa và rendering.
        input.py: Xử lý đầu vào từ người dùng.
        ai.py: Logic AI nếu có trong game.
        utils.py: Các hàm và lớp phụ trợ chung.

    docs/
        README.md: Tài liệu hướng dẫn sử dụng và cài đặt game.

    tests/
        test_game.py: Các bài kiểm tra đơn vị để đảm bảo tính ổn định của game.

    build/
        dist/: Thư mục chứa tệp kết xuất cuối cùng sau khi xây dựng game.