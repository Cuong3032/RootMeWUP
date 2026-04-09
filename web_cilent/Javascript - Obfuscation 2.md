<img width="2387" height="591" alt="image" src="https://github.com/user-attachments/assets/9a826723-94f8-45dc-8f19-60c15b3b0f21" />

pass được mã hóa 2 lớp unescape + String.fromCharCode nên chỉ việc bóc tách lần lượt từ unescape sau đó là String.fromCharCode

đầu tiên bóc tách ra được `unescape("String.fromCharCode%28104%2C68%2C117%2C102%2C106%2C100%2C107%2C105%2C49%2C53%2C54%29")`

tiếp tục bóc tách ra được `String.fromCharCode(104,68,117,102,106,100,107,105,49,53,54)`

<img width="347" height="34" alt="image" src="https://github.com/user-attachments/assets/0864ff71-7c5b-43ce-9884-7fbef1051560" />

cuối cùng bóc tách ra được `hDufjdki156` vậy là xong.
