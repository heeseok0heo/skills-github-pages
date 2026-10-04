---
title: "P-Engine: 3D Reconstruction and Segmentation"
date: 2026-10-05T00:00:00+09:00
categories: ["Computer Graphics", "AI"]
tags: ["3D Reconstruction", "Grounding DINO", "SAM2", "3D Segmentation", "Skeletonization", "OpenGL"]
---

## Overview

P-Engine은 3D Reconstruction, AI 기반 객체 탐지·분할, 3D Segmentation, Skeletonization 및 OpenGL Rendering을 연결하는 3D 데이터 처리·시각화 프로젝트입니다. AI 모델의 인식 결과와 3D 기하 처리를 함께 다루며, 재구성된 형상과 분할 결과를 시각적으로 검토하는 워크플로에 초점을 맞춥니다.

## Focus Areas

- 3D Reconstruction: 대상의 3차원 형상을 재구성하고 후속 분석을 위한 기하 데이터 구성
- Grounding DINO: 텍스트 프롬프트 기반 객체 탐지를 통한 관심 대상 식별
- SAM2: 이미지·영상의 객체 분할 결과를 후속 3D 처리에 활용
- 3D Segmentation: 3차원 데이터에서 관심 영역을 분리하고 형상 분석과 연결
- Skeletonization: 형상의 중심 구조를 추출하여 연결 관계와 기하 특성 분석
- OpenGL Rendering: 재구성 형상, 분할 영역 및 스켈레톤의 시각화

## Architecture Focus

- 객체 탐지·분할, 3D 재구성, 기하 분석 및 렌더링 단계의 책임과 데이터 흐름 정의
- 2D 인식 결과와 3D 표현을 연결할 때 필요한 좌표계 및 데이터 대응 관계 관리
- AI 추론 모듈과 기하 처리·렌더링 모듈 사이의 인터페이스 설계
- 중간 처리 결과를 시각적으로 확인할 수 있는 분석·검증 워크플로 구성

## Technologies

Grounding DINO, SAM2, 3D Reconstruction, 3D Segmentation, Skeletonization, OpenGL
