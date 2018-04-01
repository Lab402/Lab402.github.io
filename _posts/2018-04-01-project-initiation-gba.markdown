---
layout: post
title: [프로젝트 수행] Modern GBA
date: 2018-04-01 14:40:00 +0900
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: IMG_0539.jpg
categories: ModernGBA
tags: [VisualBoyAdvance,]
---

# [프로젝트 수행] Modern GBA

## 기본정보

프로젝트 착수일: 2018년 04월 01일
프로젝트 수행자: 박일순, 장민수, 김재훈, 민준, 신종환
프로젝트 목표
    - 최종 목표: 기존 소스코드를 최신 C++ 표준에 맞도록 개선
    - 기존 소스코드 분석
    - Modern C/C++ 스터디
    - 소스코드 리팩토링
Github 주소: https://github.com/lab402/VisualBoyAdvance

## 프로젝트 수행 계획

프로젝트 수행 방법
    - 기존 소스코드 분석
        - Visual Studio 2017 상에서 빌드해보기
        - Doxygen,PlantUML을 이용한 기존 소스코드 Documenting
            - 작성의 용이성을 위해 소스코드 부분별로 나누어서 문서 작성
            - 크게 ARM 에뮬레이션, Windows 어플리케이션으로 나뉨
    - Modern C/C++ 스터디
        - 참고서적: Effective Modern C++
    - 소스코드 리팩토링
        - 참고서적: Clean Code

## 프로젝트 수행 현황
    Visual Studio 2017 상에서 빌드하기 [링크]
    Doxygen,PlantUML을 이용한 소스코드 Documenting
    Modern C/C++ 스터디
    소스코드 리팩토링

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>    
