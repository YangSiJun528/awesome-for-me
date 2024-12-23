# 🌟 Awesome For Me

나에게 유용한 프로젝트, 사이트, 블로그 글, 책 등을 모아놓은 공간이에요.  
주로 자주 참고하거나 유용하다고 생각하는 자료들을 선정해요.

## 정리 형식

[EBNF (Extended Backus–Naur Form)](https://en.wikipedia.org/wiki/Extended_Backus%E2%80%93Naur_form)로 정리
```
<정리-항목> ::= <이모지> <제목> [<출처>] "-" <간단한-설명>
                [<개인적인-메모-리스트>]

<개인적인-메모-리스트> ::= <개인적인-메모> {"\n" <개인적인-메모>}*
<개인적인-메모> ::= "-" <메모-내용>

<이모지> ::= "📚" | "🌐" | "📂" | "✍️" | "🎬" | "🕹️"
<제목> ::= <텍스트>
<출처> ::= "(" <출처-설명> ")"
<간단한-설명> ::= <텍스트>
<메모-내용> ::= <텍스트>
<텍스트> ::= <임의의-문자열>
```

### 📑 이모지 의미

- 📚 : 책  
- 🌐 : 웹 사이트  
- 📂 : 코드 저장소  
- ✍️ : 기술 블로그, 서평 등  
- 🎬 : 영상 (이전: 📹)  
- 🕹️ : 게임, 인터렉티브 웹 등 상호작용 위주의 자료  

---

## 📡 Network

- **📚 [컴퓨터 네트워킹: 하향식 접근(Computer Networking: A Top-Down Approach)](https://www.yes24.com/Product/Search?domain=BOOK&query=%25EC%25BB%25B4%25ED%2593%25A8%25ED%2584%25B0%2520%25EB%2584%25A4%25ED%258A%25B8%25EC%259B%258C%25ED%2582%25B9%253A%2520%25ED%2595%2598%25ED%2596%25A5%25EC%258B%259D%2520%25EC%25A0%2591%25EA%25B7%25BC(Computer%2520Networking%2520A%2520Top%2520Down%2520Approach))** - 네트워크 개념을 잡기 좋은 책.  
    - 빠르게 훑어보려면 [📂 GitHub에 정리된 Repository](https://github.com/IT-Book-Organization/Computer-Networking_A-Top-Down-Approach) 참고.

- **📚 [High Performance Browser Networking](https://hpbn.co/)** - 웹 개발자를 위한 네트워킹과 웹 성능 최적화 기법. 무료로 읽을 수 있음.  
    - 한국어로 번역된 책 제목은 "네트워킹과 웹 성능 최적화 기법".  
    - 구글 출신 Ilya Grigorik의 자료.

- **🎬 [Network Protocol (Destroy All Software)](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=97d3ba4c24d21147)** - 네트워크 스택 동작에 대한 짦은 글. (20 minute read)  
    - _Reliable transmission_ 섹션이 특히 흥미로움.

## 💾 Computer Science

- **[📚 밑바닥부터 만드는 컴퓨팅 시스템(The Elements of Computing Systems)](https://www.yes24.com/Product/Goods/118440555)** - Nand 게이트부터 간단한 OS까지 제작한다.
    - Nand to Tetris 프로젝트의 책. 컴퓨터 구조, 어셈블리, 프로그래밍 언어의 내부 동작 등을 익히기에 좋다.
    - 다만. 분량 상의 문제로 생략된 설명(Resigter 동작, OS의 가상 메모리나 인터럽트 등)이 있는건 아쉬운 부분.
    - 하드웨어 파트를 게임으로 구현한 [nandgame 사이트](https://nandgame.com/).

## 📃 자료 아카이브 

- **🌐 [free-programming-books](https://ebookfoundation.github.io/free-programming-books-search/)** - 다양한 언어로 제공되는 무료 학습 리소스 목록.
    - 매우 많은 자료가 있다. 어셈블리어 같은 마이너한 자료도 존쟈.

## 🚀 Fun

- **🕹️ [SHENZHEN_IO](https://store.steampowered.com/app/504210/SHENZHEN_IO/)** - 가상의 어셈블리어, MCU와 Chip을 사용해 요구하는 PCB를 만들어내는 게임.
    - 임베디드 개발 공부 목적이라기엔 부족한게 많고, 그냥 재미로 하기 좋았음.
    - [비공식 한글화](https://github.com/wizroad3/shenzhen-io-korean), [메뉴얼 번역본 PDF](https://github.com/metalg0su/shenzhen-io-korean/pull/12)가 존재함.

---

# Contribution

- 자료 추천 및 오타 제보, 기타 문의는 Issue 또는 Pull Request로 자유롭게 제출 가능해요.  
- 단, 자료 선정 기준은 **나에게 유용한가**이므로 채택되지 않을 수 있어요.
