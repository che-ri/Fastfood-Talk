# Kokoa Clone 2020

HTML & CSS are so much fun!

<h1>문제해결</h1>
Ronald와의 채팅창에서 메세지가 실시간으로 오는 듯한 애니메이션을 주고 싶었다. 
message-row에 애니메이션을 주었고, 
message-row-own에 animation-delay 값을 주었지만 
애니메이션의 원 위치가 화면 안에 있으므로 실시간의 느낌을 주지 못했다. 

그래서 message-row-own에 opacity:0 값을 주었고, 
애니메이션의 to에는 opacity:1 값을 주고, 
message-row에는 forwards 를 적용했다. 

