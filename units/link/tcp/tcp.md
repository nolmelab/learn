# tcp 

TCP는 긴 역사를 갖는다. 지식과 기술의 진보는 긴 역사를 만들고 필요한 내용과 
불필요한 내용의 경계를 모호하게 만든다. 

통신은 일종의 큐로 보면 된다. 넣으면 다른 쪽에서 꺼내 볼 수 있다. TCP는 전달이 
보장되고 순서가 보장된 큐에 해당한다. 

BSD Socket API가 필요할 때도 있겠으나 여기서는 asio API를 통해 통신을 구현하는 
것으로 충분하다. 좋은 라이브러리는 그런 장점을 갖는다.  게임 서버를 만드는 
입장에서는 더욱 그렇다. 

물론 클라이언트가 C#이나 다른 언어라면 별도의 라이브러리를 사용하여 통신을 구현해야 
한다. 

## 연습  

https://think-async.com/Asio/boost_asio_1_30_2/doc/html/boost_asio/examples/cpp11_examples.html

위 문서를 따라 연습할 만한 내용은 아래 두 가지이다.
- [ex_1] chat client and server
- [ex_2] async tcp echo server

TODO:
- cmake 프로젝트 구성하고, 예제들 추가 

버퍼에 대해서는 좀 더 자세히 살펴볼 필요가 있다. 특히, streambuf 부터 시작하는 내용들은
자세히 이해할 필요가 있다. 

- [ex_3] streambuf 이해
- [ex_4] asio의 버퍼들 





