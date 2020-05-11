Create a CSS library
Commit 01: Create grid object
    + create : grid: full width 1200px chưa hết chiều ngang đối tượng cha.
    + quy định chiều ngang tối đa là 1200px: max-width: 1200px.
    + tạo reponsive cho PC , tablet, mobile.
Commit 02: Create Row object
    + chứa các column , giúp các column nằm theo chiều ngang.
    + Khi tổng chiều ngang columns vượt quá wide thì xuống dòng. tạo margin left right âm để column tràn quá wide.
    + loại bỏ khoảng thừa do gutters tạo ra 2 phía : -> commit 03
Commit 03: 
    + 