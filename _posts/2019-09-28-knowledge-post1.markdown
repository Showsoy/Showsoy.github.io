---
layout: post
title: "개발모델, 개발방법론"
date: 2019-09-29
categories: knowledge
author: "showsoy"
---
<h1>SDLC (System Development Life Cycle)</h1><br/>
<h4>○소프트웨어의 생성 ~ 소멸</h4>
<h4><br />○타당성조사 -&gt; 요구분석 -&gt; 설계 -&gt; 개발 -&gt; 테스트 -&gt; 유지보수 -&gt; 폐기&nbsp;</h4>
<p style="padding-left: 30px;">1. 타당성조사 : 고객의 요구 사항이 실현 가능한지, 또 합리적인지를 판단. 현재 몸담고 있는 회사의 영업파트에서는 전혀 이루어지고 있지 않은 단계이다. 1단계 부터 글러먹은&nbsp;<br /> 2. 요구분석 : 요구사항에 대한 식별 및 상세화. 기능요구사항 / 비기능요구사항이 있다.&nbsp;<br /> 3. 설계 : 위의 요구사항 명세를 준수하는 소프트웨어 설계&nbsp;<br /> 4. 개발 및 구현 : 코딩 , 내가 하는거<br /> 5. 테스트 : V&amp;V . 검증(Verification) -&gt; 명세대로 기술되었고 동작하는가?, 확인(Validation) -&gt; 명세를 근간으로 사용자의 요구사항에 충족하는가?&nbsp;<br /> 6. 폐기 : 소프트웨어의 수명이 끝남.</p>
<h4><br />○종류 [개발모델]&nbsp;</h4>
<p style="padding-left: 30px;">1. 폭포수 모델 (Waterfall Model)&nbsp; : 순차적으로 개발, 고전적, 완벽히 마무리해야 다음단계로 갈 수 있다.&nbsp;<br /> 2. 프로토타이핑 (prototyping Model) : 위험을 최소화 하고 점진적으로 개발, 프로토 타입을 만들고 완성품을 예측 , 비용이 많이 든다&nbsp;<br /> 3. 나선형 모델 (Spiral Model) : (폭포수 장점 + 프로토 장점) + 위험분석, 목표설정-&gt;위험분석-&gt;개발/구현-&gt;고객확인-&gt;반복여부결정&nbsp;<br /> 4. 반복적 개발 모델 (Iterative Model) : 프로토타이핑 모델을 기반으로 한다.<br />- 증분형 : 시스템을 기능별로 나누고 일부기능을 릴리즈하여 하나씩 붙여나감, 병렬형<br /> - 진화형 : 프로토 타입을 만든 후 지속적으로 반영&nbsp;<br /> 5. RAD 개발 모델 (Rapid Application Development) : 2 ~ 3개월 짧은 개발 주기로&nbsp; &nbsp; &nbsp;제품 개발을 위한 순차적 프로세스 모델로 Tool을 사용, CASE(자동화 툴) 도구 및 재사용 가능한 Library 등을 활용, 고객참여, 신속개발&nbsp; &nbsp;<br /> 6. 클린룸 모델 (Cleanroom Model) : 반도체 공정에서 사용되는 밀폐된 공간을 의미</p>
<h4><br />○고려사항&nbsp;</h4>
<p style="padding-left: 30px;">1. 프로젝트 규모와 성격<br /> 2. 개발방법과 관리방법의 연계성<br />3. 고객 요구사항에 대한 이해 수준과 변경 가능성<br />4. 프로젝트 진행 자원과 수행 능력</p>
<p style="padding-left: 30px;">&nbsp;</p>
<p style="padding-left: 30px;">&nbsp;</p>
<h1>소프트웨어 개발방법론 (Software Development Methodology)</h1><br/>
<h4>○소프트웨어 개발의 전 단계에 대한 경험을 공학적 기법으로 정형화하여 체계를 잡고 표준화한 이론</h4>
<h4><br />○개발방법론의 진화&nbsp; 구조적 기법 -&gt; 정보공학 기법 -&gt; 객체지향 기법 -&gt; CBD기법 -&gt; Agile (적시성 중시)</h4>
<h4><br />○개발방법론의 구성요소&nbsp;</h4>
<p style="padding-left: 30px;">작업절차(작업의 단계, 세부 작업, 활동 순서), 작업방법(단계별로 수행해야 하는 일)&nbsp; , 산출물 (단계별 산출물), 관리(진행 사항 기록), 기법(단계별 작업 수행 시 기술)&nbsp; , 도구(기법 별 지원도구)</p>
<h4><br />○개발방법론의 종류</h4>
<p style="padding-left: 30px;">1. 구조적 방법론 : 요구사항을 파악하여 문서화, 정형화된 분석 절차에 따라 체계적, 모듈화<br />2. 정보공학 방법론 : 기업정보시스템에 공학적 기법을 적용, 데이터 중심<br /> 3. 객체지향 방법론 : 자료와 기능이 캡슐화, 추상화, 다형성, 정보은닉, 상속성을 가짐. 재사용성 향상<br /> 4. CBD (Component-Based Development) 방법론 : 컴포넌트 중심 개발, 재사용성 향상<br /> 5. Agile Process : RAD 개발모델 기반, 실질적 코딩을 통한 방법론, 스프린트 개발 사이클 사용<br /> - XP : 테스팅 중심, TDD (테스트를 먼저 만들고 제대로 동작하도록 구현)<br /> - SCRUM :　스프린트 주기를 정하고 생산되는 프로토 타입을 통해 사용자들의 피드백을 받으며 더 나은 결과물을 구현하는 것</p>