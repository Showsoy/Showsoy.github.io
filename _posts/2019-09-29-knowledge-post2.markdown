---
layout: post
title: "트랜잭션, 무결성"
date: 2019-09-29
categories: knowledge
author: "showsoy"
---
<h1>트랜잭션 (transaction)</h1>
<p>&nbsp;</p>
<h4><br />○ 트랜잭션이란?</h4>
<p style="padding-left: 30px;">트랜잭션은 하나의 논리적 기능을 수행하기 위한 작업의 단위<br /> 데이터베이스의 일관된 상태를 또 다른 일관된 상태로 변화시킴</p>
<p style="padding-left: 30px;">&nbsp;</p>
<h4>○&nbsp;트랜잭션이 하나의 논리적 기능을 수행하기 위해서는 트랜잭션에 포함된 모든 연산이 불가분의 관계로 실행되어야 한다. 이런 불가분성을 달성하기 위해 트랜잭션이 가져야 될 특성은 다음과 같다.</h4>
<p style="padding-left: 30px;">1. Atomicity 원자성 : 자신의 연산은 all or nothing 실행만 있다.<br />2. Consistency 일관성 : 트랜잭션이 성공했다면, 데이터베이스는 그 일관성을 유지해야 한다. 일관성은 특정한 조건을 두고, 그 조건을 만족하는지를 확인하는 방식으로 검사할 수 있다.<br />3. Isolation 격리성 :&nbsp;트랜잭션이 실행 중에 있는 연산의 중간 결과는 다른 트랜잭션이 접근할 수 없다.<br />4. Durability 영속성 : 일단 실행을 완료하면 그 결과는 영속적이다.</p>
<p>&nbsp;</p>
<h4>○ 데이터베이스를 접근하여 갱신 연산을 수행하는 트랜잭션은 다음과 같은 상태 중 하나에 속하게 된다.</h4>
<p style="padding-left: 30px;">1. Active 활동 : 트랜잭션이 Begin_Trans부터 실행을 시작하였거나 실행 중인 상태, Partially committed 부분 완료,&nbsp;트랜잭션이 마지막 명령문을 실행한 직후의 상태<br />2. Failed 실패 :&nbsp;정상적 실행을 더 이상 계속할 수 없어서 중단한 상태<br />3. Aborted 철회 :&nbsp;트랜잭션에 실패하여 Rollback 연산을 수행한 상태<br />4. Committed 완료 : 트랜잭션이 실행을 성공적으로 완료하여 Commit 연산을 수행한 상태</p>
<p>&nbsp;</p>
<h4>○&nbsp;트랜잭션의 상태</h4>
<p>&nbsp;</p>
<p>&nbsp;</p>
<h1>Database의 독립성</h1>