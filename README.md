# withlionbuddha.github.io

AI 개발과 소프트웨어 엔지니어링 과정에서 학습하고 직접 구현한 내용을 정리하는 **기술 블로그 및 포트폴리오**입니다.

단순한 개념 정리에 그치지 않고, 모델 구현부터 백엔드 아키텍처, 테스트, API 연동, 컨테이너 기반 실행 환경까지 실제 개발 과정에서 확인한 내용을 기록합니다.

## Blog

기술 블로그에서는 다음과 같은 주제를 다룹니다.

- **AI / Machine Learning**
  - Transformer 구조와 Multi-Head Attention
  - Decoder-only SLM 구현 및 학습
  - PyTorch Training / Validation Pipeline
  - NumPy 기반 Neural Network 및 Backpropagation 구현

- **RAG / Agent**
  - Retrieval-Augmented Generation 구조
  - LangChain / LangGraph 기반 Agent 설계
  - LLM 서비스 구조와 API 연동

- **Backend / Architecture**
  - Spring Boot 및 REST API
  - Static Web Server와 WAS 구성
  - Frontend / Backend API 연동 구조
  - 소프트웨어 아키텍처와 설계 원칙

- **Engineering**
  - OOP / SOLID
  - Unit Test
  - Docker / Nginx / Linux
  - GitHub 기반 개발 및 운영

## Projects

블로그와 함께 직접 구현한 프로젝트를 정리합니다.

### Decoder-only SLM

PyTorch 기반의 소형 언어모델 학습 프로젝트입니다.

- SentencePiece BPE Tokenizer
- Transformer Decoder
- Causal Mask
- Training / Validation Loop
- Checkpoint 및 학습 파이프라인

### Fully Connected Neural Network

딥러닝 내부 동작을 이해하기 위해 NumPy만으로 신경망을 직접 구현한 프로젝트입니다.

- Forward Propagation
- Backpropagation
- Activation Function
- Loss Function
- Optimizer
- Unit Test

### RAG & Agent Service

LLM, 검색 파이프라인, Vector DB, Agent 흐름을 실제 서비스 구조로 확장하는 프로젝트입니다.

- RAG
- LangChain
- LangGraph
- FastAPI
- LLM API Integration

## Tech Stack

`Python` · `PyTorch` · `NumPy` · `Transformer` · `SLM` · `RAG` · `LangChain` · `LangGraph` · `Spring Boot` · `REST API` · `Django` · `PostgreSQL` · `Docker` · `Nginx` · `Linux` · `GitHub Actions`

## Purpose

이 블로그는 다음 세 가지 목적을 가지고 운영합니다.

1. 학습한 기술을 구현 가능한 수준으로 정리합니다.
2. 구현 과정에서 발생한 문제와 해결 과정을 기록합니다.
3. AI 모델부터 API, 서버 구성, 운영 환경까지 연결되는 전체 개발 흐름을 설명할 수 있는 자료를 축적합니다.

## Repository Structure

```text
withlionbuddha.github.io/
├── assets/       # CSS 및 정적 리소스
├── blog/         # 기술 블로그
├── projects/     # 프로젝트 상세 페이지
├── index.html    # Portfolio / Home
└── README.md
```

## Site

GitHub Pages 기반으로 운영하는 개인 기술 블로그 및 AI Developer Portfolio입니다.

- Blog: `blog/index.html`
- Portfolio: `index.html`
- GitHub: https://github.com/withlionbuddha

---

> **Engineering Notes**  
> AI 모델 구현, 백엔드 아키텍처, 테스트와 운영 과정에서 직접 확인한 내용을 기록합니다.
