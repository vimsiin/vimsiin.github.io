---
layout: post
title: register vs cache
categories: [hardware]
---

캐시와 레지스터가 다른 것은 무엇일까?

레지스터는 매우 소규모로 존재한다. 32개 정도. 크기도 정확한 규격이 있다. 이것들은 하드웨어 플립플롭으로 이루어져 있으며, 가격이 매우 비싸기 때문에 소규모로 만들게 된다. CPU가 직접 접근하고 사용하는 메모리라고 생각을 하면 된다.

캐시는 메인 메모리에서 자주 사용하는 내용을 저장하고 있는 것이다. 이 캐시는 레지스터보다 크기가 크다. 캐시는 DRAM을 사용하는 메인 메모리보다 값이 비싸지만 가격이 비싼 SRAM을 사용해서 만든다. 캐시와 레지스터 모두 CPU안에 내장되어 있다.
