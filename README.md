# flight-data 분석 과제

**LS빅데이터스쿨 4기 flight-data 분석 실습 과제**

## 참여 인원

<table style="text-align:center; width:100%;">
  <tr>
    <td><img src="./readme/seoyeon.jpg" width="100px;" height="100px;"></td>
    <td><img src="./readme/minchae.jpg" width="100px;" height="100px;"></td>
    <td><img src="./readme/jaewon.jpg" width="100px;" height="100px;"></td>
    <td><img src="./readme/sangwon.jpg" width="100px;" height="100px;"></td>
  </tr>
  <tr>
    <td><a href="https://github.com/9-1333">권서연</a></td>
    <td><a href="https://github.com/k1minchae">김민채</a></td>
    <td><a href="https://github.com/jaewon03561">박재원</a></td>
    <td><a href="https://github.com/osangwon">오상원</a></td>
  </tr>
  <tr>
    <td>-엔진개수와 좌석수 관계 분석 - QMD 제작</td>
    <td>- 시간대별 지연시간 분석 - QMD 제작 및 CSS</td>
    <td>- 날씨와 지연시간 분석 - 발표</td>
    <td>- 계절별 지연시간 조사 및 발표</td>
  </tr>
</table>

## 환경 설정하기

```bash
git remote add upstream https://github.com/k1minchae/flight-data.git
git remote -v
git fetch upstream
git merge upstream/main
```

![](https://docs.ropensci.org/dittodb/articles/relational-nycflights.svg)

이 데이터는 2013년 뉴욕에서 출발한 모든 항공편의 운항 데이터로 구성되어 있으며, 항공사, 공항, 날씨, 항공기에 대한 메타데이터를 포함하고 있습니다. 저희는 flight, plane, weather 데이터를 중심으로 항공 운항과 관련된 다양한 패턴을 분석하고자 합니다.

<br>

## 분석 목표

1️⃣ 데이터 전처리

- 결측치 및 이상치 처리
- 데이터 타입 변환 및 정리
- 데이터 결합 및 필요한 변수 생성

2️⃣ 항공편 지연 분석

- 시간대별 지연 패턴 확인
- 날씨별 지연 패턴 확인
- 계절별 지연 패턴 확인

3️⃣ 항공기 특성 분석

- 엔진개수별 항공기 특성 분석

<br>
