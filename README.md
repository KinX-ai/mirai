<h1 align="center">
	<a href="#"><img src="https://i.imgur.com/jdqeKHq.jpg" alt="Mirai"></a>
	Mirai Bot
</h1>
<p align="center">
	<img alt="size" src="https://img.shields.io/github/repo-size/roxtigger2003/mirai-beta.svg?style=flat-square&label=size">
	<img alt="code-version" src="https://img.shields.io/badge/dynamic/json?color=red&label=code%20version&prefix=v&query=%24.version&url=https%3A%2F%2Fraw.githubusercontent.com%2Froxtigger2003%2Fmirai-beta%2Fmaster%2Fpackage.json&style=flat-square">
	<a href="https://github.com/roxtigger2003/mirai-beta/commits"><img alt="commits" src="https://img.shields.io/github/commit-activity/m/roxtigger2003/mirai-beta.svg?label=commit&style=flat-square"></a>
</p>

<p align="center">
	<a href="#Overview">Tổng Quát Về Bot</a>
	-
	<a href="#Installation">Hướng Dẫn Cài Đặt</a>
	-
	<a href="#Author">Tác Giả</a>
</p>

# Overview

Project Mirai sẽ biến tài khoản Facebook cá nhân của bạn thành một con bot thông minh, nhanh nhẹn!

Đây là bản beta nên chắc chắn sẽ có lỗi, cân nhắc trước khi sử dụng

## Các thay đổi

<details>
	<summary>Đây là các log thay đổi qua từng phiên bản</summary>

(Tất cả những lịch sử thay đổi có thể xem ở file README.md phiên bản cũ)

- 4.6.5: genaral -> general.

- 4.7.0: Thêm lang, thay đổi rất nhiều.

</details>

# Installation

## Yêu cầu:
  - [NodeJS](https://nodejs.org/en/) và git(không bắt buộc)
  - Trình độ sử dụng NodeJS ở mức trung bình
  - Một tài khoản Facebook dùng để làm bot(Khuyên nên sử dụng acc đã bỏ hoặc không còn sử dụng để tránh mất acc hay acc bị khoá!!)
 
## Cài đặt (Linux/macOS/WSL/Windows đã cài windows-build-tools):
* Step 1: Clone hoặc download project, nếu máy bạn có git hãy sử dụng lệnh:
```bash
git clone https://github.com/roxtigger2003/mirai
```
* Step 2: Trỏ và bắt đầu cài đặt các gói module cần thiết cho bot cũng như file env:

(Windows CMD)
```cmd
cd mirai && rename .env.example .env && npm install
```
(Linux/macOS Terminal)
```bash
cd mirai && mv -f .env.example .env && npm install
```
* Step 3: Mở file .env và chỉnh sửa.
* Step 4: Login vào tài khoản Facebook của bạn theo thông tin đăng nhập bạn đã điền trong file .env:
```bash
node login.js
```
+ Step 5: Nhập lệnh này nếu bạn không dùng bot trên Glitch:
```bash
npm start
```

## Video hướng dẫn deploy và sử dụng Mirai Bot:

-  Hướng dẫn dành cho Glitchs:

[![Tutorial for Glitch.com](https://img.youtube.com/vi/wbfAxyV4n_o/0.jpg)](https://www.youtube.com/watch?v=wbfAxyV4n_o)

- Hướng dẫn dành cho Windows 10:

[![Tutorial for Window 10](https://img.youtube.com/vi/NGxyB6TRX9Q/0.jpg)](https://www.youtube.com/watch?v=NGxyB6TRX9Q)


## Deployment
Click this button:
[![Remix on Glitch](https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg)](https://glitch.com/edit/#!/import/github/roxtigger2003/mirai)
[![Run on Repl.it](https://repl.it/badge/github/roxtigger2003/mirai)](https://repl.it/github/roxtigger2003/mirai)

# Author
- **CatalizCS** (*Author and coder*) - [GitHub](https://github.com/roxtigger2003) - [Facebook](https://fb.me/Cataliz2k)
- **SpermLord** (*Co-Author and coder*) - [GitHub](https://github.com/spermlord) - [Facebook](https://fb.me/MyNameIsSpermLord)

**Và cùng nhiều anh em tester đã đồng hành cùng project! Cảm ơn!**

## License

This project is licensed under the GNU General Public License v3.0 License - see the [LICENSE](LICENSE) file