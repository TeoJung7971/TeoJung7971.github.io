---
title: "[FSV] Refactoring"
description: "Refactoring the Original Stock Price Prediction Module of FSV"
author: TeoJung
date: 2026-03-19 14:00:00 +0900         
categories:
  - Personal-Project
tags:
  - Personal Project
  - Time Series Data
pin: false
math: true
media_subpath: /assets/img/posts/20260319/
---

## Introduction

해당 문서는 2025년 상반기 기획 및 작업하였던 Financial Stock Visualizer, 이하 FSV에 사용되었던 주식 예측 모듈 코드의 **문제 분석 및 수정, 리팩토링, 향후 개선 및 발전 방향을 정리**하기 위해 작성되었다.

기본적인 사항은 아래와 같다.
> • 목적: 기업 가치 분석을 바탕으로한 장기(10년) 데이터 시각화 프로젝트에 있어서 미래의 데이터셋 구축 목적  
> • 작업기간: 2025.03 ~ 2025.06  
> • 작업환경: Windows
> • 사용언어: Python
> • 데이터셋: OPENDART api 등을 통하여 수집된 국내 기업 주가 데이터  
> • 예측모델: LSTM, PatchTST()

코드는 해당 [GitHub Repository]()에서 확인 가능하다.

**<mark style='background-color: #e2e8f0;'>Refactoring은 Claude Code의 도움을 받으며 진행하였으며, 미처 확인치 못한 오류나 권리 문제가 포함되어 있을 수 있음</mark>*
{: style="font-size: 0.85rem !important;" }

## Former Problems

### Data Leakage

### Code Redundancy

## Structures

### Original Structure
    - Modeling
      - Data
      - Model Result: LSTM 기반 모델 파라미터 저장
      - models: PatchTST 기반 모델 파라미터 저장
      - 
    - Not Used

### Modified Structure

## Refactoring

## Further Plan

----

## References