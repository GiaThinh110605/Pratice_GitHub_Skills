### Revert code
* Hướng dẫn cách revert từ 1 hay nhiều commit trong Git
#### Cách 1: Sử dụng git revert trong terminal:
- Kiểm tra nhánh hiện tại: git branch
- Đi tới nhánh cần revert: git checkout <branch_name>
- Kiểm tra lịch sử commit: git log --oneline 
- Revert nhiều Pull Request: git revert -n <commit1> <commit2> <commit3> ...
- Kiểm tra lại status: git status
- Chuyển qua nhánh khác để push code: git checkout -b <new_branch_name>
- Viết lại những thay đổi: git commit -m "Revert code"
- Push code lên, và tạo Pull request: git push
- Kiểm tra những thay đổi và merge code vào nhánh chính

#### Cách 2: Sử dụng tool hỗ trợ: Git Graph trong extension của Visual Studio Code
- Sử dụng Git Graph có những tính năng revert
