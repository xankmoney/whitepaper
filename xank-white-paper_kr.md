# Xank: 준비금으로 뒷받침되는 안정적인 거래 암호화폐

저자 :

김유현 ([ryu@xank.io](mailto:ryu@xank.io))

기여자 :

이성신 ([rl@xank.io](mailto:rl@xank.io))

김성협 ([sung@xank.io](mailto:sung@xank.io))

버전 0.99.9s

최초 발행일 : 2018년 4월 7일

최신 버전 확인 : [xank.io](https://xank.io/)

저작권 © 2018-2024 Xank Holdings OÜ. 모든 권리 보유.


# 법적 면책 조항 :

정의

**백서** : 이 정보 문서와 그에 포함된 모든 내용.

**회사** : Xank 및 관련 구성원.

**토큰** : Xank 플랫폼에서 사용하기 위해 Xank가 생성하고 배포한 토큰.

이 백서 또는 Xank 웹사이트에 제공된 정보를 사용하는 경우, 귀하는 다음 사항에 동의하는 것입니다:

이 백서의 목적은 Xank 프로젝트의 비기술적 및 기술적 측면에 관한 정보를 제공하는 것입니다. 이 정보는 포괄적이지 않으며 계약 관계를 구성하지 않습니다.

이 백서는 어떤 형태로든 투자 청약서나 투자 권유를 구성하지 않으며, 어떤 관할권에서도 증권을 매수할 제안이나 제안의 권유로 간주되지 않습니다. 따라서 투자자를 보호하기 위해 설계된 법률이나 규정에 따라 작성되지 않았으며, 그러한 법률이나 규정의 적용을 받지 않습니다. 이 백서에 포함된 특정 진술, 추정치 및 재무 정보는 예측된 진술 또는 정보로 구성됩니다. 이러한 예측은 알려진 및 알려지지 않은 위험과 불확실성을 수반하며, 실제 사건이나 결과가 예측된 진술에 포함되거나 명시된 추정치나 결과와 실질적으로 다를 수 있습니다.

영문 백서는 Xank 및 그 프로젝트에 대한 주요 공식 정보 출처입니다. 여기 포함된 정보는 때때로 국문 또는 다른 언어로 번역되거나 기존 및 잠재 고객과의 서면 또는 구두 의사소통 과정에서 사용될 수 있습니다. 이러한 번역 또는 의사소통 과정에서 일부 정보가 손실되거나 손상되거나 잘못 전달/번역될 수 있습니다. 그러한 (대체) 의사소통의 정확성은 보장되지 않습니다. 이러한 번역 및 의사소통과 이 공식 영문 백서 간에 충돌이나 불일치가 발생할 경우, 항상 영문 원본 문서의 조항이 우선합니다.

Xank는 여기서 설명한 기능을 제공하기 위해 구축되고 있습니다. 이 프로젝트와 그 토큰은 시스템 사용자에게 금융 상품이나 투자 기회를 제공하기 위해 개발되는 것이 아닙니다. 반대로, Xank와 그 토큰은 제품으로 개발되고 있으며, 증권이나 기타 투자 기회로 개발되는 것이 아닙니다. 토큰은 이 자료에서 설명한 대로만 작동할 것이며, 여기에서 설명한 경우를 제외하고, Xank 또는 프로젝트가 수행할 수 있는 어떤 사항에 대해 토큰 보유자에게 투표 권리를 부여하지 않습니다. Xank는 토큰의 잠재적 미래 가치를 보장하거나 달리 표현하지 않습니다. 프로젝트가 시작되면, 토큰 보유자는 여기 설명된 대로만 토큰을 사용하고 투기적 투자 목적으로 사용하지 않을 것으로 예상됩니다.


# 요약

어떤 통화가 유용하려면 최소한 다음 세 가지 특성을 보여야 합니다 : 교환 매체로서의 기능, 가치 저장 수단으로서의 기능, 회계 단위로서의 기능. 암호화폐는 가치 저장 수단으로 사용할 수 있지만, 교환 매체와 회계 단위로서 신뢰할 수 있는 기능을 하기에는 너무 변동성이 크다는 점이 관찰되었습니다. 스테이블코인 개념은 현재 대부분의 암호화폐에서 나타나는 이러한 약점을 해결할 필요성에서 등장했습니다. 스테이블코인은 가격이 미국 달러(USD)와 같은 다른 안정적인 자산에 고정된 암호화폐입니다. 그 결과, 교환 매체와 회계 단위의 특성을 충족하면서 가치 저장 기능을 수행할 수 있는 가격 안정적인 암호화폐 자산이 탄생하게 됩니다.

가장 지배적인 암호화폐는 지속적으로 가격 변동성을 보입니다. 이러한 변동성은 투기적 투자를 유치할 수 있지만, 그 긍정적인 효과는 소비자와 상인이 상품 및 서비스 거래의 목적으로 가격 위험에 노출되는 것을 꺼리는 경우가 많아 채택을 방해하는 부정적인 효과를 종종 발휘합니다. 직원 보수 지급이나 신용 서비스 연장과 같은 간단한 금융 거래도 지속적인 가격 변동의 왜곡 효과로 인해 쉽게 시작할 수 없습니다.

우리는 가격 안정성을 달성하면서도 탈중앙화되고 자유 변동적인 암호화폐인 Xank를 제안합니다. Xank는 소프트 가격 고정 메커니즘을 사용하여 네트워크 수준에서 가격 고정을 결정하는 프로토콜 거버넌스 메커니즘에 의해 설정됩니다. 예를 들어, Xank 거래는 IMF의 특별인출권(SDR, 또는 이 문서에서 사용될 통화 코드 XDR<sup id="a1">[1](#f1)</sup>) 또는 미국 달러(USD), 유로(EUR), 영국 파운드 스털링(GBP), 일본 엔화(JPY), 중국 위안(RMB), 한국 원화(KRW), 신 타이완 달러(TWD) 등의 다른 지원되는 법정 화폐에 대한 금액에 대해 네트워크에 의해 고정되도록 설정될 수 있습니다. 이후 단계에서는 네트워크가 인플레이션 목표를 달성하기 위해 중앙은행이 수행하는 것처럼 상품 바스켓의 소비자 물가 지수(CPI)에 대한 고정을 업데이트할 수도 있습니다. Xank 프로토콜은 XANK-XDR 비율 또는 XANK-통화 비율 사이의 변동 가격을 유지하기 위해 거래별로 XANK 코인의 수를 알고리즘적으로 조정하여 이를 달성합니다. 소프트 페그는 구매, 판매 및 결제 동안 거래 수명 주기 동안 활성화되며, 이를 통해 수요와 공급의 균형을 확립할 수 있어 Xank를 투자 가치를 가진 유일한 안정적인 암호화폐로 만듭니다.


# 차례

- [Xank: 준비금으로 뒷받침되는 안정적인 거래 암호화폐](#xank-준비금으로-뒷받침되는-안정적인-거래-암호화폐)
- [법적 면책 조항 :](#법적-면책-조항-)
- [요약](#요약)
- [차례](#차례)
- [서론](#서론)
- [Xank 설계 고려사항 : 가격 안정성 구현](#xank-설계-고려사항--가격-안정성-구현)
  - [Xank 네트워크를 위한 Avalanche 프로토콜](#xank-네트워크를-위한-avalanche-프로토콜)
  - [자체 자금 조달 재정부 시스템 채택](#자체-자금-조달-재정부-시스템-채택)
  - [IMF의 SDR(특별인출권)에 대한 소프트 페깅](#imf의-sdr특별인출권에-대한-소프트-페깅)
    - [**IMF의 SDR 역사 개요**](#imf의-sdr-역사-개요)
  - [Xank와 Bridgewater의 실적주의 시스템](#xank와-bridgewater의-실적주의-시스템)
  - [**아이디어 실적주의(Idea Meritocracy)**](#아이디어-실적주의idea-meritocracy)
    - [의미 있는 일](#의미-있는-일)
    - [의미 있는 관계](#의미-있는-관계)
    - [극단적인 진정성](#극단적인-진정성)
    - [극단적인 투명성](#극단적인-투명성)
  - [Xank 프로토콜](#xank-프로토콜)
    - [Stable Pay 기능](#stable-pay-기능)
    - [Local Pay 기능](#local-pay-기능)
    - [Xank 지분 증명(PoS) 거버넌스](#xank-지분-증명pos-거버넌스)
    - [Xank 준비금](#xank-준비금)
    - [시장 진출 전략](#시장-진출-전략)
    - [Measuring the Exchange Rate](#measuring-the-exchange-rate)
      - [SDR and Currency Feeds](#sdr-and-currency-feeds)
      - [Oracle System](#oracle-system)
      - [Oracle Feed Redundancy](#oracle-feed-redundancy)
    - [Stable Pay (or Local Pay) Transaction Lifecycle](#stable-pay-or-local-pay-transaction-lifecycle)
    - [Xank Multi-currency Support](#xank-multi-currency-support)
    - [Extreme Volatility Safeguard (EVS) Price Floor Mechanism](#extreme-volatility-safeguard-evs-price-floor-mechanism)
    - [Atomic Swap Basket](#atomic-swap-basket)
    - [Idea Meritocracy Governance](#idea-meritocracy-governance)
    - [Xank Self-sovereign Identity and Xank Reputation Index](#xank-self-sovereign-identity-and-xank-reputation-index)
    - [Xank Budget Allocation](#xank-budget-allocation)
- [Applications and Use Cases](#applications-and-use-cases)
  - [Exchanges](#exchanges)
  - [Individuals](#individuals)
  - [Merchants](#merchants)
  - [Business and Startup Funding](#business-and-startup-funding)
  - [Activism](#activism)
- [Xank in a Post-fiat World](#xank-in-a-post-fiat-world)
  - [Soft-pegging to a Consumer Price Index](#soft-pegging-to-a-consumer-price-index)
  - [Giving Power Back to the People](#giving-power-back-to-the-people)
  - [A Preamble to the Xank Constitution](#a-preamble-to-the-xank-constitution)
- [Conclusion](#conclusion)
- [Appendix](#appendix)
  - [Pros and Cons of Existing Stablecoins](#pros-and-cons-of-existing-stablecoins)
    - [Tether](#tether)
    - [Maker (Dai)](#maker-dai)
    - [Carbon](#carbon)
  - [**Xank Network Specifications and Comparisons**](#xank-network-specifications-and-comparisons)
  - [**Xank Units of Measure**](#xank-units-of-measure)
  - [XANK Coin Supply Algorithm](#xank-coin-supply-algorithm)
    - [Introduction](#introduction)
    - [Limited Supply](#limited-supply)
    - [Unlimited Supply and Inflation](#unlimited-supply-and-inflation)
    - [GDP](#gdp)
    - [Xank Network Transactions](#xank-network-transactions)
    - [Xank Coin Supply](#xank-coin-supply)
    - [Xank Emission Algorithm](#xank-emission-algorithm)
      - [Initial Design](#initial-design)
      - [Current Design](#current-design)
  - [**Xank Protocol Characteristics Comparison**](#xank-protocol-characteristics-comparison)
- [References and Resources](#references-and-resources)
  - [Notes](#notes)


# 서론

암호화폐는 일반적인 거래 시나리오에서 시장에 받아들여지지 않았습니다. 비트코인과 이더리움 같은 전통적인 암호화폐는 잠재적인 시장 수요를 충족하기 위해 확장할 수 없습니다. 확장에 어려움을 겪는 암호화폐는 번거로운 블록체인에 거래를 기록하는 데 드는 사용자 거래 비용이 증가합니다. Avalanche와 Cosmos와 같은 최신 암호화폐는 몇 초 이내에 거래를 확인하고, 초당 더 높은 거래 처리량과 저렴하고 감소하는 거래 수수료를 제공할 수 있다고 주장합니다. 이러한 주장은 신용카드 수수료보다 현금을 선호하는 상인들에게 특히 매력적입니다. 암호화폐는 환불 불가능하므로 현금처럼 작동할 수 있는 암호화폐를 상인들이 선호할 가능성이 큽니다.

암호화폐로 결제를 이미 수락하는 상인들은 일반적으로 암호화폐를 법정화폐로 즉시 전환하는 암호화폐-법정화폐 상인 서비스를 사용합니다. 일부 서비스는 판매 시점에 실시간 전환을 제공합니다. 상인들은 고객에게 상품과 서비스를 제공하는 사업을 하기 때문에 암호화폐나 금과 같은 가격 변동성이 큰 자산에 투기하는 사업을 하지 않습니다. 암호화폐는 하루에 50%의 가격 하락을 경험할 수 있으며, 이러한 가격 하락은 몇 주 동안 지속될 수 있습니다. 이는 상인 친화적이지 않으며, 상인의 상품과 서비스의 비용과 가격은 일반적으로 법정화폐 기준으로 고정되어 있기 때문에 모든 이익을 없앨 수 있습니다.

열성적인 암호화폐 지지자들은 재산에 대한 직접적인 통제, 언제 어디서나 누구와도 거래할 수 있는 편리함, 가명성 또는 일부 프라이버시 코인이 제공하는 높은 익명성 등 암호화폐의 많은 속성에 열광할 수 있습니다. 그러나 가장 열렬한 지지자조차도 전 재산을 암호화폐에 보유하는 것을 꺼리며, 친구, 가족 및 신규 투자자에게 이러한 변동성이 큰 자산에 기꺼이 잃을 수 있는 비율만 투자하도록 권장합니다.

투기적 투자 단계를 넘어 주류 채택으로 나아가기 위해서는 암호화폐가 가격 안정성을 달성하여 안정적인 교환 매체가 되어야 합니다. 이는 유용한 화폐의 핵심 요소입니다.

암호화폐 투기자들이 가격 변동성에서 중요한 역할을 하지만, 그들이 주요 원인은 아닙니다. 네트워크 수준의 문제가 종종 가격 불안정의 주요 요인이 될 수 있습니다.

비트코인을 괴롭히는 확장성 및 프라이버시 문제를 극복하기 위해 설계된 Dash 네트워크를 고려해 봅시다. 이를 달성하기 위해 Dash는 마스터노드 네트워크 레이어를 구현했습니다. 마스터노드를 운영하기 위한 높은 수준의 자본 지출과 네트워크 하드웨어 요구 사항 때문에, Dash 네트워크는 높은 수준의 거래 처리량을 보장받고 거래 가격 책정 수준을 도입할 수 있었습니다. 이러한 확장성과 처리량을 달성한 Dash는 주요 암호화폐 중 하나로 부상했습니다. 그러나 특정 네트워크 트레이드오프가 필요했습니다. 마스터노드는 중앙 집중화 요소를 도입하고 잘 자금 지원된 적대자가 이론적으로 필요한 만큼 마스터노드를 구매하여 특정 네트워크 기능을 제어할 수 있는 공격 표면을 넓혔습니다. Dash는 네트워크 거버넌스를 위한 민주적 모델도 도입하여 네트워크를 실적주의 거버넌스에서 군중의 지혜로 이동시켰습니다. 이는 비숙련 의사결정으로 이어져 네트워크를 약화시킬 수 있습니다. 시간이 지나면서 이러한 네트워크 약점이 시장에 의해 발견되면 가격 안정성을 유지할 수 없게 되어 디지털 자산의 가격 변동성이 발생합니다.

암호화폐가 대중 채택을 달성하려면 가격 안정성, 수수료 일관성, 감사 가능한 프라이버시, 탈중앙화된 거버넌스 사이에서 균형을 이루도록 설계되어야 합니다. 불안정한 가격과 수수료 네트워크는 최종 소비자나 상인이 기존의 성숙한 법정화폐 대안을 선택하는 데 자신감을 주지 않습니다. 확장할 수 없는 네트워크는 많은 사용자가 동시에 네트워크를 사용하는 것을 처리할 수 없으며, 이는 글로벌 규모의 채택을 방해합니다. 일정 수준의 프라이버시가 부족한 네트워크는 사용자의 세부 정보가 암호 분석에 노출되어 검열된 거래와 블랙리스트된 거래 문제를 초래합니다. 일정 수준의 탈중앙화된 거버넌스를 달성하지 못한 네트워크는 부패와 가치 침식에 노출됩니다(부록의 [Xank 프로토콜 특성 비교 차트](#xank-protocol-characteristics-comparison)를 참조하십시오).

이 문서는 Xank 네트워크가 이러한 경쟁적인 네트워크 요소들 사이에서 필수적인 균형을 어떻게 달성하는지 설명합니다. 이를 통해 가장 유용한 안정적인 암호화폐로 자리매김할 수 있는 방법과 그로 인해 모든 암호화폐 중에서 지배력을 갖출 수 있는 방법을 설명합니다.


# Xank 설계 고려사항 : 가격 안정성 구현

가격 안정성을 달성하기 위해 Xank 프로토콜은 주요 암호화폐의 설계 요소를 선택하고 이를 건전하고 안정적인 화폐 개념에 기반한 개념적 프레임워크와 결합했습니다. Xank는 기술적으로 Avalanche 네트워크의 포크로 구현될 것이며, 따라서 Avalanche의 많은 기술적 특성을 유지할 것입니다. 또한 Xank 프로토콜은 Xank가 안정적인 암호화폐로서 기능하고 작동할 수 있도록 필요한 가격 안정성을 달성하기 위해 Avalanche 프로토콜에 다양한 조정과 개선을 통합할 것입니다.

이 섹션에서는 다른 마스터노드 네트워크에서 구현된 탈중앙화된 거버넌스와 자체 자금 조달 예산 시스템의 중요성을 설명합니다. 그런 다음 Xank 네트워크의 첫 번째 소프트 페그로 사용될 IMF의 특별인출권(ISO 4217 통화 코드 XDR (숫자: 960), 약칭 SDR) 도구의 개념을 살펴봅니다. 민주적 거버넌스 모델과 대조적으로, Ray Dalio가 창립한 회사 Bridgewater<sup id="a2">[2](#f2)</sup>의 성공을 이끈 그의 에세이에서 설명된 실적주의 거버넌스 시스템을 구현함으로써 얻을 수 있는 이점과 이를 Xank 네트워크에 적용하는 방법에 대해 고려합니다.


## Xank 네트워크를 위한 Avalanche 프로토콜

Xank는 메타스테이블 메커니즘을 기반으로 구축된 새로운 리더리스 비잔틴 결함 허용 프로토콜의 속성을 상속받습니다.

_리더리스 합의_

Avalanche는 다음 네 가지 기본 프로토콜을 사용하여 합의를 달성합니다 :

1. Slush : 메타스테이빌리티 → 노드는 동료에게 쿼리를 시작하고 다른 노드(빨강 또는 파랑)의 응답에 따라 노드의 색상을 동료들의 다수가 선택한 색상으로 업데이트합니다. 노드가 이러한 쿼리를 수행함에 따라 네트워크는 빨간색 또는 파란색으로 기울어집니다.
2. Snowflake : 비잔틴 결함 허용(BFT) → 비잔틴 결함 허용은 노드의 확신 강도를 캡처하는 카운터를 통해 달성됩니다. 응답이 노드의 원래 색상과 같은 것을 나타내는 성공적인 쿼리가 있을 때마다 카운터가 증가합니다.
3. Snowball : 신뢰 증가 → Snowflake가 노드의 카운터를 각 색상 전환 시마다 재설정하기 때문에, Snowball은 해당 색상에 대한 임계치 결과를 제공한 쿼리 수를 기록하는 신뢰 카운터를 추가합니다. 성공적인 쿼리마다, 노드는 해당 색상에 대한 신뢰 카운터를 증가시킵니다. 일정 횟수의 연속된 쿼리 후에는 신뢰 카운터가 다른 색을 초과하거나 미달할 때 노드가 색을 전환합니다.
4. Avalanche : DAG → 마지막으로, 효율성과 보안을 위해 모든 알려진 거래를 추가하는 동적 추가 전용 방향성 비순환 그래프(DAG)가 있습니다.

작업 증명(Proof-of-Work) 또는 지분 증명(Proof-of-Stake)이 블록 생성을 위해 하나의 검증자를 선출하는 반면, Avalanche는 합의를 위해 어떠한 형태의 리더 선출도 필요로 하지 않습니다. 대신, 본질적으로 메타스테이블한 프로토콜은 한쪽으로 기울어져 모든 노드를 합의로 이끌도록 설계되었습니다. 채굴자, 대표자 또는 특권을 가진 노드가 없기 때문에, Avalanche 프로토콜은 동등한 지위를 가진 노드들의 평등한 네트워크를 만듭니다. 따라서 이 프로토콜은 네트워크의 중앙 인물이나 주요 플레이어에 독립적입니다. 모든 노드는 합의에 동등하게 기여합니다.

_고 처리량과 확장성_

분산화 요소 외에도 Avalanche는 Xank 네트워크에 여러 가지 추가적인 중요한 이점을 제공합니다. 첫째, Avalanche는 널리 인정받는 법정 결제 시스템과 경쟁하는 동급의 다른 시스템보다 훨씬 높은 처리량을 보여줍니다.

*   Bitcoin — 초당 7건의 거래
*   Ethereum — 초당 15건의 거래
*   XRP — 초당 1,500건의 거래
*   EOS — 초당 50건의 거래
*   VISA — 초당 2,000건의 거래
*   PayPal — 초당 193건의 거래
*   Avalanche — 초당 4,500건의 거래 (AWS에 호스팅된 1,000개의 노드 기준)

Xank가 더 널리 채택되고 다양한 목적으로 사용됨에 따라 거래 수는 자연스럽게 증가할 것이며, Xank 네트워크는 증가하는 거래 수를 처리할 수 있는 용량이 필요합니다. 1,000개의 노드로 구성된 테스트 네트워크에서 초당 6,500건의 거래를 달성하고 초당 4,500건의 거래<sup id="a3">[3](#f3)</sup>로 안정화된 Avalanche는 이전의 선례들보다 훨씬 더 많은 거래를 처리할 수 있는 능력을 보여주었습니다. 따라서 Avalanche 프로토콜은 실제로 사용 가능한 암호화폐로 기능하기 위해 높은 처리량과 확장성 모두가 필요한 Xank와 같은 암호화폐에 대한 최적의 솔루션입니다.

_환경 친화적_

비트코인의 작업 증명(Proof-of-Work)은 전체 국가의 전기 사용량에 맞먹는 과도한 전력 소비로 악명 높습니다. 작업 증명과 달리, Avalanche는 친환경적이고 조용하며 효율적인 프로토콜로, 생태계에서 결정이 내려질 필요가 없을 때 에너지를 사용하지 않습니다. Xank의 핵심 신념 중 하나는 세계의 오염을 근절하는 것이며, Avalanche의 지속 가능성은 전력 사용을 줄입니다. 이렇게 함으로써 전력 생산의 필요성이 줄어들고, 이는 대기 오염에 기여하는 온실 가스를 배출하는 과정을 감소시킵니다.

_감사 가능한 프라이버시_

프라이버시는 블록체인에 내장되어 있든 외부 애플리케이션을 통해 가능하든, Xank와 같은 암호화폐에 필수적입니다. Xank는 네트워크 계층에서 구현되는 감사 가능한 프라이버시를 통해 사용자가 신원과 데이터를 보호할 수 있게 하면서도, 전문화된 영지식 증명을 사용하여 공개적으로 감사 가능하도록 할 것입니다. 내장된 프라이버시 기능을 통해 Xank 유니버설 지갑은 사용자의 개인 정보가 원하지 않게 노출되는 것을 방지할 것입니다.

요약하자면, Avalanche는 오늘날 널리 사용되는 다른 프로토콜들보다 우위를 보이는 제2세대 프로토콜입니다. Avalanche는 Xank 네트워크에 탈중앙화, 속도, 보안 및 불정지 상태를 제공하여 Xank가 차세대 안정적인 암호화폐로서의 역할을 할 수 있도록 할 것입니다.


## 자체 자금 조달 재정부 시스템 채택

Xank는 다른 암호화폐들이 직면한 도전을 극복하는 데 중요한 역할을 한 Dash 스타일의 자체 자금 조달 재정부 시스템을 구현할 것입니다. 특히, 네트워크를 구축하면서 탈중앙화된 거버넌스 시스템, 자금 조달, 개발, 시스템 유지 보수 및 프로젝트 확장을 유지하는 도전을 극복하는 데 중요한 역할을 했습니다. Dash 네트워크는 이러한 문제를 해결하려고 시도한 최초의 암호화폐로, 프로젝트의 개발 및 확장 노력이 독립적이고 충분히 자금이 지원되는 자체 자금 조달 재정부 시스템을 성공적으로 구현했습니다. 이는 네트워크의 지속적인 성공을 보장하고, 네트워크가 부패하거나 악의적인 행위자에게 장악되는 위험을 최소화합니다.

Xank가 자체 자금 조달 재정부 시스템을 채택함에 따라, 핵심 프로토콜을 유지하는 동시에 네트워크와 Xank 암호화폐를 홍보하는 임무를 맡은 영리 회사를 설립할 것입니다. 회사의 주요 지침은 네트워크의 소프트웨어 개발, 헌법 개발, 커뮤니티 구축 및 시장 채택 활동에 유익한 활동들입니다. 네트워크에 가치를 더하는 것을 넘어, Xank의 자체 자금 조달 메커니즘은 네트워크의 개발 및 안정성이 기부나 네트워크 주요 토큰 홀더의 선의에 크게 의존하지 않도록 보장합니다. 이는 자체 자금 조달이 되지 않은 다른 암호화폐의 개발 및 업그레이드 과정에서 발생하는 문제를 해결합니다.

Xank는 재단 설립 대신 영리 회사 메커니즘을 사용하기로 결정했습니다. 회사는 초기 개발 및 네트워크 설정에 활발히 참여하겠지만, 네트워크 출시 후에는 네트워크 자금 제안에 대해 개방된 시장에서 경쟁하게 될 것입니다. 이는 네트워크의 실적주의 원칙과 일치하며, 이 목적을 위해 비영리 재단을 설립한 다른 네트워크와 차별화됩니다. 비트코인 및 초기 암호화폐에서 관찰된 바와 같이, 프로젝트 개발을 지원하려는 의도로 설립된 재단들은 플랫폼의 성공과 직접적으로 관련이 없으며, 초기 채택자, 대규모 토큰 홀더 및 재단 회원 자신의 이익을 봉사하는 경향이 있었습니다. 이러한 재단들은 자금을 모으는 데 어려움을 겪었으며, 초기 자금이 소진된 후에는 붕괴되기 쉬웠습니다. 결과적으로 프로토콜 개발은 자원 봉사자와 열정적인 사람들이 맡게 되었으며, 이는 네트워크를 유지하기 위한 노력에도 불구하고, 해당 작업에 전념한 자금이 충분한 네트워크 개발 팀과 경쟁할 수 없었습니다. 개발 팀을 자금 지원 없이 남겨두고 기부금으로만 생존하게 하면 기부자의 중앙 집중화 요소가 네트워크 개발 방향에 영향을 미치게 됩니다. 자기 이익을 추구하는 당사자가 네트워크 개발을 직접 지원할 때, 특히 채굴자 및 거래소와 같은 경쟁 관심사를 가진 경우, 네트워크는 사용자와 다른 이해관계자의 이익과 충돌할 수 있습니다.

일부 프로젝트는 코인을 사전 채굴하거나 사전 출시 판매를 통해 개발 팀을 자금화합니다. 이러한 모금 노력은 네트워크에 특별한 피해를 주지 않으며, 새로운 프로젝트의 출범을 위한 충분한 자금을 제공할 수 있습니다. 그러나 모금된 자금의 실제 가치는 시장 요인의 영향을 받으며, 달성될 자금 수준이나 그 자금 수준이 네트워크의 지속적인 개발 및 미래의 필요를 충족시킬지 여부를 미리 결정할 방법이 없습니다.

Xank는 또한 마스터노드라고 알려진 인센티브를 제공하는 전체 노드 네트워크를 통해 운영될 것입니다. 마스터노드는 네트워크에 투표권을 얻기 위해 담보를 제공해야 합니다. 마스터노드 운영자는 네트워크의 성공에 투자하며, 네트워크 업그레이드와 방향에 대해 투표함으로써 네트워크 개발 과정을 이끌어갈 수 있는 관리자의 역할을 할 수 있습니다. 다른 대체 코인에 채굴 투자를 확장할 수 있는 채굴자와 달리, Xank 마스터노드 운영자는 네트워크 인프라 투자를 다른 암호화폐로 전환할 수 없기 때문에 네트워크에 결속됩니다. 이 메커니즘은 네트워크에 대한 충성도를 올리고 인센티브 역할을 합니다.

각 블록 보상의 일정 비율은 네트워크에 의해 에스크로에 보관되어 네트워크와 넓은 Xank 생태계의 확장 및 지속적인 개발을 위해 할당될 것입니다. 에스크로된 자금은 마스터노드 투표 선호도에 따라 할당될 것입니다. 자금은 불변적으로 Xank 코인 및 네트워크의 홍보 및 개발을 위해 사용되며, 각 사용의 예산은 마스터노드 투표 메커니즘에 따라 개방적이고 투명하게 결정됩니다. 이 과정은 예산 정책 및 지원할 계획이 분산 방식으로 결정되며, Xank 네트워크가 미래의 새로운 시장 요구 사항에 대응하고 새로운 신생 기술을 채택할 수 있도록 보장합니다.

자체 자금 조달 재정부 시스템은 Xank 네트워크가 핵심 개발자를 고용할 수 있도록 보장합니다. 자금은 이 특정 목적을 위해 마스터노드에 의해 분산 투표 결과로 할당될 것이므로, 개발자는 회사가 아닌 실질적으로 네트워크 자체에 의해 고용됩니다. 마스터노드 운영자는 네트워크를 떠날 수 있으며, 동일한 수준의 담보를 제공할 새로운 운영자로 교체될 수 있습니다. 이는 Xank 네트워크가 초기 마스터노드 운영자가 모두 교체되더라도 지속적으로 운영되고 번창할 것임을 의미합니다.


## IMF의 SDR(특별인출권)에 대한 소프트 페깅

Xank 암호화폐는 출시 시 IMF의 SDR에 소프트 페그 기능을 설정하여 IMF 회원국 및 나아가 전 세계에 유용한 안정적인 암호화폐로서의 위치를 확보할 것입니다. Xank의 출시 및 초기 단계에서 SDR은 여러 통화의 묶음을 대표하며, 회원국 중 어느 하나가 중앙은행을 통해 회원국의 통화 공급을 인위적으로 증가시키는 것을 방지하기 때문에 가장 안정적인 국제 예비 자산으로 간주될 수 있습니다. 미래에 SDR보다 더 안정적인 가치 측정 지표가 등장할 경우, Xank 네트워크는 앞서 설명한 마스터노드 투표 시스템을 통해 이를 채택할 수 있습니다.


### **IMF의 SDR 역사 개요**

SDR은 1969년 IMF에 의해 회원국의 예비 자산을 보충하기 위해 만들어진 국제 예비 자산입니다. 2017년 9월 기준으로 2042억 SDR<sup id="a4">[4](#f4)</sup>(2910억 달러 상당)이 생성되어 회원국에 할당되었습니다. SDR은 다른 참가 통화와 자유롭게 교환될 수 있습니다.

SDR은 브레튼우즈 고정 환율 시스템의 맥락에서 보조 국제 예비 자산으로 만들어졌으며, 참여국들은 고정되고 균형 잡힌 환율을 설정하고 유지하기 위해 금과 널리 국제적으로 인정받는 통화를 정부 또는 중앙은행이 보유한 공식 예비 자산 형태로 필요로 했습니다. 그러나 두 가지 주요 예비 자산인 금과 미국 달러의 국제 공급 및 예비가 불충분하여 국제 무역과 금융의 확장이 저해되었습니다. 이로 인해 국제 사회는 IMF의 후원하에 운영될 새로운 국제 예비 자산의 창출을 결정했습니다.

SDR은 주로 보조 예비 자산으로 사용되며, IMF 회원국과 일부 다른 국제 기구 간의 회계 단위로도 사용됩니다.

그 후, SDR이 만들어진 몇 년 후 브레튼우즈 시스템이 붕괴되었고 주요 통화는 변동 환율제로 이동했습니다. 그동안 국제 자본 시장은 정부의 신용도에 기반한 새로운 차입 능력 덕분에 확장되었고, 많은 국가들이 상당한 국제 예비를 축적할 수 있게 되었습니다. 따라서 글로벌 예비 자산으로서의 SDR의 안정성에 대한 의존도가 줄어들었습니다. 2009년 글로벌 금융 위기 시기에 SDR에 대한 의존이 재확립되었습니다. 그 당시 할당된 1826억 SDR은 회원국 예비를 보충하기 위해 글로벌 경제 시스템에 유동성을 제공하는 데 중요한 역할을 했습니다. 그 후 SDR은 세계 경제에서 안정화의 역할을 되찾았습니다.

SDR 자체는 통화로 간주될 수 없으며, SDR을 보유하는 것은 IMF로부터의 예비금 청구권과 동일하지 않습니다. 대신, 이는 IMF 회원국의 '자유롭게 사용 가능한 통화'에 대한 청구를 허용하는 메커니즘의 일부입니다. 이는 SDR 보유자가 합의에 의해 설정된 두 회원국 간의 자발적 교환을 통해 자신의 SDR을 교환하여 다른 회원국의 자유 예비 통화에 대해 청구권을 행사할 수 있음을 의미합니다. SDR 보유자는 또한 강한 외부 포지션을 가진 경우 IMF에 의해 약한 외부 포지션을 가진 다른 회원국으로부터 SDR을 구매하도록 요청받을 수 있습니다.

1969년 SDR 제도가 도입되었을 때, 그 가치는 0.888671그램의 순금에 상응하는 것으로 초기 설정되었습니다. 그 당시 이 비율은 미국 달러의 고정 동등치이기도 했습니다. 1973년 브레튼우즈 협정의 붕괴로 SDR의 환율을 결정하기 위해 통화 바스켓이 사용되었습니다. 최종적으로 결정된 SDR 바스켓은 미국 달러, 일본 엔, 영국 파운드 스털링으로 구성되었으며, 나중에 유로와 중국 위안이 추가되었습니다.

IMF는 SDR의 가치를 미국 달러 기준으로 웹사이트에 게시하며, 그 가치는 매일 결정되고 업데이트됩니다. 이는 런던 시간 정오 무렵에 관찰된 현물 환율을 기준으로 미국 달러로 평가된 각 바스켓 통화의 특정 금액을 합산하여 계산됩니다.

IMF 집행이사회는 매 5년마다 바스켓의 구성을 검토합니다. 이 주기는 회의 간의 기간 동안 중요한 경제 상황이 발생할 경우 변경될 수 있습니다. 집행이사회는 국제 무역 측면에서 다섯 주요 회원국의 위치의 상대적 중요성을 고려하여 바스켓 구성을 결정합니다. 가장 최근에 포함된 통화는 2016년 10월에 포함된 중국 위안(중국 인민폐)으로, 이는 포함 기준을 충족했음을 인정받은 결과입니다. 이는 동일한 해에 채택된 새로운 가중치 알고리즘과도 일치하며, 새로운 가중치 공식에서는 통화 발행국의 수출과 종합 금융 지표에 동등한 비중을 할당하는 방식을 포함했습니다. IMF의 2016년 팩트시트<sup id="a5">[5](#f5)</sup>에 따르면,

> 금융 지표는 동등한 비중으로 다음을 포함합니다: 관련 통화를 발행하지 않는 다른 통화 당국이 보유한 해당 회원국(또는 통화 연합)의 통화로 표시된 공식 예비금, 해당 통화의 외환 거래량, 그리고 해당 통화로 표시된 미결제 국제 은행 부채 및 국제 채무 증권의 합계.

SDR의 가치는 다음과 같은 비율로 가중치가 부여된 다섯 개 주요 통화 바스켓을 기반으로 알고리즘적으로 설정됩니다 :

*   미국 달러 - 41.73% (2010년 검토시 41.9% 대비)
*   유럽 유로 - 30.93% (2010년 검토시 37.4% 대비)
*   중국 위안 - 10.92%
*   일본 엔화 - 8.33% (2010년 검토시 9.4% 대비)
*   영국 파운드 - 8.09% (2010년 검토시 11.3% 대비)

*수치는 IMF의 2016년 팩트시트에서 가져왔습니다.

이 가중치는 다음 검토가 예정된 2021년 9월까지 유지되며, 그 중 경제 및 금융 발전이 글로벌 중요성을 갖는다고 판단될 경우, 그 이전에 검토가 이루어질 수 있습니다.

이 수준의 안정성은 Xank 생태계의 첫 3년을 부트스트랩하기 위해 선택되었습니다.

## Xank와 Bridgewater의 실적주의 시스템

Xank 네트워크는 실적주의적 거버넌스를 채택할 것입니다. 다음의 주요 실적주의 요소들은 Bridgewater의 창립자인 Ray Dalio가 작성한 에세이<sup id="a6">[6](#f6)</sup>에서 발췌한 내용으로, 실적주의적 거버넌스 시스템과 그 핵심 원칙 및 구성 요소의 구현이 Bridgewater의 성공에 어떻게 복잡하게 얽혀 있는지를 설명하고 있습니다. 우리는 또한 이러한 실적주의 원칙들이 Xank 네트워크, 특히 Xank 거버넌스 시스템에서 어떻게 반영될 것인지 설명할 것입니다.

Ray는 다음과 같은 인용문에서 이 아이디어를 요약합니다 :

> 한 문장으로 우리의 성공은 **의미 있는 일**과 **의미 있는 관계**를 목표로 하는 진정한 실적주의를 창출했기 때문이며, 이를 추구하는 방법은 **극단적인 진정성**과 **극단적인 투명성**을 통해 이루어졌습니다.

Xank 거버넌스 시스템을 이해하기 위해 이러한 주요 개념들을 살펴보는 것이 중요합니다. 이러한 단어들을 개별적으로 살펴보겠습니다.


## **아이디어 실적주의(Idea Meritocracy)**

아이디어 실적주의는 최고의 아이디어가 선별되어 승리하는 의사 결정 시스템입니다. 많은 실적주의 시스템이 이론적으로 제시되었지만, 실제로 조직이나 사람들의 네트워크 내에서 이러한 시스템을 구현한 사례는 거의 없습니다. 아이디어 실적주의가 성공하려면 모든 관련자가 다음 세 가지 사항을 준수해야 합니다 :

1. 사람들이 다른 사람들이 보고 싶어 하는 것이 아니라 자신의 솔직한 생각을 모두가 볼 수 있도록 테이블 위에 올려놓아야 합니다.
2. 사람들은 합리적인 상호 작용 과정에서 신중하게 의견을 나눠야 합니다. 이 과정은 사람들이 자신의 사고를 발전시켜 개별적으로 도출할 수 있는 것보다 더 나은 해결책과 결정을 도출할 수 있도록 합니다.
3. 이 과정을 거친 후에도 결정이 해결되지 않으면, 합의된 프로토콜이 있어 사람들이 아이디어 실적주의적인 방법으로 의견 차이를 극복할 수 있도록 돕습니다.

Xank 거버넌스 메커니즘은 이러한 개념을 기반으로 네트워크에 거버넌스 도구를 제공하며, 이 거버넌스 시스템을 프로토콜 수준에서 구현합니다.


### 의미 있는 일

Ray는 의미 있는 일을 다음과 같이 설명합니다 : "사람들이 몰입하고, 흥분하며, 함께 일함으로써 공통의 미션이 되어 훌륭한 결과를 만들어내는 과정이 흥미로운 일." Xank 거버넌스 측면에서 네트워크 참여자들은 네트워크 의사 결정 과정에서 의미 있는 역할을 부여받아 결과가 탈중앙화되고, 아이디어 실적주의 모델과 결합하여 네트워크가 취할 수 있는 최선의 행동을 반영하는 방식으로 작업할 수 있도록 할 것입니다.

### 의미 있는 관계

Ray는 의미 있는 관계를 다음과 같이 설명합니다: "서로의 복지에 진정으로 관심을 가지는 것이 강력한 공동체를 만든다." Xank 거버넌스 측면에서 네트워크의 참여자들은 네트워크의 최선의 이익을 보장하는 결정을 내리는 동시에 네트워크 내 개인을 강화할 수 있는 인센티브를 제공받을 것입니다.

그는 이를 '엄격한 사랑' 접근 방식이라고 설명하며, 결정이 네트워크 전체에 영향을 미친다는 것을 강조합니다. 그는 이것이 네트워크의 성공을 보장하기 위한 중요한 요소임을 발견했습니다. 그는 해군 특수부대(Navy SEALs)와 같이 이 엄격한 사랑 접근 방식을 사용하는 다른 조직에서도 이를 목격했습니다. 이 모델과 접근 방식을 최대한 활용하기 위해서는 두 가지 핵심 요소가 더 필요합니다.


### 극단적인 진정성

여기서 Ray는 극단적인 진정성을 “특히 문제와 약점에 대해 자신의 생각과 질문을 걸러내지 않는 것”으로 설명합니다. 이는 이러한 것들을 공개적으로 이야기함으로써만 효과적으로 해결할 방법을 찾을 수 있기 때문에 이치에 맞습니다. Xank 거버넌스 모델은 모든 거버넌스 수준의 결정이 공개적으로 논의되고 비판된 후에야 결정되고 실행되도록 하여 극단적인 진정성을 준수할 것입니다. 아이디어는 잠재적인 약점이나 문제를 발견하기 위해 테스트 상황과 테스트넷에 배포될 수도 있습니다.


### 극단적인 투명성

극단적인 투명성은 “대부분의 사람들에게 대부분의 것을 볼 수 있는 능력을 부여하는 것”으로 설명됩니다. 사람들에게 필요한 정보를 덜 제공하면 그들이 주변에서 일어나는 일에 대해 자신의 의견을 형성하는 데 필요한 것을 빼앗는 것이 됩니다. 이는 그들을 다른 사람들의 왜곡에 취약하게 만들고, 실적주의에서 배제시킬 것입니다.” Xank 거버넌스 모델에서는 사람들이 아이디어를 공개적으로 논의하고 비판할 수 있을 뿐만 아니라, 의사결정 과정의 모든 단계에서 각 참가자가 의사결정 과정에서 얼마나 큰 비중을 차지하는지 미리 알 수 있게 됩니다.

Ray는 그의 에세이에서 이 시스템이 효율성 측면에서 직관에 반하는 것처럼 보일 수 있지만, 조직 내 의사 결정 과정을 중앙 집중화함으로써 전통적으로 처리되었던 것과는 대조적으로, 이 과정이 놀라울 정도로 효율적이라는 것을 설명합니다. 중앙 집중화된 거버넌스 모델에서는 많은 참가자들이 소외감을 느끼고 조직이 나아가는 방향에 대해 덜 관심을 가지게 됩니다. Ray는 이후 실적주의 거버넌스 모델에 적합한 사람들이 끌리고, 이는 다시 모델로 돌아와 성공을 더욱 보장하게 된다고 설명합니다.

Xank 네트워크는 실적주의에 의해 뒷받침되고, 이러한 시스템이 번창할 수 있게 하는 관련 원칙들을 모방할 것입니다. 이러한 메커니즘이 자리 잡으면, 우리는 네트워크를 발전시키기 위한 모든 개인적 및 집단적 노력을 보상하는 올바른 인센티브의 조합이 존재하기 때문에 가장 재능 있는 참가자들을 네트워크로 끌어들일 것으로 기대합니다. 그들이 네트워크에 가치를 더함에 따라, 이는 모든 Xank 네트워크 참가자들을 강화시키고 네트워크 전체를 강화할 것입니다.


## Xank 프로토콜

Xank 프로토콜은 법정 화폐 형태로 표현된 거래 가치를 안정화하기 위한 자동 보조 메커니즘을 배치할 것입니다. 이 자동 메커니즘은 Xank 준비금에 할당된 자금을 조정하여 환율 가치를 안정화시키는 탈중앙화 자율 조직(DAO)으로 배치될 것입니다.

이 메커니즘은 이 논문 전체에서 Xank 준비금이라고 언급될 것입니다. 이 메커니즘은 Xank Stable Pay(또는 Local Pay) 기능이 사용될 때 네트워크의 소프트 페그 통화의 가치를 거래당 동등한 법정 화폐 가치로 보정하도록 설계되었습니다.

Xank 프로토콜을 고려할 때, Xank는 Avalanche 프로토콜의 포크로 시작되며 따라서 Avalanche 프로토콜과 동일한 기본 기술적 특성을 갖게 될 것이며, 다음과 같은 추가 특성을 통해 Xank 프로토콜을 정의합니다 :

* **Xank 준비금은 블록 보상의 일부로 자금이 지원될 것입니다.** Xank 코인 발행에서 모든 코인의 15%가 Xank 준비금을 지원하며, 이는 Stable Pay 및 Local Pay 거래를 조정하는 탈중앙화 및 자율 메커니즘입니다. Stable Pay 및 Local Pay 거래에 대해서는 다음에서 설명됩니다.

*   **Xank 프로토콜은 기본 자산에 소프트 페그를 지정하고 할당할 것입니다.** Stable Pay 및 Local Pay라는 특수 거래 유형이 네트워크 사용자에게 제공될 것입니다.

Stable Pay 거래 유형은 사용자가 IMF의 SDR, 다른 법정 화폐, 소비자 물가지수(CPI)와 같은 지수 또는 사전 정의된 상품 바구니로 표시된 가치 전송을 할 수 있게 합니다. 시뮬레이션에서 페그될 기본 자산은 Xank 프로토콜의 거버넌스 메커니즘에 따라 네트워크에 의해 결정되고 설정될 것입니다. 출시 시, 소프트 페그는 SDR로 설정되며, Stable Pay 거래의 SDR 가치는 거래가 시작되어 거래 당사자 간의 최종 결제 및 수령에 이르기까지 거래 기간 동안 일정하게 유지됩니다. 초기 페그된 자산이 IMF의 SDR로 설정되어 있으므로, 이 논문의 나머지 부분에서는 예로써 소프트 SDR 페그가 언급될 것입니다.

Local Pay는 사용자가 미국 달러 또는 일본 엔과 같은 국가 통화로 표시된 가치를 전송할 수 있도록 합니다. Local Pay 거래의 법정 화폐 가치는 거래가 시작되어 거래 당사자 간의 최종 결제 및 수령에 이르기까지 거래 기간 동안 일정하게 유지됩니다.

*   **Xank 블록체인은 Oracle 서비스를 사용하여 환율 피드를 모니터링하고 가격을 측정할 것입니다.** Xank-XDR 환율은 실시간 환율 오라클에 의해 Xank 블록체인에 전달됩니다. 이는 네트워크가 중앙 집중화된 장애 지점에 노출되지 않도록 탈중앙화 방식으로 달성할 수 있습니다. 이 과정은 이 논문에서 더 자세히 설명됩니다.
*   **Xank 블록체인은 Stable Pay(또는 Local Pay) 거래당 정확한 XANK 코인 수를 조정하여,** 전송된 가치가 거래 시점의 기본 페그 자산 환율에서 벗어나지 않도록 합니다.
    
    *   Stable Pay(또는 Local Pay) 거래 시점에 XANK 코인이 원하는 SDR 균형 환율보다 **낮은** 가치로 거래되고 있다면, 거래에 참여하는 XANK 코인의 수는 알고리즘적으로 필요한 양만큼 **증가**하여 거래된 가치가 의도한 구매 가격과 동일하게 됩니다. 이 과정은 후반부에서 더 자세히 설명됩니다.
    *   Stable Pay(또는 Local Pay) 거래 시점에 XANK 코인이 원하는 SDR 균형 환율보다 **높은** 가치로 거래되고 있다면, 거래에 참여하는 XANK 코인의 수는 알고리즘적으로 필요한 양만큼 **감소**하여 거래된 가치가 의도한 구매 가격과 동일하게 됩니다. 이 과정은 후반부에서 더 자세히 설명됩니다.
*   **모든 이익과 손실은 준비금에 반환됩니다.** 이 과정은 Xank 준비금에 의해 규제되며, 안정 지불 또는 지역 지불 거래 주기 동안 발생한 XANK 코인의 모든 이익과 손실을 Xank 준비금 기금과 조정하여, 인간의 개입이나 수동 조작 없이 블록체인과 그 준비금 시스템 내에서 가치를 유지합니다. 이 모든 것은 프로토콜 수준에서 처음부터 설정됩니다.
    
    *   거래 과정에서 XANK의 가격이 하락하면 알고리즘 조정에서 발생한 모든 손실은 준비금에서 환불됩니다. 거래 과정에서 XANK의 가격이 상승하면 수신자는 더 적은 코인을 받게 됩니다. 그러나 법정 화폐로 환산한 가치는 송신자가 보낸 것과 여전히 동일하며, 차액은 준비금에 지급됩니다.
*   **극단적 변동성 방어(EVS) 가격 하한 메커니즘은** 경제가 완전히 붕괴되는 것을 방지하기 위해 설정됩니다. 이 메커니즘은 Xank 암호화폐가 재앙적인 실패에서 회복한 후에도 안정적인 암호화폐로 기능할 수 있도록 하며, 이는 극히 드문 일이지만, 정상적인 시기에는 자유 변동 암호화폐로 남아 있게 합니다. 극단적 변동성 방어에 대해서는 이 논문의 후반부에서 더 자세히 설명됩니다.
*   **극단적 변동성 방어(EVS) 가격 상한 메커니즘은** _설정되지 않으며_, 이는 어떠한 상승분도 준비금에 남아있어 준비금 기능의 **안정성과 지속 가능성에 대한 신뢰를 보장합니다.**

이 시점에서 소프트 페깅 메커니즘을 실제로는 자율적으로 조정되는 가격 추적 메커니즘으로 생각하는 것이 유용합니다. 페그는 일반적으로 중앙 집권적 기관이 임의로 설정한 수치를 의미하기 때문입니다. 다음 예를 제공합니다 :

앨리스가 Xank Stable Pay(또는 Local Pay) 기능을 사용하여 밥에게 100.00달러 상당의 XANK 코인을 보내기로 결정하면, 밥이 XANK 코인을 받고 그 코인을 다시 법정 화폐로 교환하려고 할 때 다음 두 가지 시나리오가 발생할 수 있습니다 :


![그림 1](images/Xank-Price-Increase-Scenario_wt-en.jpg "Xank 가격 상승 시나리오")

<div align="center"><strong>그림 1</strong> : Xank 가격 상승 시나리오</div>

**시나리오 A**

> 앨리스가 거래를 보낸 시점에 XANK의 가격은 10.00달러 USD였습니다. 이는 앨리스가 100.00달러 USD의 가치를 달성하기 위해 밥에게 10개의 XANK 코인을 보내야 한다는 것을 의미합니다 (10 XANK = 100.00달러 USD). 밥이 거래를 받는 동안 XANK의 가치가 두 배로 상승하여, 이제는 100.00달러 USD의 가치를 달성하기 위해 5개의 XANK 코인만 필요하게 됩니다. 이 시나리오에서 프로토콜은 수신 지갑에서 5개의 XANK 코인을 차감하여 Xank 준비금 시스템에 넣습니다. 밥이 Xank를 법정 화폐로 전환할 때, 그는 100.00달러 USD 상당의 법정 화폐를 받게 됩니다. 앨리스와 밥의 안정적인 암호화폐 거래 필요가 충족되었습니다.



![그림 2](images/Xank-Price-Decrease-Scenario_wt-en.jpg "Xank 가격 하락 시나리오")

<div align="center"><strong>그림 2</strong> : Xank 가격 하락 시나리오</div>


**시나리오 B**

> 앨리스가 거래를 보낸 시점에 XANK의 가격은 10.00달러 USD였습니다. 이는 앨리스가 100.00달러 USD의 가치를 달성하기 위해 밥에게 10개의 XANK 코인을 보내야 한다는 것을 의미합니다 (10 XANK = 100.00달러 USD). 밥이 거래를 받는 동안 XANK의 가치가 절반으로 떨어져, 이제 100.00달러 USD의 가치를 달성하기 위해 20개의 XANK 코인이 필요하게 됩니다. 이 시나리오에서 프로토콜은 Xank 준비금 시스템에서 10개의 추가 XANK 코인을 추출하여 수신 지갑에 추가합니다. 밥이 Xank를 법정 화폐로 전환할 때, 그는 100.00달러 USD 상당의 법정 화폐를 받게 됩니다. 앨리스와 밥의 안정적인 암호화폐 거래 필요가 충족되었습니다.



![그림 3](images/Xank-Universal-Wallet-wt_en.jpg "지갑 내 Stable/Local Pay 전환이 가능한 Xank 유니버설 지갑")

<div align="center"><strong>그림 3</strong> : 지갑 내 Stable/Local Pay 전환이 가능한 Xank 유니버설 지갑</div>

**시나리오 C**

> 앨리스가 밥에게 거래를 보내고자 할 때 XANK의 가격은 9.99달러 USD입니다. 이는 앨리스가 100.00달러 USD의 가치를 달성하기 위해 밥에게 10.00728개의 XANK 코인을 보내야 한다는 것을 의미합니다 (10.00728 XANK = 100.00달러 USD). 앨리스는 이번 전송에 일반 XANK 코인을 사용하기로 선택했습니다. 또한, 전송 방법으로 일반 전송 대신 Stable Pay를 사용하려고 합니다. Xank 유니버설 지갑은 지갑 내 Stable Pay 전환을 지원하며, 이는 여러 Xank 지갑을 연결할 수 있는 전화번호 기반 지갑이기 때문에 가능합니다. 이 지갑은 일반 XANK와 Stable/Local Pay 코인을 모두 보유할 수 있습니다. 앨리스는 Xank 유니버설 지갑을 사용하여 법정 화폐 은행 계좌 및 신용/직불 카드를 지원하기 때문에 쉽게 법정 화폐를 전송할 수 있습니다.


### Stable Pay 기능

위 시나리오에서 설명한 이 프로토콜 기능은 Stable Pay라고 하며 선택적 기능입니다. 이는 송신자와 수신자가 기본 소프트 페그에 연결된 안정적인 거래를 위해 프로토콜을 사용할지 아니면 기본 자산에 연결되지 않은 원래의 XANK 코인 거래를 할지 상호 합의할 수 있음을 의미합니다. Stable Pay는 국제 거래 시 통화 변동성을 완화하기 위해 종료 날짜 없이 작동하는 FX 선도 계약과 매우 유사하게 작동합니다. 우리는 이 귀중한 서비스를 암호화폐 수준으로 가져와 그와 관련된 높은 비용을 제거하고자 합니다.


### Local Pay 기능

Local Pay는 Stable Pay와 동일하게 작동하지만, 안정적인 가치를 위해 IMF SDR 대신 지원되는 지역 법정 화폐를 사용합니다. 이 기능은 비교적 안정적인 지역 통화(예: G20 국가의 국가 통화)로 거래하려는 사람들에게 유용합니다. Local Pay를 사용하면 송신자와 수신자가 안정적인 거래에 사용할 통화를 상호 결정합니다. 두 사람이 미국 달러를 Local Pay 통화로 선택하면 거래는 미국 달러로 표시된 소프트 페그 가치를 유지합니다. Stable Pay와 마찬가지로 Local Pay는 선택적 기능이므로 사용자는 안정성 요소 없이 원래의 Xank 코인 거래를 수행할 수 있습니다.


### Xank 지분 증명(PoS) 거버넌스

네트워크 전체의 합의와 보안을 달성하기 위해 작업 증명(PoW) 채굴 합의 메커니즘을 사용하는 비트코인과 Dash와 달리, Xank는 새로운 메타스테이블 합의 프로토콜인 Avalanche 프로토콜을 구현할 것입니다. Avalanche를 구현함으로써 Xank 네트워크 참여자들은 PoW 구현에서 발생하는 문제, 예를 들어 51% 채굴 공격과 빠르게 구식이 되어 과도한 전기 소비를 특징으로 하는 하드웨어 투자 문제를 피할 수 있습니다. 합의는 Avalanche 프로토콜 군을 통해 달성되지만, 거버넌스는 지분 증명 마스터노드 시스템의 형태를 취합니다.

Xank 생태계에는 한 가지 형태의 스테이킹이 있을 것입니다 :

*   **마스터노드 스테이킹** - 마스터노드 운영자는 Xank 네트워크에서 투표 권한을 부여받기 위해 마스터노드를 생성할 때 1,000 XDR 상당의 XANK 코인을 스테이킹하여 Xank 마스터노드를 운영합니다. Xank 마스터노드 운영자는 **관료(Governor)** 라고도 하며 네트워크로부터 인센티브를 받습니다.

마스터노드 스테이킹에 XANK 코인 수 대신 XDR을 회계 단위로 사용하는 이유는 Xank 네트워크에서 마스터노드를 운영하려는 후발 주자에게 잠재적인 진입 장벽을 제거하기 위함입니다. 마스터노드 스테이킹 요건으로 1,000 XANK를 설정하면 초기에 마스터노드를 스테이킹하기는 쉽지만, 가격이 상승함에 따라 마스터노드를 스테이킹하는 것이 점점 더 어려워질 것입니다. 마스터노드 스테이킹 요건으로 1,000 XDR을 설정하면 각 마스터노드에 필요한 XANK의 수는 변동하지만, 법정 화폐로서의 가치는 항상 일정하게 유지될 것입니다. 우리는 이 시스템이 후발 투자자들이 관료로 네트워크에 참여하기 더 쉽게 만들 것이라고 믿습니다. 비인플레이션 화폐를 구축하는 것이 암호화폐의 중요한 목표이기 때문에 이것이 더 합리적이라고 생각합니다.

초기 투자자의 공정성에 관해서는, 초기 투자자는 Xank 가격이 상승하면 마스터노드를 소유하고 있든 아니든 크게 보상받을 것입니다. 그러나 가격이 너무 올라 후발 투자자들이 Xank의 유일한 의사결정 기구에 참여할 수 없게 되면, 초기 투자자들만이 Xank 블록체인을 관리하는 주체가 될 것입니다. 새로운 관료의 부족은 오늘날 대부분의 마스터노드 네트워크에서 관찰되는 신선한 혈액 공급이 없는 죽은 통제 기구로 이어질 수 있습니다.


### Xank 준비금

암호화폐의 폭넓은 채택을 방해하는 주요 요인 중 하나는 법정 화폐 및 기타 전통적 자산과 비교할 때의 높은 변동성입니다. 이러한 변동성은 암호화폐가 교환의 매개로 쉽게 사용될 수 없다는 것을 의미하며, 이는 가치가 가격 변동에 노출되기 때문입니다. 가격 변동은 중장기적으로만 발생하는 것이 아니라, 거래가 완료되거나 암호화폐가 법정 화폐로 전환되는 동안에도 발생할 수 있습니다. 암호화폐가 상품 및 서비스 결제에 사용될 때, 거래 중 변동성은 수신자를 위험에 노출시킬 수 있습니다.

Xank의 제안된 해결책은 안정화 메커니즘으로 작동하는 자율 준비금 기금을 설립하는 것입니다. 이 메커니즘을 통해 네트워크 사용자는 거래 시 Stable Pay(또는 Local Pay) 기능을 활성화할 수 있습니다. 이러한 거래는 자율 준비금 시스템에 의해 조정되며, 기본 자산이나 법정 화폐 가치 측면에서 균형이 이루어집니다. 따라서 송신자와 수신자는 Stable Pay(또는 Local Pay) 기능을 사용하여 법정 화폐 가치로 합의할 수 있으며, 프로토콜은 송신자가 법정 화폐로 안정적인 금액을 보내고 수신자가 합의된 법정 화폐 가치에 상응하는 XANK 코인을 받도록 보장합니다. 이러한 유형의 거래에서 발생하는 XANK 코인의 차이는 준비금 메커니즘을 통해 조정됩니다.

*   거래가 Xank-XDR 환율 하락으로 인해 더 많은 XANK 코인을 필요로 할 경우, 준비금 시스템은 법정 화폐 가치로 거래를 조정하기 위해 필요한 양의 XANK를 제공합니다.
*   Xank-XDR 환율 상승으로 인해 거래에 더 적은 XANK 코인이 필요할 경우, 잉여 XANK 코인은 법정 화폐 가치로 거래를 조정하기 위해 준비금 시스템에 의해 회수됩니다.

Xank 준비금은 Stable Pay(또는 Local Pay) 기능이 선택될 때 안정적인 거래 기능 목표를 달성하기 위해 충분한 자금을 유지할 수 있도록 Xank 프로토콜 내의 경제적 인센티브와 정렬되어야 합니다. 항상 준비금에 있는 XANK 코인의 양은 준비금이 제공하는 보조금의 비용보다 많아야 합니다. 보조금의 비용은 Stable Pay(또는 Local Pay) 활성화된 거래량에 XANK 코인의 가치를 곱한 값에 비례합니다. 보조금 비용은 Xank 생태계 전반에 걸쳐 제공되는 인센티브와 정렬되어야 합니다. 모든 프로토콜 구성 요소 - 시민, 관료, 준비금 및 재정부 (일부 구성 요소는 후반부에서 더 논의될 예정) -는 시스템이 지정된 대로 작동하기 위해 균형점으로 수렴해야 합니다.


![그림 4](images/Xank-Coin-Supply-en.jpg "블록 보상으로 생성된 Xank 준비금")

<div align="center"><strong>그림 4</strong> : 블록 보상으로 생성된 Xank 준비금</div>

마스터노드 수는 경제에서 유통되는 XANK 코인의 수에 직접적인 영향을 미칩니다. 마스터노드의 이해관계는 Xank 프로토콜의 준비금 및 재정부 시스템과 일치해야 합니다. 이미 언급했듯이, Xank는 자율적 자체 자금 조달 네트워크로 성공한 후 Dash 스타일의 마스터노드 네트워크를 구현할 것입니다. 위에서 설명한 균형 경향은 Xank 생태계의 어떤 플레이어나 파벌도 네트워크에 대한 중앙 권력을 확립하고 행사할 수 없도록 하기 위해 필요합니다.

이를 달성하기 위해, 우리는 블록 보상에서 자금을 다음과 같이 할당할 것입니다 :

**1.	관료** - 전체 블록 보상의 35%

* Xank 관료는 1,000 XDR을 담보로 스테이킹한 Xank 노드 운영자로, Xank 마스터노드 운영자로 자격을 갖추게 됩니다. 마스터노드 운영자는 재정부 자금 사용 방법에 대한 투표권을 가질 수 있습니다. 마스터노드 운영자는 또한 프로토콜 수정, 업그레이드 및 기본 자산 페깅 메커니즘에 대한 제안에 투표할 수 있는 권리를 설정하여 시장 상황, 네트워크 견고성 및 네트워크 경쟁력에 대응할 수 있습니다. 관료는 항상 1,000 XDR에 해당하는 원래의 XANK 코인을 담보로 유지해야 하며, 이 잔액이 부족할 경우 모든 투표권을 상실하게 됩니다. 각 블록 보상의 35%는 네트워크의 관료들에게 배분될 것입니다. 운영자가 획득할 수 있는 마스터노드의 수에는 상한이 없지만, 자기주권 신원(SSI) 시스템을 통해 운영자가 몇 개의 마스터노드를 운영하든 상관없이 단일 평판 가중 투표의 권한만을 행사할 수 있도록 보장할 것입니다. 보상 메커니즘은 Xank 준비금 풀의 관료 부분에 대한 최소 5%의 코인 공급량을 항상 에스크로로 유지할 것입니다. 이에 대해서는 이 논문 후반부에서 다룰 것입니다.

**2.	시민** - 전체 블록 보상의 35%

* Xank는 많은 특별한 기능을 가지고 있지만, 암호화폐는 그 채택률만큼만 가치가 있습니다. 그래서 우리는 로열티 포인트 환급 프로그램을 통해 시장 채택을 위해 코인 발행량의 35%를 시민 풀에 할당했습니다. 시민 풀은 상인, 소비자, Xank라는 세 가지 당사자가 Xank의 독특한 로열티 환급 구조뿐만 아니라 네트워크가 미래에 구현하기로 선택한 기타 시장 채택 전략으로부터 혜택을 받을 수 있게 합니다. 예를 들어, 추후 단계에서 네트워크는 모든 시민이 최소한의 소득을 받을 수 있도록 보장하기 위해 일부 정부가 채택한 것과 유사한 보편적 기본 소득(UBI) 이니셔티브를 시민 풀을 사용하여 자금을 지원하는 결정을 내릴 수 있습니다. 더 많은 기업과 소비자가 Xank의 채택 전략의 장점을 보고 참여하게 되면, 사용은 자연스럽게 증가할 것이라고 믿습니다. 그런 다음 Xank 네트워크는 독특하게 설계된 프로토콜일 뿐만 아니라 널리 사용되는 암호화폐로 성장할 것입니다. 보상 메커니즘은 Xank 준비금 풀의 시민 부분에 대한 최소 5%의 코인 공급량을 항상 에스크로로 유지할 것입니다. 이에 대해서는 이 논문 후반부에서 다룰 것입니다.

**3.	Xank 준비금** - 전체 블록 보상의 15%

* XANK 코인의 가치를 XDR, 법정 화폐, 또는 네트워크가 안정적인 거래 기능을 위해 선택한 기본 자산의 가치에 맞춰 조정하려면 준비금에서 거래를 보조해야 합니다. Xank 준비금 기금은 자율적으로 운영되며 각 블록 보상의 일정 비율로 자금을 지원받게 됩니다. Xank 프로토콜의 Xank 준비금 사용은 프로토콜이 죽음의 나선이나 안정적인 거래 기능을 유지하는 데 반대 효과를 미치는 긍정적 피드백 루프에 저항할 수 있도록 설계되었습니다. 기본적으로 각 블록 보상의 15%가 Xank 준비금을 위해 배분될 것입니다. 세계 대부분의 정부 운영 중앙 은행은 해당 통화를 안정화하기 위해 10% 미만의 준비금을 유지합니다. 거래 수명 주기 동안 XANK 가격이 상승할지 하락할지 예측할 수 없으므로, 거래가 시작되고 끝나는 가격 수준이 다르기 때문에, 준비금은 전체 코인 공급량의 15%를 유지할 것으로 예상되며, 이는 대부분의 정부 운영 중앙 은행의 준비금보다 높은 비율입니다.

**4.	Xank 재정부** - 전체 블록 보상의 15%

* Xank 재정부는 네트워크 개발 및 성장을 위한 자체 자금 조달 메커니즘입니다. Xank 재정부는 코드 개발, 코드 감사, 마케팅, 번역가 및 Xank 헌법에 명시된 기타 모든 자금 필요에 기여할 것입니다. 자금 할당 및 사용될 자금의 비율은 각 마스터노드 투표 라운드에 따라 달라질 것입니다. Xank 헌법에 대해서는 이 논문 후반부에서 더 자세히 설명합니다. 각 블록 보상의 15%가 Xank 재정부에 배분될 것입니다. 보상 메커니즘은 Xank 준비금 풀의 재정부 부분에 대한 최소 5%의 코인 공급량을 항상 에스크로로 유지할 것입니다. 이에 대해서도 이 논문 후반부에서 다룰 것입니다.


### 시장 진출 전략

Xank 코인의 시민 풀은 기업과 소비자가 Xank 네트워크에 참여하도록 장려하는 대규모 채택 프로그램에 사용될 것입니다. 그 예로 Xank 로열티 프로그램이 있습니다. 이 프로그램은 Xank가 상인 X와 제휴하여, 소비자가 Xank 지갑을 사용해 상인 X의 포인트를 Xank 코인으로 교환할 수 있도록 하는 방식입니다. 포인트를 Xank 코인으로 교환한 소비자는 Xank를 보유하거나, 현지 거래소에서 현금화하거나, Xank 코인을 받아들이는 상점에서 사용할 수 있습니다. Xank는 상인 X의 포인트를 Xank 코인으로 교환받은 후, 해당 포인트를 소각하여 상인 X가 로열티 프로그램의 부채를 삭감할 수 있도록 합니다. 포인트가 소멸되는 대가로 상인 X는 모든 결제 단말기에서 Xank를 결제 수단으로 받아들일 것입니다.


### Measuring the Exchange Rate

In order for the Xank Reserve system to function autonomously and in real time, the Xank blockchain will be informed of the Xank-XDR exchange rate by using exchange rate feeds that are generated by an oracle system. It is important to note that the XANK coin will be a free-floating cryptocurrency with built-in stable transactions functionality that is derived from using the Stable Pay (or Local Pay) feature. The XANK coin will be exposed to supply and demand market forces and will vary in value and be priced accordingly and independently on all exchanges where it will be listed. This does not in any way diminish the usefulness of the Stable Pay (or Local Pay) feature which, when chosen, provides the stable cryptocurrency functionality that is required for certain types of transactions. 


#### <span style="text-decoration:underline;">SDR and Currency Feeds</span>

The Xank-XDR exchange rate measurement must take into account various data feeds. In particular, the exchange rate calculation requires the SDR and all its component basket currencies to be tracked. The resultant real-time data needs to be independently and autonomously fed to the blockchain as needed for Stable Pay (or Local Pay) functionality. The data will be handled at the masternode level, and the established rate will be calculated and entered into each Xank block to be made available to the whole network.

Seeing as the SDR rate is measured against a basket of weighted currencies and is announced and published by the IMF on its website on a daily<sup id="a7">[7](#f7)</sup> basis, this daily feed will be fed directly into the oracle system and used as a basis for calculating the Xank-XDR exchange rate. 

As the currency value of the SDR is determined by summing the values in U.S. dollars based on market exchange rates of a basket of major currencies, a further step is required to establish the Xank-XDR exchange rate. The exchange rate calculation needs to track the exchange rate of the XANK coin against the fiat currencies that are included in the SDR basket. The oracle system needs to establish feeds from exchanges where the XANK coin is listed, traded and denominated in the U.S. dollar, Euro, Japanese yen, British pound sterling, and the Chinese renminbi. These feeds will be made available during the launch of the Xank blockchain, and a voting mechanism will be outlined in the Xank Constitution should more reliable feeds become available or should more feeds be added for better aggregation calculations ensuring the robustness of the feed information. Should the Xank network also decide as a whole to change the Stable Pay peg away from the SDR and choose a different underlying asset value, the same voting mechanism will be enacted for the provision of the new feeds, and the oracle system will be updated.

At the time of the launch of the network and during the infancy of the network, should Xank only trade on exchanges that only provide non-fiat cryptocurrency trading pairs, such as the Xank-BTC or Xank-ETH pairs, the fiat denominated rates can be extrapolated from the selected cryptocurrency rate against the corresponding fiat rates that make up the SDR basket. 


#### <span style="text-decoration:underline;">Oracle System</span>

These feeds will be provided by purpose-built oracles that will function autonomously and transparently. Oracle input streams will be known and their code will be made publicly available and open to scrutiny. This level of openness and autonomy will assure that they are tamper proof and trusted. The oracle system will be implemented at the Xank masternode level, ensuring that the feeds will be supported by the robust network infrastructure. 


#### <span style="text-decoration:underline;">Oracle Feed Redundancy</span>

Should any of the public feeds that the oracle system rely upon experience failure or permanent loss of data, such as in the case of a sustained denial-of-service attack, regional IP censorship or geo-blocking, permanent shutdown of data feed, or any other temporary or permanent feed interruption, the masternodes will be able to rely on further layers of redundancy - Masternode Feed Aggregation, Masternode Direct Manual Feed Input, and Staker Oracle Feed Data Corruption Assurance.

*   **Masternode Feed Aggregation** - should autonomous feed interruptions or losses affect 49% or less of the masternode network, such as in the case where certain oracle feeds are geo-blocked in certain regions, the affected masternodes can retrieve feed data from the unaffected masternodes on the network that are still able to retrieve the oracle feeds. The affected masternodes will aggregate the information and feed it back into the network.
*   **Masternode and Staker Feed Aggregation** - should autonomous feed interruptions or losses affect 50% or more of the masternode network and less than 49% of the Staker’s node software, such as in the case where certain oracle feeds are geo-blocked in certain regions, the affected masternodes can retrieve feed data from the unaffected masternodes and unaffected Staker nodes on the network that are still able to retrieve the oracle feeds. The affected masternodes will aggregate the information and feed it back into the network.
*   **Masternode Direct Manual Feed Input** - should autonomous feed interruptions or losses affect 50% or more of the masternode network and 50% or more of the Staker’s node software resulting in the autonomous nature of the feeds becoming unreliable, such as in the case of the feeds being shut down or discontinued, the masternode network will be allowed to provide Direct Manual Feeds until reliable autonomous feeds can be reestablished. Such an event will also activate a daily masternode voting mechanism where masternodes will vote on whether a new feed needs to be permanently established to replace the defunct feed, and if so, which is the preferred new feed. This mechanism will be activated in accordance with the voting rules that are established in the Xank Constitution. When the Direct Manual Feed mode is activated, the Xank masternode network will aggregate manual masternode feeds along with any remaining autonomous feeds still available to any of the masternodes to derive the desired exchange rate.
*   **Staker Oracle Feed Data Corruption Assurance** - As a further redundancy measure, Staker nodes will be incentivised to monitor the network for corrupt or compromised feeds. Staker node software will be able to monitor individual masternode feeds and alert the network of Staker nodes if any masternodes are corrupted or compromised, where votes are weighted according to stake ownership. Should corrupt or compromised masternodes be identified, a vote can be arranged among the Staker network to suspend the masternode from the network until the problem is resolved and uncorrupted and uncompromised feeds can be resumed from the masternode in question. This mechanism can act as a counter to any masternode collusion as the Staker network is incentivized to preserve the long-term viability and robustness of the network and to retain its decentralized nature. It should be noted that this mechanism will not punish masternodes that are not able to retrieve oracle feed information. Rather, this mechanism will only be activated should a masternode provide feed data that is not consistent with oracle feeds or masternode aggregation data and is a deliberate or compromised attempt to provide the network with false information.


### Stable Pay (or Local Pay) Transaction Lifecycle

To calibrate the count of Xank coins per Stable Pay (or Local Pay) transaction, the Xank protocol defines the lifecycle of a transaction that meets the following four explicit stages:

*   **Stable Pay (or Local Pay) Coin Send** - for example, Alice sends 100 XDR worth of XANK coins to Bob. They have agreed to use the Stable Pay (or Local Pay) method for this transaction. 
*   **Stable Pay (or Local Pay) XDR Calculation** - Alice’s wallet software uses data provided to the Xank blockchain by the Oracle system as implemented by the masternodes and makes her aware of the required amount of XANK coins that is equivalent to 100 XDR as agreed. She selects the required amount of Xank and performs a Stable Pay send transaction. Bob receives the amount of XANK coins that is equivalent to the 100 XDR as agreed. As the transaction is entered into the blockchain, the coins are flagged and are known to the network as Stable Pay (or Local Pay) coins. 
*   **Stable Pay (or Local Pay) Coin Sell** - at a future point in time, Bob is ready to sell the coins he received from Alice. Seeing as these coins are flagged as Stable Pay (or Local Pay) coins, he will receive the denominated amount of XANK coins in return when he sells his coins. The terminology of sell here simply refers to Bob using the Stable Pay (or Local Pay) coins he received in a subsequent transaction that includes these coins. When Bob sends this ‘sell’ transaction, the sent amount will be denominated in XDR value in his wallet software, and he can send up to the full 100 XDR amount that he currently holds. The Stable Pay feature will be activated, and the required amount of XANK coins will be sent to the receiver to fulfill the 100 XDR rate at the time of the sell transaction.
*   **Stable Pay (or Local Pay) XDR Normalization** - After the sale, the coins are no longer pegged as Stable Pay (or Local Pay) coins on the network, and the coins become ‘free-floating’ XANK coins once again.


### Xank Multi-currency Support

The Xank blockchain is a closed network that is disconnected from the world. It cannot retrieve the daily SDR price from the official IMF SDR website, nor is it going to manually pull data from the exchanges on which Xank is listed to calculate the Xank-XDR rate for Stable Pay (or Local Pay) transactions. Thus, the Xank network requires an oracle system to provide the SDR rate and the price of the XANK coin for the Xank blockchain.

Every day at noon (London time), the IMF publishes the SDR rate on its website. Xank’s oracle system will feed the SDR rate to the Xank blockchain so that it has the numbers it needs to fulfill Stable Pay (or Local Pay) calibrations. It is important to note that the SDR rate will not only be pulled from the official IMF website, but also from multiple other sources. This is important because a single-source feed, if compromised, has the potential to corrupt the entire network. Here, the oracle provides the Xank blockchain with real-world information, that is, the SDR rate.

However, that is only one part of the equation. In order to determine the Xank-XDR rate, we also need the price of the XANK coin. Let’s say that Xank is listed on 10 different cryptocurrency exchanges in locations around the world. The oracle would establish feeds from all 10 exchanges and calculate the average Xank price to be used in determining the Xank-XDR rate.

Similar to the SDR rate, the oracle will draw data from multiple exchanges, and not just one. The reason is twofold. First, one exchange does not accurately represent the global price of the XANK coin. Second, if the one exchange were to suffer an attack or any sort of downtime, the XANK coin’s price may be misrepresented or not retrievable at all. Here, the oracle provides the Xank blockchain with real-world information, that is, the price of the XANK coin.

Let’s look at XDR/USD rate in the chart below. This should give you an idea of how the SDR rate (“XDR/USD Rate”) and the price of the XANK coin (“Xank Price in USD”) are used to calculate the Xank-XDR rate (“Xank Price in SDR”). Note that this local currency conversion takes place in the wallet and not in the protocol.

|                       |  Transaction  | Price Increase |  Scenario   | Price Decrease |   Scenario   |
| --------------------- | :----------: | :------------: | :---------: | :------------: | :----------: |
|                       | Start |  1 Year High   | 1 Year Low  |  1 Year High   |  1 Year Low  |
| XDR/USD Rate          |   1.38195    |    1.45998     |   1.37778   |    1.45998     |   1.37778    |
| Xank Price in USD     |    \$10.00    |     \$20.00     |   \$20.00    |     \$5.00      |    \$5.00     |
| Xank Price in XDR     |     7.24     |      13.7      |    14.52    |      3.42      |     3.63     |
| Stable Pay in USD     |   \$100.00    |    \$105.65     |   \$99.70    |    \$105.65     |    \$99.70    |
| Stable Pay in XDR     |    72.36     |     72.36      |    72.36    |     72.36      |    72.36     |
| No. of XANK Coins     |      10      |  5.282318463   | 4.984912623 |  21.12927385   | 19.93965049  |
| Xank Reserve Position |      0       |  4.717681537   | 5.015087377 |  -11.12927385  | -9.939650494 |
|                       |              |                |             |                |              |
| XDR/EUR Rate          |   1.22087    |    1.16335     |   1.16335   |    1.16335     |   1.16335    |
| Xank Price in EUR     |   € 10.00    |    € 20.00     |   € 20.00   |     € 5.00     |    € 5.00    |
| Xank Price in XDR     |     8.19     |     17.19      |    17.19    |      4.3       |     4.3      |
| Stable Pay in EUR     |   € 100.00   |    € 95.29     |   € 95.29   |    € 95.29     |   € 95.29    |
| Stable Pay in XDR     |    81.91     |     81.91      |    81.91    |     81.91      |    81.91     |
| No. of XANK Coins     |      10      |  4.764430283   | 4.764430283 |  19.05772113   | 19.05772113  |
| Xank Reserve Position |      0       |  5.235569717   | 5.235569717 |  -9.057721133  | -9.057721133 |
|                       |              |                |             |                |              |
| XDR/RMB Rate          |   9.60669    |    9.66967     |   9.0478    |    9.66967     |    9.0478    |
| Xank Price in RMB     |   ¥100.00    |    ¥200.00     |   ¥200.00   |     ¥50.00     |    ¥50.00    |
| Xank Price in XDR     |    10.41     |     20.68      |    22.1     |      5.17      |     5.53     |
| Stable Pay in RMB     |  ¥1,000.00   |   ¥1,006.56    |   ¥941.82   |   ¥1,006.56    |   ¥941.82    |
| Stable Pay in XDR     |    104.09    |     104.09     |   104.09    |     104.09     |    104.09    |
| No. of XANK Coins     |      10      |   5.03277924   | 4.709114169 |  20.13111696   | 18.83645668  |
| Xank Reserve Position |      0       |   4.96722076   | 5.290885831 |  -10.13111696  | -8.836456678 |
|                       |              |                |             |                |              |
| XDR/JPY Rate          |  156.89423   |   161.49191    |  152.41589  |   161.49191    |  152.41589   |
| Xank Price in JPY     |  ¥1,000.00   |   ¥2,000.00    |  ¥2,000.00  |    ¥500.00     |   ¥500.00    |
| Xank Price in XDR     |     6.37     |     12.38      |    13.12    |      3.1       |     3.28     |
| Stable Pay in JPY     |  ¥10,000.00  |   ¥10,293.04   |  ¥9,714.56  |   ¥10,293.04   |  ¥9,714.56   |
| Stable Pay in XDR     |    63.74     |     63.74      |    63.74    |     63.74      |    63.74     |
| No. of XANK Coins     |      10      |  5.146521641   | 4.857281558 |  20.58608656   | 19.42912623  |
| Xank Reserve Position |      0       |  4.853478359   | 5.142718442 |  -10.58608656  | -9.429126234 |
|                       |              |                |             |                |              |
| XDR/KRW Rate          |  1559.10086  |   1594.68606   | 1513.16261  |   1594.68606   |  1513.16261  |
| Xank Price in KRW     |   ₩10,000    |    ₩20,000     |   ₩20,000   |     ₩5,000     |    ₩5,000    |
| Xank Price in XDR     |     6.41     |     12.54      |    13.22    |      3.14      |     3.3      |
| Stable Pay in KRW     |   ₩100,000   |    ₩102,282    |   ₩97,054   |    ₩102,282    |   ₩97,054    |
| Stable Pay in XDR     |    64.14     |     64.14      |    64.14    |     64.14      |    64.14     |
| No. of XANK Coins     |      10      |  5.114120904   | 4.852677106 |  20.45648362   | 19.41070843  |
| Xank Reserve Position |      0       |  4.885879096   | 5.147322894 |  -10.45648362  | -9.410708426 |
|                       |              |                |             |                |              |
| XDR/TWD Rate          |   42.80559   |    43.36092    |  41.99386   |    43.36092    |   41.99386   |
| Xank Price in TWD     | NT\$1,000.00  |  NT\$2,000.00   | NT\$2,000.00 |   NT\$500.00    |  NT\$500.00   |
| Xank Price in XDR     |    23.36     |     46.12      |    47.63    |     11.53      |    11.91     |
| Stable Pay in TWD     | NT\$10,000.00 |  NT\$10,129.73  | NT\$9,810.37 |  NT\$10,129.73  | NT\$9,810.37  |
| Stable Pay in XDR     |    233.61    |     233.61     |   233.61    |     233.61     |    233.61    |
| No. of XANK Coins     |      10      |  5.064866528   | 4.905184113 |  20.25946611   | 19.62073645  |
| Xank Reserve Position |      0       |  4.935133472   | 5.094815887 |  -10.25946611  | -9.620736451 |

Looking at the first example of the XDR/USD rate, we can see that the oracle system makes it possible for the network to retrieve the values for the XDR/USD Rate and the Xank price in USD, both of which are necessary to calculate the Xank price in SDR that is required for Stable Pay transactions.

SDR: Special drawing rights (ISO 4217 currency code XDR) are supplementary foreign-exchange reserve assets defined and maintained by the International Monetary Fund (IMF).


### Extreme Volatility Safeguard (EVS) Price Floor Mechanism

![Figure 5](images/Xank-Extreme-Volatility-Safeguard_Simplified_wh-en.jpg "Extreme Volatility Safeguard (EVS) Price Floor Mechanism")

<div align="center"><strong>Figure 5</strong>: Extreme Volatility Safeguard (EVS) Price Floor Mechanism</div>

The Xank Treasury has a minimum limit set to 5% of the total coin supply of Xank. Therefore when the Xank Treasury falls beneath that level, it algorithmically stops any more funding. Because of how Stable Pay operates, the equilibrium state of the Xank Reserve is expected to retain 15% of the total coin supply of Xank at all times. When extreme volatility hits, the first level of EVS is set at a 50% price drop in a single day. When that happens, the Xank Reserve will automatically pull the escrow funds preserved in the Xank Treasury. The second level of EVS is set at a 70% price drop in a single day. When that happens, the Xank Reserve will pull the escrow funds engaged in Xank Governors’ masternode collaterals automatically. The third level of EVS is set at a 90% price drop in a single day. When that happens, the Xank Reserve will pull the escrow funds engaged in Xank Citizens’ staking collaterals automatically. On top of these measures, 30% of the Xank Reserve Pool will at all times be atomically swapped with five cryptocurrencies with a low or negative correlation to Xank in prorated percentages reviewed every quarter as an extra safety net. When volatility subsides and normal times return, all escrow collaterals from Xank Citizens will be returned first, and all escrow collaterals from Xank Governors will be subsequently returned.

Hence we define the general term for Xank Reserve Pool as,

$$Rp=Xr+Te+Ge+Ce$$

where, 

*   $Rp = Xank \ Reserve \ Pool$ (30% of Total Coin Supply)
*   $Xr = Xank \ Reserve$ (15% of Total Coin Supply)
*   $Te = Xank \ Treasury \ Escrow$ (5% of Total Coin Supply)
*   $Ge = Xank \ Governors \ Escrow$ (5% of Total Coin Supply)
*   $Ce = Xank \ Citizens \ Escrow$ (5% of Total Coin Supply)


### Atomic Swap Basket

The Atomic Swap Basket will be composed of tokenized assets and cryptocurrencies that have a low or negative correlation to Xank. We currently have no historical data on Xank, so Bitcoin's correlation to various crypto assets is used as a proxy. The depth of market liquidity will also be evaluated for these tokenized assets. Our current proposed Atomic Swap Basket is composed of the following:

*   BTC Bitcoin 35%
*   ETH Ethereum 35%
*   AVAX Avalanche 10%
*   LINK Chainlink 10%
*   PAXG PAX Gold 10%

The composition and weighting of the Atomic Swap Basket will be voted on by Xank DAO quarterly. If Xank has a low correlation to BTC, we anticipate BTC to become a greater proportion within the basket. Tokenized commodities such as gold are currently not large enough to be included in the basket, but we hope to include commodities when liquidity is sufficient. 

Hence we define the general term for Xank Atomic Swap Basket as,

$$Sb = Rp * 0.3 = Xs * 0.09$$

where, 

*   $Sb = Xank \ Atomic \ Swap \ Basket$
*   $Rp = Xank \ Reserve \ Pool$
*   $Xs = Xank \ Total \ Coin \ Supply$ or $M_n$


### Idea Meritocracy Governance

Xank will introduce an idea meritocracy based on Ray Dalio’s implementation of it at the Bridgewater firm, which transformed the fledgling firm operating out of a bedroom into one of the largest hedge funds in the world, into its governance ecosystem. To avoid centralizing forces that are evident in democratic or pseudo-democratic blockchains, Xank will implement a meritocratic governance system. The Xank DAO will implement a Self-sovereign Identity system that will allow for the operation of a reputation-based mechanism that will operate at the Xank masternode level, which will have a bearing on the voting power that each masternode operator has on the network. This way, a masternode operator cannot simply buy into the network governance and voting mechanisms. They must develop reputation credentials that are recognized by other masternode operators as beneficial to the network in order to be able to have the appropriate influence over the network and earn their vote.

It has been found that blockchains coalesce toward centralization when they implement democratic or pseudo-democratic governance models. These centralizing forces can increase over time with the effect of solidifying the networks and often make them incapable of simple upgrades. In order for a network to remain dynamic and thrive, it must be able to respond to new market conditions and adapt to new technologies as they evolve. We look at the weaknesses present in earlier blockchain governance implementations and then describe the Xank Idea and Social Meritocracy Governance system at the Xank DAO level.

Satoshi Nakamoto decided to use the Proof-of-Work mechanism for Bitcoin’s network governance, where each node on the network can effectively vote on Bitcoin Improvement Proposals (BIPs). With Bitcoin, each node is able to upgrade its node software to the software that was proposed. Upon achieving a certain threshold of acceptance, that is when enough nodes upgrade to the new software, a consensus is achieved on the upgrade, and the network forks accordingly. In the early days of Bitcoin, each node operator was also a miner, which effectively gave each miner a vote. This governance model could be thought of as pseudo-democratic in that it mapped a democratic governance model. 

As mining hardware became increasingly competitive, the mining component of Bitcoin started to become centralized. Nodes decoupled and specialized from the original nodes that performed all network functions to mining nodes, validating nodes, pruning nodes, and archival nodes. Mining nodes retained the ability to ‘vote’ on network proposals. However, the miner’s voting process was heavily influenced by non-mining node operators with economic network gravity, such as exchange and Bitcoin service operators. Further, mining node operators often found their economic interests clashing with leading Bitcoin protocol developers, who seem more conservative in their approach to network development, which led to upgrading standoffs between competing interests. These standoffs have resulted in controversial network forks along with difficulties in achieving an easy path to technological upgrades. 

The Dash network resembles Bitcoin in many ways, as it was modeled after the Bitcoin network. However, Dash made distinct changes to the network governance system by introducing masternodes and allowing the masternodes to have one vote as recognition of the commitment of their resources to the network. The Dash masternode voting mechanism can be seen as a direct effort to add a democratic element to the governance model. This enabled Dash to become self-funding, as the masternodes were rewarded from the block rewards and could also allocate funds towards the development and growth of the network. This gave the Dash network the ability to operate autonomously and self-fund its development, which has contributed to the network’s success and prominence. 

This development has been a revolution in the ability for blockchains to self-fund. It has also introduced a new element of centralization in that a large economic player external to the network could influence the network by buying up a simple majority of masternodes. Due to the value of the masternode capital buy-in, it is not economically viable that an attacker would use this method under current market conditions, but this does remain a theoretical centralizing force and network weakness. Potential network weaknesses are usually reflected in the market value of the network in real-time, meaning that the Dash network is not realizing its full potential. 

The Dash network made tangible improvements over the Bitcoin network, and that is the main reason Xank has decided to implement Dash-style governance, thereby inheriting many of its favorable characteristics. Xank starts by using the Dash framework as a proven and well-functioning base and then builds new features and characteristics to avoid the potential centralization that Dash is exposed to. Xank is set to move away from the democratic governance mechanisms employed in earlier blockchains and move towards meritocratic governance as described and implemented at Bridgewater. 


### Xank Self-sovereign Identity and Xank Reputation Index

A Self-sovereign Identity system and a reputation system will be built into the Xank DAO and will operate at the masternode level, which has voting power over the network’s funding mechanisms. Xank masternodes require 1,000 XDR worth of XANK coins at the creation point and dedicate this capital, along with appropriate network resources, to gain access to the Xank voting mechanism. This can be thought of as gaining a ‘seat at the Xank network’s governance table’. Unlike the Dash network, however, this seat does not give the masternode an automatic vote. Xank votes will be awarded to Xank masternodes based on their merit, and this will be decided by a weighted reputation-based system, known as the Xank Reputation Index, that will resemble the Bridgewater Believability Index. With Bridgewater, company employees rate each other on their merits, which results in highly rated employees establishing more voting clout in terms of company direction, initiatives, and governance.  

The Xank Reputation Index will work in conjunction with the Xank Self-sovereign Identity system ensuring that masternode operators cannot gain additional votes by simply purchasing more XANK coins as each ‘seat at the table’ will need to establish a reputation that is favorable to the network in order to establish voting power. This does not diminish a masternode operator’s ability to purchase additional masternodes that support the Xank network; it only diminishes their ability to buy voting power. With Xank, a Governor needs to earn their vote by establishing a Reputation Score, which will give them weighted voting power but never more than one vote. The Reputation Score will be aggregated from all masternodes and will be logged with the masternode operators’ Self-sovereign Identity and be made visible to all. The score will award the masternode operator with a proportion of a full vote. Masternode operators that do not establish a Reputation Score can continue supporting the network with their resources and allocated capital stake but will not be able to vote on network funding proposals.

We consider the attack scenario where a masternode operator attempts to game the Xank Reputation System by purchasing additional masternodes and covertly appointing fake or proxy operators that are under control in order to create a sufficient voting block to overpower the network. Even if the masternodes are geographically dispersed, the masternode operator would need to establish Self-sovereign Identities for each of these masternodes, and each fake operator would need to establish their reputation among the masternode social ecosystem - that is to be rated by other nodes based on their public standing, one of the key attributes of the merit-based system. For the attacker to have any chance of success, they would need to recruit highly principled people with high standing within the cryptocurrency and wider scientific and business community. The people that rise to the top of these meritocratic hierarchies are in whole the most protective of their reputations and are often the least corruptible. To bribe and corrupt enough people with high social standing in order to establish a voting block of a size that can dominate a reputation-based network is a task that is doomed to failure, as it would need high levels of simultaneous coordination, untainted loyalty, and sustained effort over time. Such an attack will be more costly to coordinate than the profits a masternode operator can make by contributing resources to the network to profit from its existing incentives and rewards.

The algorithm that allocates weighting for masternode voting powers will take many factors into consideration that will fall under two key pillars of additional proofs as described herein; Proof-of-Service (PoSv) and Proof-of-Merit (PoM):

*   **Proof-of-Service (PoSv)** - Base voting seat
    *   A masternode operator is required to purchase 1,000 XDR worth of XANK coins and put them up as collateral to obtain a base voting seat in the Xank Congress. Although the seat has no voting power in and of itself, it is the first necessary step in the process of establishing voting power, as it is proof that the operator has extended resources that support and service the network, hence the ‘Proof-of-Service’ moniker. A Xank masternode operator reserves the right to not establish voting power, and this in no way limits the masternode operator from acquiring more masternodes and receiving the block reward incentives proportional to their investment. Should an operator operate one or many masternodes, they still only establish one voting seat.
*   **Proof-of-Merit (PoM)** - Establishing voting power
    *   A seat, as such, has no voting power until it has secured a Self-sovereign Identity with a Reputation Score. A Reputation Score is attained by providing credentials to the network that are assessed by the network of masternodes that assign weights to each masternode’s Reputation Index, which will be based on criteria that indicate the level of merit the masternode operator can provide to the network. Merit scoring will take into consideration expertise, talents, and intellect that lends itself to being of benefit to the network. The Self-sovereign Identity system, along with the 0-10 point Reputation Index, ensure that a masternode operator is weighted according to their Proof-of-Merit to the Xank network, making sure that network funding proposals and approvals are governed in a meritocratic way. 


### Xank Budget Allocation

Masternodes operators that have established their Self-sovereign Identity and have been awarded a weighted vote according to the Reputation Index criteria will be able to vote on network proposals. The total available budget of the network can be calculated by taking 15% of the block rewards over the period of time between two superblocks. Superblocks occur every 87,600 blocks or approximately 30.41 days. A voting cutoff will occur prior to the superblock in order for the final votes to be tallied, and the results will be made available to the network so that all have time to prepare for the superblock event. A voting proposal must be formulated so that the resultant vote data can be presented as a boolean data type format 

where,

$$Yes/True = 1$$

and 

$$No/False = 0$$

Governors must also establish the desired funding amount, either as a total amount or a percentage of funds awarded between superblocks. 

A successful Yes vote will be indicated by the total number of weighted Yes votes being 50% or greater than the Total Voting Power allocated to the masternode network at that time. If multiple proposals are awarded funding rights, they will be ranked according to their voting margins and will receive a share of funding in proportion to their rank and voting margin up until the level of the entire budget being allocated or where all funding requests have been exhausted within budget. Any funds that remain after intra-superblock funding allocations will be deposited in the Xank Treasury and be made available for future funding proposals.

As mentioned above, a purpose-built for-profit company will be created to oversee the development, launch, and initial deployment of the network. Once the network has been launched and is operational, the company will then compete in the free market for network funding proposals. Funding proposals will often require the setting up of organizational structures, such as companies or committees, that are responsible for the completion of tasks or projects. A successful vote will result in the tasked organization being funded directly. This can be in the form of an initial budget allocation in full, payment at the conclusion of the task, or milestone payments. For payment tasks or projects where funds need to be withheld until the conclusion of the project or task, their funds can be held in escrow in a treasury mechanism and released as agreed. Some proposals will require varying levels of human oversight, management, and reporting for their implementation and completion. Managers, team managers, and committees that are responsible for the proposals will also be responsible for the reporting of budget expenditures and milestone achievements to indicate how the funds were allocated and managed during the execution of the said project. 

The use of the Xank Self-sovereign Identity system can be used where said managers or committees can build a Reputation Score based on their success of completed projects and in time gain a reputation for managing funds in a way that is to the ultimate benefit of the network. Successful implementers will be preferred by the network and favored for future proposals, and less successful implementers will be overlooked for future funding proposals in an organic and meritocratic way.

# Applications and Use Cases

In this section, we explore the primary applications envisioned for the Xank network in relation to the wider cryptocurrency and digital asset ecosystem and examine how Xank will be used by the five main user groups: exchanges, individuals, merchants, businesses, and activists.

We will focus on the main advantages as they apply to each of these user groups:

*   Xank properties that will be bestowed on other asset classes
*   The reduction of volatility and the establishment of Xank as a reliable unit of account
*   Migration of global assets to the Xank blockchain


## Exchanges

Digital currency and asset exchange operators that accept fiat currency deposits and allow for fiat currency withdrawals experience varying degrees of friction when interfacing with the legacy financial infrastructure. This is often challenging, risky, and costly. Here are some of the common issues digital currency and asset exchanges face:

*   Creating fiat to crypto on-ramps and off-ramps (also known as payment rails) that require interfacing with traditional legacy financial institutions, primarily banks.
    *   Establishing agreements with the rigid financial legacy system while internally dealing with irreversible transactions, low transaction fees, fraud protection and more.
*   Interfacing with banking platforms that are not up to speed with appropriate APIs for transaction and account integration
*   Liaising with these banks and other financial institutions to organize compliance, security, and build trust
*   Prohibitive costs for small value transfers
*   3-7 days for international wire transfers to clear
*   Unfavorable and often arbitrary currency conversion charges and procedures
*   Needing to interface with traditional financial sector intermediaries when clearing and settling funds with other cryptocurrency exchanges

Digital asset and cryptocurrency exchanges can use Xank to overcome many of these friction points and gain access to new benefits, such as:

*   Accept cryptocurrency and fiat-denominated crypto amounts for deposits, withdrawals, and storage purposes in order to bypass legacy banks and payment providers.
*   Eliminate the risks that are inherently present in Proof-of-Work chains that employ mining for their security mechanism, which expose exchanges that list coins with weak hashpower and mining support that are open to miner attacks and double spending hacks
*   Allow users to move a fiat-denominated cryptocurrency in and out of the exchange with little to no friction
*   Outsource their fiat custodial risk and take advantage of the Xank Reserve stabilizing mechanism, thereby freeing them up to only deal and manage cryptocurrencies
*   Offer more fiat-to-crypto trading pairs by taking advantage of Xank’s pegging mechanism and stability
*   Secure customer assets purely through cryptocurrency industry best practices and encryption technologies, such as multisignature security, cold and hot wallet usage, Hierarchical Deterministic (HD) wallets (BIP32)<sup id="a8">[8](#f8)</sup> and more.

*   Set up their systems to purely deal with cryptocurrencies thereby reducing complexity and improving audit readiness.
*   Utilize all additional functionality that Xank offers over earlier blockchains, such as Xank stable transactions functionality, reduced block times for quicker withdrawal and deposit confirmations, and more transactions per second, allowing for a new class of trading products

Exchange users undergo risks when holding fiat on exchanges and may face barriers to exiting exchanges with fiat amounts that exceed bank account limits that are often arbitrarily set. Exchanges can support the Xank Stable Pay functionality and extend it to their users, who can store withdrawals privately in a fiat-denominated cryptocurrency and retain value while remaining under bank account limits. Exchanges can take advantage of the reduction in counter-party risk to users and thereby attract more users.


## Individuals

From traders looking to find value in digital assets; to cryptocurrency holders that are looking at a long-term value proposition for storing their wealth with potential upside; to the technology savvy who are looking to avoid credit card and remittance fees when transacting and shopping; to the philosophically inclined that see digital assets as revolutionary with the potential to save the world; to those looking to accept payments internationally more effectively; to those in third world nations looking for access to financial services for the first time; to developers that create new technologies; and to those who have found other applications for Bitcoin and cryptocurrencies that are not mentioned here - we believe that Xank offers similar utility with additional features, for example:

*   Transact with a fiat denominated digital asset, pseudo-anonymously, without any middlemen/intermediaries
*   Fiat value digital asset storage, including cold storage and multisig private keys outside of the financial system
*   Avoid the risk of storing fiat on exchanges — move crypto­fiat in and out of exchanges faster
*   Avoid having to open a fiat bank account to store wealth in a fiat denominated value
*   Anything you can do with Bitcoin as an individual, one can also do with Xank


## Merchants

Merchants need payments systems that work seamlessly with their operations so that they can focus on their business. In an increasingly connected world where payments need to be made inexpensively across borders, there is a lack of inexpensive, near-instant and ubiquitous payments systems that don’t rely on the legacy financial system, which leaves merchants as a captive audience. Earlier cryptocurrencies also came with the promise of cheap and fast transactions, but their price volatility is not compatible with merchant services. Additionally, cryptocurrency transaction fees have often rivaled and sometimes exceeded those of the legacy financial system. Waiting for block confirmations before a customer leaves with the goods has also not helped the cryptocurrency use case for merchants. Merchants large and small deserve better. Here are some of the ways Xank can help:

*   Goods and services can be valued and invoiced in fiat values by requesting payments that use the Xank Stable Pay or Local Pay feature (no moving conversion rates/purchase windows)
*   Prevent the need to regularly convert cryptocurrencies to fiat as well as remove all associated fees and procedures
*   Prevent chargebacks, reduce fees, and gain greater transactional privacy
*   Provide novel services that derive from cryptocurrency features, such as privacy, cold-storage, escrow accounts, and multisignature private-keys
*   Token-specific, data-rich features such as customer loyalty points, gift cards, promotions, affiliate programs, and more
*   Additional Xank features that are useful to merchants that are not offered by Bitcoin, such as stable transactions functionality, fast confirmations, additional privacy features, and near-instant transactions


## Business and Startup Funding

In the data and information age, new businesses and startups need to be more responsive to environmental concerns and differentiate themselves from business practices that were more common during the industrial age. Running a business that is eco-friendly and that complies with new environmental and employment regulations is becoming more costly while there is an increasing lack of government support, consumer awareness, and other funding initiatives. Sometimes these higher costs prohibit new businesses from entering the market altogether. The Xank protocol seeks to help businesses and startups achieve their funding goals if their behaviour is congruent and in principle with the Xank Constitution. Here are a few potential use case scenarios and ways Xank can help:

*   Fund composting toilets and alternative septic systems startups that can drastically reduce waste, chemicals, and general pollution that reaches the oceans
*   Fund high-rise aquaponics farm startups that can drastically reduce soil pollution and degradation
*   Fund plant-based diet campaigns and support research grants that can drastically reduce global warming
*   Fund clinical experiments of natural medicine that can drastically improve human health
*   Fund startups and individuals in the tiny house movement to reduce carbon footprint at the household level
*   Fund Tesla-style wall battery installations to homes and offices around the world to improve air quality
*   Other proposals that are aligned with the Xank Constitution can seek funding as a viable alternative to Initial Coin Offering (ICO) fundraising, something that is facing increased regulatory capture and compliance costs as a funding model


## Activism

Community-driven events and organizations that seek to foster improved human relationships often lack appropriate funding to create positive community awareness. Activist organizations are typically poorly funded, lack government support, and struggle to gain recognition for causes that can potentially improve human behavior and promote peaceful interactions. The Xank protocol seeks to help activists, communities, and non-governmental organizations (NGOs) achieve their funding goals when their intent is congruent and in alignment with the Xank Constitution. Here are a few potential use case scenarios and ways Xank can help:

*   Foster cultural exchanges and understanding through sponsoring K-pop, anime, food, and other cultural aspects
*   Advocate for LGBTQ equality by lobbying for LGBTQ rights at federal, state, and local government levels
*   Advocate for equality by lobbying for women’s rights at federal, state, and local government levels
*   Advocate for racial equality by lobbying for different ethnicity rights at federal, state, and local government levels
*   Support non-violent anti-hate rallies to counter negativism and encourage positive engagement by the larger population
*   Fund and foster awareness in installing accessibility equipment, custom roads, and pathways for the disabled in public and private spaces
*   Other proposals that are aligned with the Xank Constitution can seek funding as a viable alternative to NGO fundraising


# Xank in a Post-fiat World

By soft-pegging to the IMF SDR, Xank will be able to leverage all of the economic stabilization policies and efforts that are pursued by the world’s most dominant central banks. Xank’s stable transactions functionality offers the world a currency with stable buying power. This feature alone is aligned with the concept of an ideal money that is set to attract individuals, businesses, communities, and organizations to use it. As the Xank ecosystem grows through increased adoption and use, so too will it’s self-funding Reserve and Treasury grow, offering transactional stability and funding opportunities that are rarely seen outside institutional and governmental organizations that rely on taxing populations. 

It should be emphasized that the SDR facility is only offered to participating central banks that are members of the IMF. This means that until now, only these member banks could benefit from the stabilizing currency forces offered by the SDR facility. Xank is set to distribute this stabilizing power right down to the individual level in an effort to truly democratize this currency stabilizing functionality. This sets the scene for Xank’s increasing adoption as a widely used medium of exchange with the potential to even displace fiat currencies in trade volume. Were this to happen, Xank would present the world with both the technology and the chance to develop an independent, transparent, and possibly a more stable financial system with a more reliable infrastructure than the current central bank-based financial system.

What are the possible future implications? What follows is an exploration of several scenarios.


## Soft-pegging to a Consumer Price Index

Should Xank begin to control a significant share of the world's transaction volume, we could assume that some goods will begin to be offered at costs denominated in Xank. In such a world, the Xank protocol could be updated to a peg that is independent of any currency that is denominated in a nation-based currency or even a basket of currencies, such as the SDR. It is probable that Xank would move to a peg that reflects the value of a Xank denominated basket of products. Functionally, this could be similar to the way the central banks currently implement monetary policies based on a Consumer Price Index (CPI) to maintain a purchasing power equilibrium for their respective national currencies.

A Xank protocol pegged to the Xank denominated CPI-like basket would be an implementation of a monetary policy that is independent of any government with the potential to achieve a global trade scale. 

At the highest level of consideration, we believe that governments provide two critical solutions for their citizens in preserving control over the money supply: verifiability and price stability. Regarding verifiability, governments can issue cash notes and coins and create the legal protections against counterfeiting. Regarding price stability, central banks are able to intervene in an economy through the use of monetary and fiscal policies with the intent to provide stability to the financial system and encourage financial demand. Financial stability in an economy can encourage growth, reduce unemployment, and attract investment. Most central banks have a mandate to provide stable conditions to the local economies.

Bitcoin provided a solution to the double spend problem that doesn’t need enforcement by a central authority, thereby removing the need for centralized verifiability. Xank is proposed as a solution to the current reliance on centralized economic interventions for achieving relative price equilibrium. As well-intentioned and well-insulated central banks might be, authorities often exert pressure on them to inflate the money supply when their economies end up in too much debt. This increases inflationary pressure and results in the value of government-issued currencies eroding over time, sometimes even catastrophically as countries end up in default on their debts. 

We believe that when cryptocurrencies mature to the point where they can fulfill all the necessary functions of money, they will be preferred by citizens and taxpayers to replace the legacy financial and governance system. Digital money alternatives can offer society independent, transparent, cryptocurrency-based monetary policies that offer degrees of accountability to the likes never been seen in history.


## Giving Power Back to the People

When Oda Nobunaga found himself in fragmented feudal Japan in the mid-sixteenth century, he sought to unify Japan into a modern state through military force taking territories controlled by many warlords at that period. 500 years later, we find ourselves similarly fragmented - into some 200 nation states controlled by many local governments (akin to modern-day warlords) even as the globe has been connected on the Internet for some time now. The increased interconnectedness of the world brought about by advances in communications, transportation, and trade have made the use of national currencies and passports cumbersome, which have increasingly become more of a hindrance to trade and human global relations. 

Multinational corporations that span the globe, communities, NGOs, and increasingly, individuals, face bureaucratic friction when navigating multiple jurisdictions and their regulations, to perform otherwise simple tasks, such as electronically engaging in commerce across borders. As these technologies become more ubiquitous in our daily lives, the need to rely on central banks and nation states will dissolve.

In his era, Nobunaga had to resolve territorial disputes in order to unite the world. Thanks to Nakamoto’s blockchain technology, we no longer need to resort to this kind of hard power to unite the world. The widespread use and adoption of blockchain technology can be the soft power humanity needs to establish a global currency and governance. This change need not happen through violent revolution or the destruction of the nation-state world. Instead, as technology thrives and evolves, it will leave the nation-state model behind, and history will see its era of rule as a remnant of its time. The transformation will be a grassroots change as humanity moves toward using more efficient technological alternatives to the current paradigm.

Having lived in both South Korea and the United States for more than ten years in each country, both two of the most successful economies in the world, I have developed an understanding of how these governments operate. Both governments proclaim to serve their people, as servants. Instead, I observed the citizens of both countries becoming more aware that they were watching big-brother states being built around them. The authorities increasingly grant themselves more power, which results in systemic corruption. Instead of serving the best interests and the will of the people, those in power devote most of their time to special interest groups and corporate lobbyists, not the general population.

In the last century, two dominant political systems emerged to govern over most populations: autocracies, as seen in North Korea, and liberal democracies as seen in South Korea and the United States. Both political systems are equally prone to failure at serving their populations. It can be argued that liberal democratic systems have performed better than their autocratic counterparts; yet these results are often only apparent on the surface level. Even the liberal democracies that oversee successful market-based economies have managed to create a huge divide between the haves and the have-nots.

> “The top 1/10 of 1% of the population has a net worth that is equal to the bottom 90% combined. The wealth gap is the largest wealth gap that there has been since the 1935 to 1940 period. And so while we have good conditions here, for the bottom 60% of the population, we have bad conditions. So, the averages don’t convey what the picture is because of this disparity. And so, what was tapped into and what we see is there’s a large percentage of the population who is hurting, and that there is a conflict between the “haves” and the “have-nots” and liberal ideas and conservative ideas and all of that. And we have a greater polarity.”
>
> – Ray Dalio, Founder of Bridgewater Associates


With the exception of Singapore, autocratic systems all but failed. Consider North Korea and South Korea, for example, where both populations share the same ethnicity and where the only clear division is their political systems. The South is economically flourishing to the degree of 100 to 1 in terms of GDP per person while their northern counterparts are daily preoccupied with their survival. One thing both populations do have in common is that they are both increasingly being surveilled by the state as technology has made it more feasible for mass surveillance.

To maintain hegemony, one system collect taxes, and the other distributes wages. Both governance systems have failed as the Earth is being ravaged, waterways are increasingly becoming polluted, corporations are allowed to run rampant and destroy air-quality, industrial farming is depleting the soils, and many regions are becoming uninhabitable for humans, native species, and plants. 

Both systems fail us economically as they resort to inflating the money supply to manage ever-increasing costs of servicing debt, which in turn deflates our assets and national wealth. 

Both systems fail us as they spend taxes on military buildup and often senseless wars instead of education, health, research, and societal well-being. These systems become corrupt, overbearing, and ultimately can turn oppressive, often in spite of their original intent.


## A Preamble to the Xank Constitution

Here we document the principles that will be drafted to be embedded in the full version of the Xank Constitution, which will be ratified and passed by the Xank DAO as a priority.

The draft is primarily modeled from the work laid out in Ray Dalio’s book, _Principles_. Ray Dalio is often fondly thought of as a modern-day Adam Smith and Karl Marx. A businessman foremost, Ray is also a philosopher. 

Ray originally set out to create a meritocratic system that would be of benefit to himself and his company, but what emerged is a system that can have much wider institutional level implications throughout society. 

The ultimate success of the Xank network can be measured by the degree to which it enriches the people of the world with a true meritocracy that can scale to a global level - this is our intent. It is, therefore, no coincidence that Xank will share characteristics with Ray Dalio’s meritocratic model. Xank sets out to address the problems that are most vital to human survival and prosperity that are not being addressed by the current crop of governments and corporations. The Xank Constitution will act as a magnet to attract people to the Xank economy based on their merit. These people will earn the ability to guide how the Xank Treasury funds are to be spent with a view of prolonging human sustainability on this Earth and beyond.

**Pollution Clause** - efforts that aim to provide for:

1. Clean Air
2. Clean Soil
3. Clean Water

**Discrimination Clause** - efforts that aim to eliminate discrimination of:

1. Ethnicity or Disability
2. Religion or Ideology
3. Sex or Sexual Orientation

**Oppression Clause** - efforts that aim to counter and eliminate the destructive forces of:

1. War and Military Buildup
2. Inflation and Quantitative Easing
3. Systemic Corruption

**Abuse Clause** - efforts that aim to counter and curtail the abuse of:

1. Human 
2. Animal 
3. Slaughter

**Consumption Clause** - efforts that aim to counter and curtail the use of:

1. Overconsumption
2. Big Houses
3. Food Waste

**Sustainable Development Goals (SDGs)** - efforts that aim to support the UN initiative<sup id="a9">[9](#f9)</sup>:

1. No Poverty
2. Zero Hunger
3. Good Health and Well-being
4. Quality Education
5. Gender Equality
6. Clean Water and Sanitation
7. Affordable and Clean Energy
8. Decent Work and Economic Growth
9. Industry, Innovation, and Infrastructure
10. Reducing Inequality
11. Sustainable Cities and Communities
12. Responsible Consumption and Production
13. Climate Action
14. Life Below Water
15. Life On Land
16. Peace, Justice, and Strong Institutions
17. Partnerships for the Goals

We are the same people even though we came to speak different languages and have different skin colors. We are all brothers and sisters sharing the same planet. We can be more friendly toward each other and respect each other. A more peaceful, loving, and compassionate world cannot be achieved as long as people hate others based on their differences. As all people are unique, we are all different from each other, and this should be celebrated. A better world cannot be built if people allow forces that divide us into opposing groups that are often based on ethnicity, social class, economic clout, religious and ideological beliefs, race, gender, sexual orientation, and all other perceived human differences to exist. Xank will add clauses in its constitution to allow for the funding of projects that work toward the elimination of pollution, discrimination, oppression, and curtail consumption.

The act of moving assets away from government-backed fiat currencies and establishing assets in decentralized self-funding and self-governed cryptocurrencies can alleviate much of the government-sponsored oppression and corruption that is rampant in the world, should the required scale be achieved. Ultimately, the governments of the world are collectively sponsored by citizens in the form of taxes collected in fiat. When assets are moved off the balance sheets of centralizing forces, such as governments, central banks, and corporations, and move into decentralized human-powered networks, the governments of the world will lose their self-imposed influence and lordship over the people’s wealth and the allocation thereof. As governments are no longer able to sustain monopolies over the people’s wealth through taxation and reallocation, they will lose their ability to sustain large centralized infrastructure, such as is required to maintain large militaries and wage senseless and unnecessary wars.  Centralized government will give way to more decentralized governance structures that empower locally based communities that exercise governance in transparent ways to provide for the required levels of community protection, health, education, well-being, and prosperity. Nation-state-backed fiat currencies will lose their relevance as nation-states themselves become less relevant. Currency wars and inflationary monetary policies will no longer have such degrading influence over the people's wealth. Locally based community governance structures can be held more accountable, which will degrade the scale of corruption that is rampant in centralized, opaque government structures and institutions.

The Xank Constitution<sup id="a10">[10](#f10)</sup>: will act as a mechanism to guide network proposals and initiatives that are beyond the scope of network maintenance, development, upgrades, and promotion. The Xank Reputation Index criteria will allow masternode operators to gain voting influence over the network each time they back initiatives that are beneficial to the network or in line with the Xank Constitution - and this will be the basis for building a meritocratic network that benefits all users and humanity. As more proposals that benefit humanity get funded, a positive feedback loop that will attract more involvement by the wider community will be created. This will further fund and grow the Xank network and fulfill it’s imbued intention to be of service to humanity by building a better society.


# Conclusion

The birth of Bitcoin gave rise to the idea of cryptocurrencies competing with fiat currencies for transactional usage and removing the world’s reliance on centralized institutions that make up the legacy financial system. However, Bitcoin’s inherent price volatility does not lend itself to such use cases. 

In this paper, we introduced Xank, a robust, decentralized, autonomous organization, a reserve-backed stable transaction cryptocurrency. Xank’s stable transactions functionality will act to stabilize the purchasing power and offer protection against price volatility. Xank, therefore, stands as a network that can be used for price stable payments and wealth storage. As Xank’s unique stable transactions characteristics and use cases gain traction and adoption, we believe this contribution will cause cryptocurrencies to experience a virtuous cycle of adoption and help them transition into a mainstream medium of exchange.


# Appendix

## Pros and Cons of Existing Stablecoins

It is important to consider what problems certain cryptocurrencies have attempted to solve and how their efforts have resulted in gaining a better understanding of the Xank proposition. Below are commentary, analysis, observations and extracts based on a post by Haseeb Qureshi on Hackernoon, where he explains the key concepts behind the current batch of stablecoins (full text<sup id="a11">[11](#f11)</sup>).


### Tether

Tether’s attempt at a stablecoin was to create an IOU-based debt instrument that is redeemable for \$1.00 USD. By depositing dollars into a bank account, you can issue Tether on a 1:1 basis. Users that wish to redeem their value are paid back the Tether value in fiat and the Tether coins are destroyed so as to maintain the 1:1 ratio in the available supply and the amount in the bank account.

This simple setup requires trust in a central Tether issuer who constitutes a single point of failure. Trust can be minimized through periodic audits or full level transparency which is lacking.

The peg should remain stable as long as the amounts issued match with the funds that are allocated in the bank account.

Tether can be useful for price stable payments, but the U.S. dollar is a currency that is continually inflated and experiences value degradation over time, which does not make it ideal for wealth preservation and a store of value. Furthermore, it cannot attract a rate of interest on deposits as can its fiat counterpart in a savings account, which further degrades its value proposition.

Fiat-backed schemes are also highly regulated and constrained by legacy payment rails that involve bank wires and cheques when cashing out back into fiat.

**Pros:**

*   100% price-stable
*   Simplest (a big virtue)
*   Less vulnerable to hacks, since no collateral is held on the blockchain

**Cons:**

*   Centralized — need a trusted custodian to store the fiat (otherwise vulnerable to brick and mortar theft)
*   Expensive and slow liquidation into fiat
*   Highly regulated
*   Need regular audits to ensure transparency

Tether recently avoided an audit which allows room for doubt on whether they hold the funds they purport to hold. Other stablecoins like Saga are trying to do the same thing but with more transparency. Digix Gold is a similar scheme, except that the collateral is gold instead of fiat. Nevertheless, such stablecoins share the same fundamental properties.


### Maker (Dai)

The basic concept here is to peg to a fiat currency by reserving collateral in a cryptocurrency. To combat the price volatility of the underlying cryptocurrency, one must establish an overcollateralized pool of funds that can absorb price shocks. The incentive for someone to ‘lock-up’ their funds as collateral is that their position can be leveraged against the base cryptocurrency in fiat value terms. 

> ...if a depositor locks up \$200 of Ether, they can create \$100 of stablecoins. If they use the 100 stablecoins to buy another \$100 of Ether, they now have a leveraged position of \$300 Ether, backed by \$200 in collateral. If Ether goes up 2x, they now have \$600, instead of the \$400 they’d otherwise make.

This mechanism can be set up to operate on a transparent blockchain and thereby eliminate the need to trust the amounts held in collateral. However, it has one required feature, and that is a constant price feed that records price fluctuations on the blockchain to keep the peg ‘informed’. This means that although trust is eliminated in the collateralization, the trust has now shifted onto the trusted feed. 

Crypto-collateralized coins are also exposed to sharp drops in the valuation of the underlying cryptocurrency asset. If the underlying asset drops in value to below the collateralized amounts, the coins will instantly be liquidated into the underlying asset, which then fully exposes the held value to the price volatility of the underlying cryptocurrency. This failing makes the crypto-collateralized stablecoin unlikely to be used by exchanges, which vastly reduces its adoption surface area. 

**Pros:**

*   More decentralized
*   Can liquidate quickly and cheaply into underlying crypto collateral (a blockchain transaction)
*   Very transparent — easy for everyone to inspect the collateralization ratio of the stablecoin
*   Can be used to create leverage

**Cons:**

*   Can be auto-liquidated during a price crash into underlying collateral
*   Less price-stable than fiat
*   Tied to the health of a particular cryptocurrency (or basket of cryptocurrencies)
*   Inefficient use of capital
*   Most complexity

Thus, MakerDAO’s Dai crypto-collateralized stablecoin is collateralized by Ether. BitUSD is another example, the first crypto-collateralized stablecoin to be issued and collateralized with BitShares.


### Carbon

The idea that a coin does not need to be issued by an underlying asset gained traction in thought circles since it was first propounded by F.A. Hayek in the 1970s. After all, the United States was able to decouple the dollar from the gold standard and maintain a relatively stable valuation using monetary inflationary and deflationary policies to regulate the supply of the currency in circulation. Seigniorage shares, a scheme invented by Robert Sams in 2014, was based on the simple idea that a central bank can be replaced by a smart contract that regulates the amount of the currency that is in circulation. The smart contract could be mandated to peg the currency to a fiat value, say \$1.00 USD. 

Expanding the money supply is a simple matter of course for a central issuer. You simply issue more coins as demand for the coin increases to keep the price stable. Contracting the money supply, however, is not as straightforward, as it would involve you having to buy back the coins at market value, which would be lower than the peg and thereby restricting the price until the value returns to the peg. Offering newly issued coins to the market to lower the price returns a profit; this is known as seigniorage.

Contracting the supply would mean that the smart contract would need to have a large reserve of funds that can buy up excess coins in price downturns, which is not very feasible or practical. The seigniorage shares proposed solution is to issue shares that would cover the difference in times of price downturn. Shareholders would then gain access to seigniorage profits when the market turns the other way, and the coin becomes profitable to the smart contract. 

Other non-collateralized stablecoins use variations of this method. There are many detractors to this methodology, and critics are quick to highlight its potential flaws, the most prominent one being that the system assumes that network growth will be continual in order for it to fulfill its obligations toward the shareholders. Others feel it is akin to a pyramid scheme where new entrants are continuously needed to prop the system up, and others yet point to the system virtually collateralizing from its future growth, thereby inherently cannibalizing its future growth potential and limiting the growth of the network. The coin is also open facing to a death spiral if it comes under continual pressure to sell, where traders sell their shares even below the peg value whereby the currency can experience a catastrophic collapse. 

Non-collateralized stablecoins are inherently susceptible to failure should they come under sustained selling pressure. However, as seen with many fiat currencies, they are issued with the intention of achieving a Schelling point, that is, if enough people believe that the system will survive, the belief itself will ensure the system’s survival as more entrants enter the network. This makes it one of the most exciting stablecoin propositions because if such a network can achieve a Schelling point, then it can potentially become resistant to shocks that other currencies experience, as it will act independently from them. Even if the U.S. dollar and Ethereum collapse, the non-collateralized stablecoin could act as a more stable store of value. And unlike central banks that can be overtaken by perverse incentives under the influence of nation-state governments, the stablecoin’s smart contract would carry on fulfilling its mathematically coded mandate to maintain price stability. For this reason, non-collateralized stablecoins have the potential to revolutionize money but exist on a knife’s edge where they can also experience catastrophic failure. 

**Pros:**

*   No collateral required
*   Most decentralized and independent (not tied to any other cryptocurrency or to fiat)

**Cons:**

*   Requires continual growth
*   Vulnerable to general crypto market decline or crash and cannot be liquidated in a crash
*   Difficult to analyze safety bounds or health
*   High levels of complexity

Carbon is a seigniorage shares style stablecoin that emerged in early 2018 with plans for protocol-governed expansion and contraction of the money supply via the issuance of additional tokens as the price moves above the peg and the withdrawal of tokens as the price moves below the peg. 


## **Xank Network Specifications and Comparisons**

| Masternode Cryptocurrency      |                             Dash                             |                             Pivx                             |                             Xank                             |
| ------------------------------ | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| Consensus algorithm            |        Proof-of-Work (PoW)<br>Proof-of-Service (PoSv)        |       Proof-of-Stake (PoS)<br>Proof-of-Service (PoSv)        |  Avalanche<br>Proof-of-Stake (PoS)<br>Proof-of-Merit (PoM)   |
| Hashing algorithm              |                             X11                              |                            Quark                             |                            Quark                             |
| Hardware mineable              |                             Yes                              |                No* (but multipool supported)                 |                No* (but multipool supported)                 |
| Block time                     |                         150 seconds                          |            60 Seconds (Re-targeting every block)             |             60 Seconds (Time based Super-block)              |
| Block size                     |                             2MB                              |                             2MB                              |             A batch size (Block size) of 40 TXs              |
| Datastore                      |                          Blockchain                          |                          Blockchain                          |                 DAG (Directed acyclic graph)                 |
| Premine                        | No premine. But 2M Dash was mined within first 36 hours of launch. (aka. instamine) | 60K on genesis block for setup of 6 initial masternodes. Premine was burnt from coin supply at block 279917. | 1B on genesis block for setup of 6 initial masternodes, early backers, ICO investors, founders, and founding company. |
| Max. coin supply               |                Approx. 17.6M after 100 years.                | No max. Increases by approx. 2.6M PIV per year. Approx 312M after 100 years. | No max. Increases by XANK coin Supply Algorithm. Approx 6.26B after 100 years. |
| Denominations                  |                           1e8 Duff                           |                             1e8                              |                         1e16 Ryu(𝔯)                          |
| Masternodes                    |                             Yes                              |                             Yes                              |                             Yes                              |
| Instant Pay                    |                             Yes                              |                        Yes (SwiftTX)                         |                        Yes (SwiftTX)                         |
| Private Pay                    |                        Yes (Coinjoin)                        |                        Yes (Zerocoin)                        |                Yes (Zerocoin at Wallet level)                |
| Stable Pay                     |                              No                              |                              No                              |                             Yes                              |
| IPv6 support                   |                              No                              |                Yes (both wallet & masternode)                |                Yes (both wallet & masternode)                |
| Decentralized governance       |                   Yes (masternode voting)                    |                   Yes (masternode voting)                    |                   Yes (masternode voting)                    |
| Budget funding                 |                  Yes. 10% of block reward.                   |                  Yes. 10% of block reward.                   |                  Yes. 15% of block reward.                   |
| In-wallet BIP38 encryption     |                              No                              |                      Yes (private key)                       |                      Yes (private key)                       |
| Permanent self funded treasury |                              No                              |                             Yes                              |                             Yes                              |


## **Xank Units of Measure**

Xank has a metric system of denominations used as units of Xank. Each denomination has its own unique name. The smallest denomination aka base unit of Xank is called a Ryu. Below is a list of the named denominations and their value in Ryu. Following a common pattern, Xank also designates a unit (of 1e16 or ten quadrillions Ryu) of the currency. 
| Unit | Ryu                    | Symbol | Xank               | Symbol | Ryu Value |
| ---- | ---------------------- | ------ | ------------------ | ------ | --------- |
| Ryu  | 1                      | 𝔯      | 0.0000000000000001 | 𝔛      | 1 𝔯       |
|      | 10                     | 𝔯      | 0.000000000000001  | 𝔛      | 1e1 𝔯     |
|      | 100                    | 𝔯      | 0.00000000000001   | 𝔛      | 1e2 𝔯     |
| Kryu | 1,000                  | 𝔯      | 0.0000000000001    | 𝔛      | 1e3 𝔯     |
|      | 10,000                 | 𝔯      | 0.000000000001     | 𝔛      | 1e4 𝔯     |
|      | 100,000                | 𝔯      | 0.00000000001      | 𝔛      | 1e5 𝔯     |
| Mryu | 1,000,000              | 𝔯      | 0.0000000001       | 𝔛      | 1e6 𝔯     |
|      | 10,000,000             | 𝔯      | 0.000000001        | 𝔛      | 1e7 𝔯     |
|      | 100,000,000            | 𝔯      | 0.00000001         | 𝔛      | 1e8 𝔯     |
| Bryu | 1,000,000,000          | 𝔯      | 0.0000001          | 𝔛      | 1e9 𝔯     |
|      | 10,000,000,000         | 𝔯      | 0.000001           | 𝔛      | 1e10 𝔯    |
|      | 100,000,000,000        | 𝔯      | 0.00001            | 𝔛      | 1e11 𝔯    |
| Tryu | 1,000,000,000,000      | 𝔯      | 0.0001             | 𝔛      | 1e12 𝔯    |
|      | 10,000,000,000,000     | 𝔯      | 0.001              | 𝔛      | 1e13 𝔯    |
|      | 100,000,000,000,000    | 𝔯      | 0.01               | 𝔛      | 1e14 𝔯    |
| Qryu | 1,000,000,000,000,000  | 𝔯      | 0.1                | 𝔛      | 1e15 𝔯    |
| Xank | 10,000,000,000,000,000 | 𝔯      | 1                  | 𝔛      | 1e16 𝔯    |


## XANK Coin Supply Algorithm

### Introduction

Cryptocurrencies are produced through a sophisticated cryptographic process known as mining. Mining involves the use of high-powered computers running hash algorithms to find solutions to cryptographic problems that vary in complexity, known as the mining difficulty.  A solution is discovered once a problem is solved and the miner is permitted to create new units of the currency. This is known as the block reward. To ensure that the currency is not subject to endless inflation, the block reward is reduced at regular intervals. The coin emission rate is the term used to describe the quantum at which new cryptocurrency is introduced into the system.


### Limited Supply

Bitcoin and Dash are two important cryptocurrencies that have upper boundaries on the amount of cryptocurrency that can be theoretically minted. Bitcoin’s total coin emission can be calculated as the sum of a geometric series, with the total emission approaching (but never reaching) 21,000,000 BTC. While Dash is based on Bitcoin, it significantly modifies the coin emission rate to offer a smoother reduction in coin emission over time. Bitcoin reduces the coin emission rate by 50% every 4 years, whereas Dash reduces the emission by one-fourteenth (approx. 7.14%) every 210,240 blocks (approx. 383.25 days). It can be seen that reducing the block reward by a smaller amount each year offers a smoother transition to a fee-based economy than Bitcoin.

Dash’s total coin emission is also the sum of a geometric series, but the ultimate total coin emission is uncertain because it cannot be known a priori how much of the 10% block reward reserved for budget proposals will actually be allocated since this depends on future voting behavior.


### Unlimited Supply and Inflation

Unlike Bitcoin, which has a maximum supply capped at 21,000,000 BTC, Ethereum does not have an overall cap. While the total annual issuance of ETH is fixed, the relative inflation decreases every year. Since the total supply increases, the inflation caused by issuance reduces.

By approximately the year 2140, the issuance of BTC ceases, and since some BTC will likely be lost each year, the monetary base of Bitcoin is expected to start shrinking at that point.

At approximately the same time, the expected rate of annual loss and destruction of ETH will balance the rate of issuance.  If the demand for ETH is still growing at that point due to an expanding economy, prices will be in a deflationary regime. 


### GDP

Almost no coins use any economic indicators to assess the current growth of the economy. They hope to adjust the emission rate, to account for price deflation, through external community-based consensus, if needed. Xank uses the current global GDP value as an economic indicator inside the emission logic to reduce deflationary pressure in the future.

GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for the depreciation of fabricated assets or for the depletion and degradation of natural resources. Data are in current U.S. dollars. Dollar figures for GDP are converted from domestic currencies using single-year official exchange rates. World Bank national accounts data provide us with the current value at \$85 trillion USD.  The global GDP shows economic growth/decline, which will, in turn, increase or decrease the Xank economy. Hence it is used as a primary factor in Xank emission. 


### Xank Network Transactions

Xank also measures the network usage or adoption by calculating the cumulative Xank collected as gas (tx fee). We release equal amounts of newly created Xank during emission. As the number of transactions in the network increases, the gas fee also collected increases. Hence the coins emitted will also increase. As the newly created Xank is evenly split between different stakeholders, the network effect is bound to increase Xank transactions.


### Xank Coin Supply

If the increase in the value obtained by holding a coin becomes larger than the value of using the coin, economically minded users will refrain from using the coin. To encourage widespread usage of the coin, the issuance of coins should be coordinated in a direct relationship to the size of the economy.

Conversely, if an infinite number of coins are issued, the value of a coin will dramatically fall as the coin will depreciate due to oversupply. If the coin discourages investors from holding it, no investors will assist in the growth of the coin economy. Therefore, the issuance policy should take this into consideration to avoid reducing and discouraging the coin’s investment value.

The initial money supply should be sufficient to ensure liquidity, and coin issuance should gradually decrease as the network’s economy stabilizes. However, if the economy grows rapidly, more coins must be issued to ensure sufficient liquidity and minimal price variance. Therefore, the maximum number of coins must remain unrestricted.

Initially, there will be 1 billion Xank coins pre-mined that will be made available to the founders, advisors, initial public token sale (ICO) participants, and early backers.


### Xank Emission Algorithm

#### Initial Design 

In our initial design, a binary logarithmic emission based on the initial year issuance(800m) was used, where the supply will double in 1.5 years, triple by the fifth year, quadruple by the thirteenth year, and quintuple by the thirty-first year; and so on. 

Emission volume is reduced by half every $2_n$ years.  For example, the 1st year 800M, the next two years 400M each year, and the next 4 years 200M each, and so on. In this distribution formula, it is self-evident that the summation of coins in the $2_n$ period always becomes 800M. So the coin issue rate converges to zero, but the sum of them diverges infinitely.

#### Current Design 

We use the binary logarithm to calculate the emission of the Xank coins in the $N^{th}$ year. The binary logarithm is the logarithm to the base 2. It is the inverse function of the power of two functions and is used to reduce the coin emission gradually. Instead of using a fixed issuance amount, Xank takes into account the current global GDP as an economic growth Indicator and Xank TPS as the network growth indicator. As the global GDP, as well as Xank TPS, is bound to increase over time, we can reduce them gradually by applying binary logarithms.

The general term of the emission sequence of Xank coins is:

$$E_n=(GDP_n + TPS_n) *(\frac{1}2)^{INT(log_2n)}$$

From the below graph, you can see that the amount of Xank released per year is very high during the initial years and gradually reduces over time. This gives rise to very high inflation during the initial period.  From the above link, you can see that any changes in GDP or TPS in the initial years cause significant variance in issuance amounts. As seen in the table, these initial volatile years correspond to the first three logarithmic cycles.

![Figure 6](images/Xank-Emission-for-100-years-en.png "Xank Emission for 100 years")

<div align="center"><strong>Figure 6</strong>: Xank Emission for 100 years</div>


To mitigate the high volatility as well as high inflation of logarithmic emission, we use a fixed emission for the first 7 years. The fixed emission amount should be selected such that, after 7 years, the total Xank emitted will be equal to that of normal binary logarithmic emission. Hence we have used 340M Xank as the fixed emission for the first 7 years, after which the binary logarithmic emission resumes.

Hence we define the general term for Xank emission per year as,

$$E_n = 340,000,000, for\ n < = 7$$

$$E_n=(GDP_n + TPS_n) *(\frac{1}2)^{INT(log_2n)}, for\ n > 7$$

where, 

*   $E_n=N^{th}$ year emission
*   $GDP_n= N^{th}$ year Global GDP divided by 100K (Rounded off to Millions)
*   $TPS_n=N^{th}$ year Xank network transactions per second
*   $INT()=$ integer-valued function which takes the integer part of the given number 
    *   for instance 
        *   $INT(1.1)=1$
        *   $INT(2)=2$
        *   $INT(\sqrt2)$ $=INT(1.414$ \.\.\. $)=1$
        *   $log_23\approxeq1.58496$ so that $INT(log_2 3)=1$


![Figure 7](images/Xank-Final-Emission-for-100-years-en.png "Xank Final Emission for 100 years")

<div align="center"><strong>Figure 7</strong>: Xank Final Emission for 100 years</div>

The partial sum of the sequence is:

$$M_n=P+\sum^n_{k=1n} E_k$$

$$M_n=P +\sum^n_{k=1} E_{340,000,000} , for\ n < = 7$$

$$M_n=P+7*340,000,000 +\sum_{k=8}^n E_k , for\ n > 7$$


where,

*   $M_n=$ Total summation of money supply up to the $N^{th}$ year
*   $P=1$ billion (Pre-mined coins.)



Mathematically it is easy to prove $E_n$ converges to zero, but $M_n$ diverges infinitely.

$$M_n=\infty\ where\ E_n=0$$



Proof: 

1. If $n$ &#8594; $\infty$, then  $log_2n$ &#8594; $\infty$ also $INT(log_2n)$ &#8594; $\infty$ so that $(\frac1 2)$ &#8594; $0, E_n=0$
2. Since $INT()$ function takes the integer part of the given numbers so that $INT(log_2n)\leq{log_2n}$ is always true, therefore the following is also true. $(\frac1 2)^{log_2n} \leq (\frac1 2)^{INT(log_2n)}$ from the definition of the logarithm $(\frac1 2)^{log_2n}=\frac1 n$ and the above relation we can see that $\frac1n \leq (\frac1 2)^{INT(log_2n)}$ using integral test $\int_{1}^{\infty}\frac1x dx \leq \int_{1}^{\infty}(\frac1 2)^{INT(log_2x)}dx, \int_{1}^{\infty}\frac1x dx =(1n(x))^\infty_1 =\infty \leq \int_{1}^{\infty}(\frac1 2)^{INT(log_2x)}dx$

By the theorem of the integral test, since the integral on the left side diverges, the series on the right side also diverges. Hence $M_n=\infty$ 

Proof end.



Using the above equation, the money supply for 100 years can be calculated by substituting _n_ to 100. 

$$M_{100}=P+7*340,000,000 +\sum_{n=8}^{100}(GDP_n + TPS_n) * (\frac1 2)^{INT(log_2n)}$$


![Figure 8](images/Xank-Money-Supply-for-100-years-en.png "Xank Money Supply for 100 years")

<div align="center"><strong>Figure 8</strong>: Xank Money Supply for 100 years</div>


We have not set a maximum coin supply and the amount of Xank emitted in a year depends on the GDP and TPS of that respective year.  The emission volume, per year, is reduced by $(GDP_n + TPS_n)$ times every $2_n$ years. 

E.g.: Considering current GDP and average TPS of 10, In the 4th logarithmic cycle(Year 8 -Year 15) 111.2M Xank is released,  in the 5th cycle(Year 16 - Year 31) 55.6M Xank and next cycle $(GDP_n + TPS_n)$ each, and so on. In this distribution formula, it is self-evident that the summation of coins in the $2_n$ period is always equal to the average value of $(GDP_n + TPS_n)$ over the period. So the coin issue rate converges to zero, but the sum of them diverges infinitely.


## **Xank Protocol Characteristics Comparison**

Xank aims to solve the Cryptocurrency Quadrilemma: price stability, fee consistency, auditable privacy, and distributed governance to become a true medium of exchange cryptocurrency. To gain a better understanding of how the Xank network will work, it can be useful to compare the network’s characteristics against those of other cryptocurrency networks. The following metrics have been used in the comparison:

*   **Stability** - can the network achieve price stability, either through network design or price stabilizing features?
*   **Consistency** - can the network achieve transaction fee consistency, either through network design or fee-stabilizing features?
*   **Privacy** - are network users given the right tools to achieve adequate levels of anonymity and fungibility while preserving public auditability?
*   **Governance** - can the network’s governance remain independent from coercion and collusion by central authorities or major stakeholders?

| Cryptocurrency     | Stability | Consistency | Privacy | Governance |
| ------------------ | :-------: | :---------: | :-----: | :--------: |
| Avalanche          |     ✕     |      ✓      |    ✕    |     ✓      |
| Bitcoin            |     ✕     |      ✕      |    ✕    |     ✕      |
| BitShares (BitUSD) |     ✓     |      ✕      |    ✕    |     ✕      |
| Carbon             |     ✓     |      ✕      |    ✕    |     ✕      |
| Cosmos             |     ✕     |      ✕      |    ✕    |     ✓      |
| Dash               |     ✕     |      ✕      |    △    |     ✓      |
| Digix (DGX)        |     ✓     |      ✕      |    ✕    |     ✕      |
| EOS                |     ✕     |      ✕      |    ✕    |     ✓      |
| Ethereum           |     ✕     |      ✕      |    ✕    |     ✕      |
| Libra (Diem)       |     ✓     |      ✕      |    ✕    |     ✓      |
| Maker (DAI)        |     ✓     |      ✕      |    ✕    |     ✕      |
| Monero             |     ✕     |      ✕      |    △    |     ✕      |
| Pivx               |     ✕     |      ✕      |    △    |     ✓      |
| Polkadot           |     ✕     |      ✕      |    ✕    |     ✓      |
| XRP                |     ✕     |      ✕      |    ✕    |     ✕      |
| Saga               |     ✓     |      ✕      |    ✕    |     ✕      |
| Synthetix          |     ✓     |      ✕      |    ✕    |     ✓      |
| Terra              |     ✓     |      ✕      |    ✕    |     ✓      |
| Tether             |     ✓     |      ✕      |    ✕    |     ✕      |
| Xank               |     ✓     |      ✓      |    ✓    |     ✓      |
| Zcash              |     ✕     |      ✕      |    △    |     ✕      |
△ No auditability 

# References and Resources

Understanding the Governance and Budget System

[https://dashpay.atlassian.net/wiki/spaces/DOC/pages/8585240/Understanding+the+Governance+and+Budget+System](https://dashpay.atlassian.net/wiki/spaces/DOC/pages/8585240/Understanding+the+Governance+and+Budget+System)

The Key to Bridgewater's Success: A Real Idea Meritocracy

[https://www.linkedin.com/pulse/key-bridgewaters-success-real-idea-meritocracy-ray-dalio](https://www.linkedin.com/pulse/key-bridgewaters-success-real-idea-meritocracy-ray-dalio)

Employees at the world's largest hedge fund use iPads to rate each other's performance in real-time — see how it works

[http://www.businessinsider.com/bridgewater-ray-dalio-radical-transparency-app-dots-2017-9](http://www.businessinsider.com/bridgewater-ray-dalio-radical-transparency-app-dots-2017-9)

Special Drawing Right (SDR)

[https://www.imf.org/external/np/exr/facts/sdrcb.htm](https://www.imf.org/external/np/exr/facts/sdrcb.htm) 

Stablecoins: designing a price-stable cryptocurrency

[https://hackernoon.com/stablecoins-designing-a-price-stable-cryptocurrency-6bf24e2689e5](https://hackernoon.com/stablecoins-designing-a-price-stable-cryptocurrency-6bf24e2689e5)

Binary logarithm

[https://en.wikipedia.org/wiki/Binary_logarithm](https://en.wikipedia.org/wiki/Binary_logarithm)

Protocol Spotlight: Avalanche Part 1

[https://flatoutcrypto.com/home/avalancheprotocol](https://flatoutcrypto.com/home/avalancheprotocol)

Protocol Spotlight: Avalanche Part 2

[https://flatoutcrypto.com/home/avalancheprotocolpart2](https://flatoutcrypto.com/home/avalancheprotocolpart2)

The Mathematics of Agile Communication

[https://theagiledirector.com/article/2013/12/09/the-mathematics-of-agile-communication/](https://theagiledirector.com/article/2013/12/09/the-mathematics-of-agile-communication/)

Avalanche (AVA) — Blockchain 3.0: A Novel Metastable Consensus Protocol

[https://hackernoon.com/avalanche-ava-blockchain-3-0-a-novel-metastable-consensus-protocol-28cdc4ee8984](https://hackernoon.com/avalanche-ava-blockchain-3-0-a-novel-metastable-consensus-protocol-28cdc4ee8984)

Demystifying “Snowflake to Avalanche”

[https://medium.com/@elseidy/demystifying-snowflake-to-avalanche-966f56c33fd7](https://medium.com/@elseidy/demystifying-snowflake-to-avalanche-966f56c33fd7)

“Snowflake to Avalanche” Consensus Protocol Family: Overview and Technicality

[https://medium.com/@marcomanoppo/snowflake-to-avalanche-consensus-protocol-family-overview-and-technicality-68db9febfa1](https://medium.com/@marcomanoppo/snowflake-to-avalanche-consensus-protocol-family-overview-and-technicality-68db9febfa1)

Snowflake to Avalanche: A Novel Metastable Consensus Protocol Family for Cryptocurrencies

[http://muratbuffalo.blogspot.com/2018/06/snowflake-to-avalanche-novel-metastable.html](http://muratbuffalo.blogspot.com/2018/06/snowflake-to-avalanche-novel-metastable.html)

Bitcoin Cash and Avalanche Video:

[https://www.youtube.com/watch?v=F1HZSKdR7eA](https://www.youtube.com/watch?v=F1HZSKdR7eA)




## Notes

<b id="f1">1</b>:Convert XDR/USD. International Monetary Fund (IMF) Special Drawing Rights to United States Dollar [↩](#a1)
    https://www.xe.com/currencyconverter/convert/?Amount=1&From=XDR&To=USD

<b id="f2">2</b>:Ray Dalio’s meritocratic governance system, as outlined in his essay, which led to the success of the company he founded, Bridgewater [↩](#a2)
    https://www.linkedin.com/pulse/key-bridgewaters-success-real-idea-meritocracy-ray-dalio

<b id="f3">3</b>:Avalanche, which reached 6,500 transactions per second on a test network of 1,000 nodes and stabilized at 4,500 transactions per second [↩](#a3)
    https://medium.com/avalabs/avalanche-ava-monthly-update-may-2019-7a78657217f4

<b id="f4">4</b>:As of September 2017, 204.2 billion SDRs ($291 billion USD equivalent) had been created and allocated to the member states. [↩](#a4)
    https://www.imf.org/en/About/Factsheets/Sheets/2016/08/01/14/51/Special-Drawing-Right-SDR

<b id="f5">5</b>:IMF’s 2016 factsheet [↩](#a5)
    https://www.imf.org/external/np/exr/facts/sdrcb.htm 

<b id="f6">6</b>:How a meritocratic governance system and the implementation of its key principles and components were intricate to the success of the Bridgewater venture. [↩](#a6)
    https://qz.com/1071749/bridgewater-associates-ceo-ray-dalio-explains-the-dot-collector-feedback-tool-his-company-uses-to-rate-employees/

<b id="f7">7</b>:Seeing as the SDR rate is measured against a basket of weighted currencies and is announced and published by the IMF on its website. [↩](#a7)
    https://www.imf.org/external/np/fin/data/rms_sdrv.aspx

<b id="f8">8</b>:Multisignature security, cold and hot wallet usage, Hierarchical Deterministic (HD) wallets (BIP32) [↩](#a8)
    https://bitcoin.org/en/glossary/hd-protocol

<b id="f9">9</b>:Sustainable Development Goals (SDGs) [↩](#a9)
    https://www.un.org/sustainabledevelopment/

<b id="f10">10</b>:The Constitution of the Xank Decentralized Autonomous Organization [↩](#a10)
    https://github.com/xankmoney/governance/blob/master/xank-constitution.md/

<b id="f11">11</b>:A commentary, analysis, observations and extracts based on a post by Haseeb Qureshi on Hackernoon, where he explains the key concepts behind the current batch of stablecoins. [↩](#a11)
    https://hackernoon.com/stablecoins-designing-a-price-stable-cryptocurrency-6bf24e2689e5
