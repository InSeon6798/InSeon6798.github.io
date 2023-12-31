---
layout: page
image: /assets/img/blog/getout_company.jng
description: >
  회사 활동
hide_description: true
sitemap: false
---



# 객체지향

## SOLID(객체 지향 설계) 5대 원칙

* SRP(Single Responsibility Principle) : 단일 책임 원칙

* OCP(Open/Closed Principle) : 개방 폐쇄 원칙

* LSP(Liskov Substitution Principle) : 리스코프 치환 원칙

* ISP(Interface Segregation Principle) : 인터페이스 분리 원칙

* DIP(Dependency Inversion Principle) : 의존관계 역전 원칙

-- SOLID란 객체지향 프로그래밍 및 설계의 5가지 기본원칙으로 소프트웨어 작업에서 프로그래머가 소스코드가 읽기 쉽고 확장하기 쉽게 될 때까지 소프트웨어 소스코드를 리팩토링하여 코드 냄새를 제거하기 위해 적용할 수 있는 지침

(코드 냄새 : 프로그래밍 코드에서 더 심오한 문제를 일으킬 가능성이 있는 프로그램 소스 코드의 특징)

(리팩토링 : 결과의 변경 없이 코드의 구조를 재조정하며 코드를 이해하고 수정하기 쉽게 만드는게 목적)

### 단일 책임 원칙

-- 모든 클래스는 하나의 책임만 가지며, 클래스는 그 책임을 완전히 캡슐화해야함
-- 어떤 클래스나 모듈은 변경하려는 단 하나의 이유만을 가져야 한다고 결론 짓는다.

### 개방 폐쇄 원칙

-- **확장**에 대해 열려 있어야 하고, **수정**에 대해서는 닫혀 있어야 한다는 프로그래밍 원칙

-- 1. 확장에 대해 열려 있다? : 모듈의 동작을 확장할 수 있다는 것을 의미하며 변경에 맞게 새로운 동작을 추가해 모듈을 확장할 수 있다. 즉, 모듈이 하는 일을 변경할 수 있다.

-- 2. 수정에 대해 닫혀 있다? : 모둘의 소스 코드, 바이너리 코드 등을 수정하지 않아도 모듈의 기능을 확장하거나 변경할 수 있다. 핵심요소는 추상화


### 리스코프 대체 원칙

-- 기본 클래스에 대한 포인터 또는 참조를 사용하는 함수는 모르는 사이에 파생 클래스의 개체를 사용할 수 있어야 한다. 

### 인터페이스 분리 원칙

-- 많은 클라이언트 별 인터페이스가 하나의 범용 인터페이스보다 낫다

### 종속성 반전 원칙

-- 구체화되지 않은 추상화에 의존하라
