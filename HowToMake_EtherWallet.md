# 개인 Ethereum Wallet 만드는 법

Ethereum Wallet 은 여러가지 종류가 있지만 여기서는 간단하게 MyEtherWallet (웹 기반)으로 만드는 법을 설명드리겠습니다.

## MyEtherWallet 만들기

[MyEtherWallet]( https://www.myetherwallet.com/) 에 접속합니다. https://www.myetherwallet.com/

![](img\HowToMakeEtherWallet\MyEtherWallet_1.JPG)
해당 화면에서 본인이 만들 개인 비밀번호를 입력한뒤 "Create New Wallet" 을 입력합니다.

![](img\HowToMakeEtherWallet\MyEtherWallet_2.JPG)
해당비밀번호로 만든 Keystore File 을 본인의 컴퓨터에 저장한뒤 I understand. Continue. 버튼을 클릭합니다.
#### 주의사항 : 해당 파일은 절대 잃어버리면 안되니 2중 & 3중으로 백업해두는것을 권장하며, 절대 공유하지마세요.

![](img\HowToMakeEtherWallet\MyEtherWallet_3.JPG)
Private key를 종이에 적어두거나, 프린트하거나 혹은 파일로 따로 백업해두세요. 동일하게 공유/잃어버리면 안됩니다. Save Your Address 를 클릭하세요. 

![](img\HowToMakeEtherWallet\MyEtherWallet_4.JPG)

앞서 Keystore  / JSON File 로 저장을 했으니, 우리는 Keystore / JSON 을 선택하고, "SELECT WALLET FILE"버튼을 눌러 저장했던 Keystore File을 찾아줍니다. 

![](img\HowToMakeEtherWallet\MyEtherWallet_5.JPG)

앞서 입력한 **개인 비밀번호**를 입력하고 Unlock 을 눌러줍니다. 

![](img\HowToMakeEtherWallet\MyEtherWallet_6.JPG)

개인지갑이 만들어졌습니다! 위에 0x로 시작하는 Address가 우리의 개인지갑을 식별하는 주소입니다.

## 개인 지갑 내용 보기

이제 개인지갑이 만들어졌습니다. 개인지갑들의 전송내역이나 남은 잔액들을 보시려면 etherscan.io 에서 아래처럼 본인의 주소를 입력하여 볼수 있습니다. 
> https://etherscan.io/address/**0x6B2bDACa49Cae5C2d8E27a742C5f4BB4d6C03690**
![](img\HowToMakeEtherWallet\MyEtherWallet_7.JPG)
방금 이더리움 지갑을 만들었기때문에, 지갑에 내용이 아무것도 없을것입니다. 

유명 Polonix 거래소의 지갑을 한번 살펴보도록 합시다.

https://etherscan.io/address/0x32be343b94f860124dc4fee278fdcbd38c102d88

![](img\HowToMakeEtherWallet\MyEtherWallet_8.JPG)
폴로닉스 거래소의 지갑에는 아주 많은 양의 이더리움을 보유하고 있습니다. 그리고 이더리움 뿐만아니라 이더리움을 기반으로한 다른 코인까지 전송된 내역을 볼수 있는데요. Erc20 Token Txns 버튼을 클릭해봅시다.

![](img\HowToMakeEtherWallet\MyEtherWallet_9.JPG) 
아주 다양한 ERC-20 Token들이 존재하는것을 보실수있습니다.

방금 만든 Ethereum Wallet으로 이더리움 기반의 Airdrop 이벤트, 혹은 ICO에 참여할수 있으니 폭넓게 활용해보세요.


