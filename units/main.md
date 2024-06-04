# 게임 서버 프로그래밍 

게임 서버를 잘 만드는 프로그래머가 되려면 필요한 연습이 있습니다. 작은 단위부터 
큰 라이브러리 이해까지 차근차근 연습한다면 새로운 세상을 효율적이고 안정적으로 
만들 수 있습니다. 좋은 프로그래머가 되는 길은 고민하고 찾고 연습하고 개선하는 
과정이 꼭 필요합니다. 게임 서버 프로그래머는 새롭기도 하지만 견고한 세상을 
만들 수 있어야 합니다. 그러기에 책임도 많이 따릅니다. 그러기에 연습은 더할 나위 없이 
중요한 덕목입니다. 

따라서, 연습하고 또 연습할 것을 권하고 저도 최선을 다해 연습하려고 합니다. 

## 목표

게임 서버 만드는데 필요한 대부분의 기초를 갖출 때까지 찾고 익히고 정리하는 과정을
반복하려고 합니다. 여기에 쓴 글과 코드는 그대로 공개할 예정입니다. 

책으로 정리하고 싶은 마음도 있었으나 배우는 것 보다 쓰는데 더 많은 노력이 들었습니다. 
GSP 폴더가 그 기록입니다. 헤맨 과정, 정리한 과정, 나만의 의견이나 생각을 자유롭게 적고 
코드와 코드 주석 형태로 전달해도 충분하고 그럴 때 더 잘 전달할 수 있으며 더 많은 범위를 
포괄 할 수 있다는 생각을 들어 이와 같은 형태로 진행하기로 했습니다. 

## 단위 구분 

- env
  - c++ 
    - brief history
    - cmake 
    - vcpkg
    - standard library
  - os 
    - linux
    - windows
  - ide
    - visual studio
    - vscode

- base
  - macro 
  - logger
  - memory managers
  - instrumentation tools

- link 
  - asio
    - tcp
      - buffer
      - serialize / deserialize
      - flatbuffers
    - processing
      - multi-threaded
      - strand

- db 
  - odbc
  - nanodbc

- data
  - relational
  - tree 

- ecs
  - behaviortree
  - timer
  - boost.signal2
  - scripting

- physical space
  - rigidbody physics
  - shape
  - collision / overlap 
  - navigation 

