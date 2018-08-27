# 이더리움 문제점
이더리움의 문제와 약점에 대해 다룹니다.

### 처리 성능과 용량
* 가장 낮은 가스 비용을 기준으로 트랜잭션의 처리 평균 13 분이 소요되고 있습니다 (일반 상거래에 비해 매우 늦은 수준)
*  Consensus Algorithm 개선이 필요하다

### POW방식의 합의 엔진
* 컴퓨팅 자원 투자의 증가를 불러오고 있습니다
* 운영에 있어서 큰 전기 소모를 불러오고 있습니다
* 마이닝 파워가 소수에게 집중되고있습니다

### 51% Attack
 * 시간차 공격에 의해 이중지불 될 수있습니다.
 
 ### 파이널리티의 불확실성
 * POW에서 블록체인이 분기될 때 항상 긴 블록체인을 선택하는 과정에서 블록체인이 긴 블록체인으로 revert될 경우 짧은 블록체인에 속한 블록에 포함된 트랜잭션의 경우 처리가 되었음에도 반영되지 못할 수 있습니다.
 * 현재 해결 방안으로는 uncle block, ghost protocol을 사용하고 있습니다  
 * 진행중인 [캐스퍼 프로젝트](https://steemit.com/crypto/@shsfse/casper-raiden-plasma-sharding)
 
 ### 블록체인 데이터 크기 증가
 * 데이터 크기 증가에 따른 동기화가 늦어지고 있습니다
 * 블록체인 데이터의 크기가 커질수록 이를 전체 동기화하려는 노드는 줄 것이므로 역설적으로 블록체인의 중앙집중화가 발생할 것입니다
 
 ### 스마트 컨트랙트와 EVM
 * 단순 거래 로직을 구현할 뿐, 스마트 컨트랙트라 할 수 없습니다
 * EVM에서 지원하는 반복 호출 횟수의 크기또한 1024에 불과합니다
 * 스마트 컨트랙트의 입력 데이터에 대한 신뢰성 확보를 위한 외부기관 오라클이 필요합니다
 ### ICO 버블
 * [ICO (Initial Coin Offerings)](https://steemit.com/ico/@shiningmoon1969/ico)
 * 검증되지 않은 프로젝트들이 단순한 백서 하나로 막대한 자금을 조달하고 있습니다