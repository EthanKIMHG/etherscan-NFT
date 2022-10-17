# etherscan-NFT

로직

필요한 스택
npm = discord.js, web3(infura),

하드코딩으로 가져올 NFT 의 ID 값을 미리 정해놓는다.
이유는, /커맨드를 사용하고, params에 해당 NFT id 값을 넣어 줘야하기 때문에 복잡하다.

/image 하면, 저희가 지정한 NFT 이미지가 올 수 있게.

1. discord.js로 /image 커맨드를 작성한다.

2. discord 앱 에서 /image 커맨드를 입력한다.

3. infura로 원격 이더리움 노드에 접근하여, NFT 이미지를 가져온다.

어쨋든, NFT에 img URL이 있기때문에, 이 imgURL을 가져오면 될거같은데.
conflict를 일부로 내보겠습니다.


에러사항

1. 이미파일로 불러와야하는데, 그 이미지 URL만 가져오는 경우.STRING 으로... -> 해결가능, 미드저니, AI 아트 그림. 디스코드로 Img를 다 불러옴.짭짭짭

당황스럽게도 에러사항이 너무 쉽게 해결되었다..

추가 고려사항.

Params를 넣는 과제를 나중에 해보자.
something change
