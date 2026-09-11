# 깃허브 저장소 포크 목록 과 저장소 설명

> 기준일: 2026-09-11 · **현재 공개 포크 187개** · 대상 계정: [`sodam-AI`](https://github.com/sodam-AI?tab=repositories) · 전부 공개(Public)
> 이 문서는 **현재 `sodam-AI` 계정에 실제로 존재하는 공개 포크만**을 기준으로 다시 확인했고, 기능별 카테고리를 기존 14개보다 더 세분화해 정리했습니다.

---

## 이 문서를 읽기 전에 — 꼭 알아두면 좋은 말 9가지

컴퓨터나 개발을 한 번도 안 해보신 분도 이해할 수 있도록, 아래에서 자주 나오는 낱말을 먼저 풀어드립니다. (한 번만 읽고 넘어가시면 아래 187개 설명이 훨씬 쉬워집니다.)

| 용어 | 쉬운 설명 |
|---|---|
| **깃허브(GitHub)** | 프로그램을 만드는 사람들이 자기가 만든 프로그램의 "설계도(코드)"를 인터넷에 올려두고 나누는 창고 같은 사이트 |
| **저장소(Repository, 줄여서 "레포")** | 그 창고 안에 있는 프로젝트 하나하나의 폴더 |
| **포크(Fork)** | 남이 만든 저장소를 "내 창고에도 복사해서 갖다 놓기" 기능. 원본은 그대로 있고, 내 계정에도 똑같은 사본이 하나 더 생깁니다 |
| **원본(원조 저장소)** | 그 포크의 뿌리가 된, 맨 처음 만든 사람의 저장소 |
| **오픈소스** | 설계도(코드)를 누구나 볼 수 있게, 대부분 무료로 공개해 둔 것 |
| **터미널 / CLI** | 마우스로 클릭하는 예쁜 화면 없이, 까만 화면에 글자로 명령을 쳐서 쓰는 방식(또는 그런 프로그램) |
| **AI 에이전트** | 사람이 "이거 해줘"라고 말하면 스스로 판단해서 여러 단계를 대신 처리해주는 AI. "AI 비서"라고 생각하면 됩니다 |
| **플러그인 / 스킬** | 이미 있는 프로그램(주로 아래 나오는 Claude Code, Codex)에 끼워 넣는 "추가 기능 부품". 스마트폰에 앱을 추가로 설치하는 것과 비슷합니다 |
| **MCP** | 서로 다른 AI 프로그램들이 도구·정보를 주고받을 수 있게 만든 공통 연결 규격. "AI들끼리 통하는 전화선"이라고 보면 됩니다 |

> ⚠️ 아래 목록은 **`sodam-AI` 계정에 현재 실제로 존재하는 공개(Public) 포크만** 포함합니다. 다른 계정(`SoDam-Fork` 등)에만 있는 저장소나 현재 `sodam-AI`에서 확인되지 않는 저장소는 넣지 않았습니다.

---

## 전수 점검 결과 (누락·오류·모순 확인)

GitHub의 현재 `sodam-AI` 공개 저장소를 다시 조회해 포크 여부까지 분리해서 확인한 결과입니다.

- ✅ **현재 공개 포크 총 187개 확인**: `sodam-AI` 계정의 Public + Fork 조건으로 끝 페이지까지 확인했습니다.
- ✅ **다른 계정 혼입 제거**: 이전 191개 문서에 `SoDam-Fork` 링크로 들어갔던 항목 가운데 현재 `sodam-AI`에 없는 `ECC`, `open-command`, `openclaude`, `solo-skills` 4개를 제거했습니다.
- ✅ **현재 계정에서 사라진 기존 항목 제거**: `ComfyUI_AI-Toolkit_Easy_Install`, `anatomy`는 현재 `sodam-AI` 공개 저장소에서 확인되지 않아 제거했습니다.
- 🆕 **현재 계정 신규 포크 2개 추가**: `OmniRoute`(원본 `diegosouzapw/OmniRoute`), `agent-skills`(원본 `addyosmani/agent-skills`)를 추가했습니다.
- 🔗 **계정 링크 통일**: 이전 문서에서 `SoDam-Fork` 주소로 들어갔지만 현재 `sodam-AI`에도 실제 존재하는 항목은 모두 `https://github.com/sodam-ai/...` 주소로 바로잡았습니다.
- 🧩 **카테고리 세분화**: 기존 14개 대분류를 기능·사용 목적 기준 **28개 세부 카테고리**로 다시 나눴습니다.
- ✅ **중복 0개 / 미분류 0개**: 187개 저장소가 각각 정확히 한 카테고리에만 들어가도록 점검했습니다.

---

## 한눈에 보기 (세분화 카테고리 목록)

| # | 분류 | 개수 |
|---|---|---|
| 1 | [AI 코딩 CLI 본체](#1-ai-코딩-cli-본체-6개) | 6 |
| 2 | [개인용 AI 에이전트·채팅 작업공간](#2-개인용-ai-에이전트채팅-작업공간-6개) | 6 |
| 3 | [Claude Code 확장·설정·계정 관리](#3-claude-code-확장설정계정-관리-13개) | 13 |
| 4 | [Codex 확장·플러그인·하네스](#4-codex-확장플러그인하네스-6개) | 6 |
| 5 | [공용 에이전트 스킬·플러그인·하네스](#5-공용-에이전트-스킬플러그인하네스-16개) | 16 |
| 6 | [AI 코딩 품질검증·자기개선·비용 최적화](#6-ai-코딩-품질검증자기개선비용-최적화-11개) | 11 |
| 7 | [멀티에이전트·오케스트레이션·에이전트 운영](#7-멀티에이전트오케스트레이션에이전트-운영-10개) | 10 |
| 8 | [AI 앱·워크플로우·에이전트 프레임워크](#8-ai-앱워크플로우에이전트-프레임워크-7개) | 7 |
| 9 | [AI 모델 게이트웨이·라우팅](#9-ai-모델-게이트웨이라우팅-1개) | 1 |
| 10 | [AI 메모리·지식 그래프·컨텍스트 관리](#10-ai-메모리지식-그래프컨텍스트-관리-8개) | 8 |
| 11 | [검색·리서치·문서 이해·법률·공개 API](#11-검색리서치문서-이해법률공개-api-6개) | 6 |
| 12 | [브라우저·컴퓨터 조작·웹 자동화](#12-브라우저컴퓨터-조작웹-자동화-7개) | 7 |
| 13 | [메신저·원격 제어·에이전트 통신](#13-메신저원격-제어에이전트-통신-11개) | 11 |
| 14 | [Hermes 생태계 보조도구·접속 환경](#14-hermes-생태계-보조도구접속-환경-5개) | 5 |
| 15 | [알림·HUD·작업 상태 모니터링](#15-알림hud작업-상태-모니터링-3개) | 3 |
| 16 | [UI·UX·웹 디자인·컴포넌트](#16-uiux웹-디자인컴포넌트-12개) | 12 |
| 17 | [이미지·그래픽·폰트·로고·앱 스크린샷](#17-이미지그래픽폰트로고앱-스크린샷-7개) | 7 |
| 18 | [프레젠테이션·차트·다이어그램](#18-프레젠테이션차트다이어그램-6개) | 6 |
| 19 | [영상·화면 녹화·모션·애니메이션](#19-영상화면-녹화모션애니메이션-9개) | 9 |
| 20 | [문서·오피스·기획서·전자책 제작](#20-문서오피스기획서전자책-제작-3개) | 3 |
| 21 | [파일 변환·OCR·CAD·PDF 처리](#21-파일-변환ocrcadpdf-처리-4개) | 4 |
| 22 | [한국어 글쓰기·문체·콘텐츠 품질](#22-한국어-글쓰기문체콘텐츠-품질-2개) | 2 |
| 23 | [SEO·콘텐츠 마케팅·SNS 자동화](#23-seo콘텐츠-마케팅sns-자동화-3개) | 3 |
| 24 | [투자·금융·시장 정보·뉴스레터 자동화](#24-투자금융시장-정보뉴스레터-자동화-3개) | 3 |
| 25 | [보안·권한·의존성 안전 점검](#25-보안권한의존성-안전-점검-3개) | 3 |
| 26 | [터미널·쉘·AI 도구 전환·개발 작업환경](#26-터미널쉘ai-도구-전환개발-작업환경-7개) | 7 |
| 27 | [AI 연구·모델 성능·실험적 기반기술](#27-ai-연구모델-성능실험적-기반기술-6개) | 6 |
| 28 | [생활·교육·개발자 행사·기타 유틸리티](#28-생활교육개발자-행사기타-유틸리티-6개) | 6 |

각 항목은 `**[내 계정 사본 이름](링크)** *(원본: [원래 만든 사람/원본 이름](링크))* — 무엇을 하는 도구인지 한두 문장 설명` 형식입니다. **파란 글씨(이름)를 누르면 바로 그 저장소로 이동**합니다.

---

## 1. AI 코딩 CLI 본체 (6개)

터미널에서 직접 대화하며 코드를 작성·수정하는 독립형 AI 코딩 비서 본체입니다.

- **[claude-code](https://github.com/sodam-ai/claude-code)** *(원본: [anthropics/claude-code](https://github.com/anthropics/claude-code))* — Anthropic(클로드를 만든 회사)이 만든 공식 AI 코딩 비서. "이 버그 고쳐줘"처럼 말로 시키면 내 프로젝트 코드를 이해하고 직접 고쳐줍니다. 지금 대화하고 계신 이 프로그램 본체입니다.
- **[codex](https://github.com/sodam-ai/codex)** *(원본: [openai/codex](https://github.com/openai/codex))* — OpenAI가 만든 터미널용 AI 코딩 비서. claude-code와 비슷한 역할이지만 OpenAI의 AI 모델을 사용합니다.
- **[gemini-cli](https://github.com/sodam-ai/gemini-cli)** *(원본: [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli))* — 구글이 만든 터미널용 AI 비서로, 구글의 Gemini AI를 터미널에서 바로 쓸 수 있게 해줍니다.
- **[qwen-code](https://github.com/sodam-ai/qwen-code)** *(원본: [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code))* — 중국 알리바바의 Qwen AI를 쓰는 터미널 코딩 비서.
- **[kimi-cli](https://github.com/sodam-ai/kimi-cli)** *(원본: [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli))* — 중국 문샷AI의 Kimi 모델을 쓰는 터미널 코딩 비서.
- **[grok-cli](https://github.com/sodam-ai/grok-cli)** *(원본: [superagent-ai/grok-cli](https://github.com/superagent-ai/grok-cli))* — 일론 머스크의 xAI가 만든 Grok AI를 쓰는 터미널 비서.

---

## 2. 개인용 AI 에이전트·채팅 작업공간 (6개)

개인 AI 비서나 채팅형 작업공간처럼 단독으로 실행해서 쓰는 에이전트·UI 프로그램입니다.

- **[hermes-agent](https://github.com/sodam-ai/hermes-agent)** *(원본: [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent))* — "쓸수록 나에게 맞춰 성장하는 AI 비서"를 표방하는 독립 AI 에이전트 프로그램.
- **[openclaw](https://github.com/sodam-ai/openclaw)** *(원본: [openclaw/openclaw](https://github.com/openclaw/openclaw))* — 윈도우·맥·리눅스 어디서나 쓸 수 있는 개인용 AI 비서 프로그램.
- **[open-webui](https://github.com/sodam-ai/open-webui)** *(원본: [open-webui/open-webui](https://github.com/open-webui/open-webui))* — 챗GPT처럼 예쁜 채팅 화면으로 여러 AI(Ollama, OpenAI 등)를 쓸 수 있게 해주는 웹 프로그램. 검은 터미널 화면이 아니라 보통 웹사이트 같은 채팅창입니다.
- **[OpenManus](https://github.com/sodam-ai/OpenManus)** *(원본: [FoundationAgents/OpenManus](https://github.com/FoundationAgents/OpenManus))* — 유료 AI 에이전트 서비스 "Manus"와 비슷한 기능을 누구나 무료로 쓸 수 있게 만들려는 오픈소스 프로젝트.
- **[OpenMinis](https://github.com/sodam-ai/OpenMinis)** *(원본: [OpenMinis/OpenMinis](https://github.com/OpenMinis/OpenMinis))* — 윈도우·맥 등 여러 기기에서 쓸 수 있는 무료 공개 AI 에이전트 앱.
- **[odysseus](https://github.com/sodam-ai/odysseus)** *(원본: [arcahyadi/odysseus](https://github.com/arcahyadi/odysseus))* — 내 컴퓨터(또는 개인 서버)에 직접 설치해서 쓰는 개인용 AI 업무 공간.

---

## 3. Claude Code 확장·설정·계정 관리 (13개)

Claude Code에 직접 기능을 더하거나 설정·플러그인·계정·작업 방식을 관리하는 도구입니다.

- **[Aurakit](https://github.com/sodam-ai/Aurakit)** *(원본: [smorky850612/Aurakit](https://github.com/smorky850612/Aurakit))* — claude-code에 33가지 작동 모드와 여러 겹의 보안 점검, 자동 실행 규칙 23개를 한 번에 넣어주는 종합 세트.
- **[bkit-claude-code](https://github.com/sodam-ai/bkit-claude-code)** *(원본: [ww-w-ai/bkit-claude-code](https://github.com/ww-w-ai/bkit-claude-code))* — "계획→실행→점검→개선"이라는 업무 방법론(PDCA)을 claude-code에 적용한 도구 모음.
- **[claude-code-harness](https://github.com/sodam-ai/claude-code-harness)** *(원본: [Chachamaru127/claude-code-harness](https://github.com/Chachamaru127/claude-code-harness))* — "계획→작업→검토"를 사람 손 없이 자동으로 반복시켜 결과물 품질을 높이는 claude-code 운영 도구.
- **[claude-config-editor](https://github.com/sodam-ai/claude-config-editor)** *(원본: [jung-wan-kim/claude-config-editor](https://github.com/jung-wan-kim/claude-config-editor))* — claude-code의 여러 설정(자동 규칙, 에이전트, 스킬)을 마우스로 끌어다 놓으며 쉽게 편집하는 화면 도구.
- **[claude-plugins-official](https://github.com/sodam-ai/claude-plugins-official)** *(원본: [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official))* — Anthropic이 직접 관리하는 "검증된 claude-code 부속 프로그램 모음 창고".
- **[claude-skills](https://github.com/sodam-ai/claude-skills)** *(원본: [dragon1086/claude-skills](https://github.com/dragon1086/claude-skills))* — claude-code를 잘 쓰는 사람들이 모아둔 유용한 스킬 모음.
- **[claude-swap](https://github.com/sodam-ai/claude-swap)** *(원본: [realiti4/claude-swap](https://github.com/realiti4/claude-swap))* — claude-code 계정을 여러 개 등록해두고, 사용량 제한에 걸리면 자동으로 다른 계정으로 바꿔주는 도구.
- **[everything-claude-code](https://github.com/sodam-ai/everything-claude-code)** *(원본: [affaan-m/ECC](https://github.com/affaan-m/ECC))* — claude-code, codex 등을 더 빠르고 저렴하며 똑똑하게 쓰게 해주는 "성능 최적화" 종합 도구.
- **[gstack](https://github.com/sodam-ai/gstack)** *(원본: [garrytan/gstack](https://github.com/garrytan/gstack))* — 위 gbrain을 만든 Garry Tan이 실제로 쓰는 claude-code 설정 23종(기획자·디자이너·QA 등 역할 부여).
- **[my-cc-harness](https://github.com/sodam-ai/my-cc-harness)** *(원본: [jh941213/my-cc-harness](https://github.com/jh941213/my-cc-harness))* — 어떤 개인 사용자가 자신의 claude-code 설정을 정리해둔 개인용 모음집.
- **[oh-my-claudecode](https://github.com/sodam-ai/oh-my-claudecode)** *(원본: [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode))* — claude-code에서 여러 AI 에이전트를 "팀"처럼 굴리는 것에 초점을 맞춘 확장 도구.
- **[teamclaude](https://github.com/sodam-ai/teamclaude)** *(원본: [jung-wan-kim/teamclaude](https://github.com/jung-wan-kim/teamclaude))* — claude 계정 여러 개를 등록해두고 사용량이 다 차면 자동으로 돌려쓰게 해주는 중계 서버.
- **[claude-code-tips](https://github.com/sodam-ai/claude-code-tips)** *(원본: [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips))* — Claude Code를 더 잘 쓰기 위한 45개 이상의 팁과 상태 표시줄 스크립트, 추가 스킬·플러그인 활용법을 모아둔 실전 가이드.

---

## 4. Codex 확장·플러그인·하네스 (6개)

OpenAI Codex의 작업 방식, 플러그인, 멀티에이전트 기능을 강화하는 도구입니다.

- **[FableCodex](https://github.com/sodam-ai/FableCodex)** *(원본: [baskduf/FableCodex](https://github.com/baskduf/FableCodex))* — 계획을 먼저 세우고 코드를 짜는 방식을 따르는 codex용 코딩 작업 흐름 도구.
- **[codex-fleet](https://github.com/sodam-ai/codex-fleet)** *(원본: [gongnyang/codex-fleet](https://github.com/gongnyang/codex-fleet))* — codex를 여러 개 동시에("함대처럼") 띄워서 작업을 병렬로 시키는 claude-code 스킬 모음.
- **[codex-plugin-cc](https://github.com/sodam-ai/codex-plugin-cc)** *(원본: [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc))* — claude-code를 쓰다가 코드 검토나 일부 작업을 codex에게 넘겨서 시킬 수 있게 해주는 연결 도구.
- **[gptaku-plugins-codex2](https://github.com/sodam-ai/gptaku-plugins-codex2)** *(원본: [fivetaku/gptaku-plugins-codex](https://github.com/fivetaku/gptaku-plugins-codex))* — codex 전용으로 만든 부속 프로그램 장터(마켓플레이스).
- **[lazycodex](https://github.com/sodam-ai/lazycodex)** *(원본: [code-yeongyu/lazycodex](https://github.com/code-yeongyu/lazycodex))* — codex 안에서 프로젝트 전체를 기억하고, 계획·실행·완료 검증까지 도와주는 하네스.
- **[oh-my-codex](https://github.com/sodam-ai/oh-my-codex)** *(원본: [Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex))* — codex에 자동 알림, 여러 에이전트 팀, 상태 표시(HUD) 등을 더해주는 확장 도구.

---

## 5. 공용 에이전트 스킬·플러그인·하네스 (16개)

Claude Code·Codex 등 여러 AI 코딩 도구에서 함께 활용할 수 있는 스킬·플러그인·하네스 모음입니다.

- **[WAY](https://github.com/sodam-ai/WAY)** *(원본: [Global-mindee/WAY](https://github.com/Global-mindee/WAY))* — "개발자가 아니어도 괜찮다"는 컨셉으로, 나를 학습해서 맞춰주는 개인용 AI 도구 모음.
- **[agent-harness](https://github.com/sodam-ai/agent-harness)** *(원본: [MattMagg/agent-harness](https://github.com/MattMagg/agent-harness))* — AI 코딩 작업을 안전하고 규칙적으로 시키기 위한 원칙·체크리스트 문서 모음.
- **[cowork-plugins](https://github.com/sodam-ai/cowork-plugins)** *(원본: [modu-ai/moai-cowork](https://github.com/modu-ai/moai-cowork))* — 마케팅·법률·회계·인사 등 업무용 전문 지식을 갖춘 AI 부속 프로그램 16종 모음(Claude Cowork용).
- **[garden-skills](https://github.com/sodam-ai/garden-skills)** *(원본: [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills))* — 웹 디자인, 자료 검색, 이미지 생성 등을 도와주는 claude-code 스킬 모음.
- **[gptaku_plugins](https://github.com/sodam-ai/gptaku_plugins)** *(원본: [fivetaku/gptaku_plugins](https://github.com/fivetaku/gptaku_plugins))* — "AI를 잘 쓰고 싶은 사람들"을 위한 claude-code 부속 프로그램 모음집.
- **[harness](https://github.com/sodam-ai/harness)** *(원본: [revfactory/harness](https://github.com/revfactory/harness))* — 어떤 분야든 그 분야 전용 "AI 팀"(여러 역할의 에이전트)을 자동으로 설계해주는 상위 도구.
- **[harness-100](https://github.com/sodam-ai/harness-100)** *(원본: [revfactory/harness-100](https://github.com/revfactory/harness-100))* — 위 harness로 미리 만들어 둔, 분야별(10개 분야) 완성형 AI 팀 100개 모음(한국어·영어 모두 제공).
- **[loop-engineering](https://github.com/sodam-ai/loop-engineering)** *(원본: [cobusgreyling/loop-engineering](https://github.com/cobusgreyling/loop-engineering))* — AI 에이전트에게 반복 작업을 시키는 노하우와 도구 모음.
- **[oh-my-opencode](https://github.com/sodam-ai/oh-my-opencode)** *(원본: [opensoft/oh-my-opencode](https://github.com/opensoft/oh-my-opencode))* — "OpenCode"라는 다른 AI 코딩 도구를 claude-code만큼 강력하게 만들어주는 확장 팩.
- **[ponytail](https://github.com/sodam-ai/ponytail)** *(원본: [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail))* — "코드는 안 쓸수록 좋다"는 마인드로, AI가 불필요한 코드를 안 만들게 유도하는 도구.
- **[skills](https://github.com/sodam-ai/skills)** *(원본: [mattpocock/skills](https://github.com/mattpocock/skills))* — 어느 개발자가 실제로 자기 claude-code 폴더에 쓰던 스킬들을 그대로 공개한 모음집.
- **[solaria](https://github.com/sodam-ai/solaria)** *(원본: [brad9432/solaria](https://github.com/brad9432/solaria))* — claude-code·codex 등 여러 AI 비서에서 "성격(페르소나)", "규칙(트리거)"을 공통으로 관리해주는 운영 계층.
- **[superpowers](https://github.com/sodam-ai/superpowers)** *(원본: [obra/superpowers](https://github.com/obra/superpowers))* — AI에게 "능력치(스킬)"를 단계적으로 붙여주는 프레임워크이자 개발 방법론. (이 대화 중 안내 문구로도 등장했던 도구입니다.)
- **[tofukyung-plugins](https://github.com/sodam-ai/tofukyung-plugins)** *(원본: [treylom/tofukyung-plugins](https://github.com/treylom/tofukyung-plugins))* — 프롬프트 작성법, 리서치, 지식 정리 등 12가지 claude-code·codex 부속 프로그램 장터.
- **[k-skill](https://github.com/sodam-ai/k-skill)** *(원본: [NomaDamas/k-skill](https://github.com/NomaDamas/k-skill))* — 한국 사용자를 위해 만든 에이전트 스킬 모음집. AI가 한국어·한국 환경에 더 맞게 작업하도록 돕는 부속 지식 세트입니다.
- **[agent-skills](https://github.com/sodam-ai/agent-skills)** *(원본: [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills))* — Claude Code·Codex·Cursor 등 AI 코딩 에이전트에서 재사용할 수 있도록 실무 수준의 엔지니어링 작업 지침을 모아둔 Agent Skills 모음.

---

## 6. AI 코딩 품질검증·자기개선·비용 최적화 (11개)

AI가 결과를 스스로 검증·개선하거나 토큰과 비용을 줄이도록 돕는 품질·최적화 도구입니다.

- **[autoresearch](https://github.com/sodam-ai/autoresearch)** *(원본: [karpathy/autoresearch](https://github.com/karpathy/autoresearch))* — 유명 AI 연구자 Karpathy가 만든 것으로, AI가 스스로 실험을 반복하며 더 나은 AI 학습 방법을 찾아가는 자동 연구 도구.
- **[autoresearch-builder](https://github.com/sodam-ai/autoresearch-builder)** *(원본: [jung-wan-kim/autoresearch-builder](https://github.com/jung-wan-kim/autoresearch-builder))* — 위 autoresearch 방식을 웹·앱·자바 등 어떤 프로젝트에도 쓸 수 있게 claude-code용으로 바꾼 버전.
- **[autoresearch-skill](https://github.com/sodam-ai/autoresearch-skill)** *(원본: [olelehmann1337/autoresearch-skill](https://github.com/olelehmann1337/autoresearch-skill))* — claude-code의 스킬(부속기능) 하나를 반복 실행·채점·수정해가며 자동으로 더 좋게 만들어주는 도구.
- **[fable-ish](https://github.com/sodam-ai/fable-ish)** *(원본: [chrisryugj/fable-ish](https://github.com/chrisryugj/fable-ish))* — "검증 안 됐으면 끝났다고 하지 마라" — 작업이 실제로 검증됐는지 스스로 확인하게 강제하는 claude-code용 장치.
- **[fablelayer](https://github.com/sodam-ai/fablelayer)** *(원본: [VoidLight00/fablelayer](https://github.com/VoidLight00/fablelayer))* — 위 fable-ish와 비슷하게, AI가 절차를 지켰는지·검증했는지 자동으로 채점하는 도구.
- **[fablize](https://github.com/sodam-ai/fablize)** *(원본: [fivetaku/fablize](https://github.com/fivetaku/fablize))* — AI 모델(Opus)이 "확실히 검증된 것만 완료라고 말하게" 행동을 바꿔주는 claude-code 부속 프로그램.
- **[hyper-waterfall](https://github.com/sodam-ai/hyper-waterfall)** *(원본: [postmelee/hyper-waterfall](https://github.com/postmelee/hyper-waterfall))* — AI와 함께 코딩할 때 "누가 뭘 승인했는지" 기록이 남는, 단계별 승인 절차 도구.
- **[rtk](https://github.com/sodam-ai/rtk)** *(원본: [rtk-ai/rtk](https://github.com/rtk-ai/rtk))* — 자주 쓰는 개발 명령을 중간에서 가로채, AI에게 보내는 사용량(토큰)을 60~90%까지 줄여주는 절약 도구.
- **[value-for-fable](https://github.com/sodam-ai/value-for-fable)** *(원본: [itsinseong/value-for-fable](https://github.com/itsinseong/value-for-fable))* — 비싼 고성능 AI만큼의 결과물을 더 저렴한 AI로 뽑아내려는 실험 프로젝트.
- **[vibe-sunsang](https://github.com/sodam-ai/vibe-sunsang)** *(원본: [fivetaku/vibe-sunsang](https://github.com/fivetaku/vibe-sunsang))* — 코딩 초보자(바이브 코더)의 claude-code 대화 기록을 분석해서 얼마나 성장했는지 알려주는 멘토형 AI.
- **[SkillOpt](https://github.com/sodam-ai/SkillOpt)** *(원본: [microsoft/SkillOpt](https://github.com/microsoft/SkillOpt))* — 마이크로소프트가 만든 도구로, AI 에이전트가 쓰는 "설명서(스킬 문서)"를 실제 사용 기록을 바탕으로 자동으로 더 정교하게 고쳐줍니다.

---

## 7. 멀티에이전트·오케스트레이션·에이전트 운영 (10개)

여러 AI 에이전트를 동시에 배치하고 역할을 나누거나 운영 상태를 관리하는 도구입니다.

- **[Agentlas-OS](https://github.com/sodam-ai/Agentlas-OS)** *(원본: [agentlas-ai/Agentlas-OS](https://github.com/agentlas-ai/Agentlas-OS))* — 전문 분야별 AI들을 한 곳에 모아두고, 일이 생기면 그때그때 임시 "팀장 AI"를 붙여 처리하는 시스템.
- **[agency-agents](https://github.com/sodam-ai/agency-agents)** *(원본: [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents))* — 프론트엔드 개발자, 커뮤니티 관리자 등 역할별로 성격이 다른 AI들을 모아놓은 "AI 대행사" 세트.
- **[agent-assemble](https://github.com/sodam-ai/agent-assemble)** *(원본: [rjrlwksp-droid/agent-assemble](https://github.com/rjrlwksp-droid/agent-assemble))* — MCP(AI 연결 규격)를 이용해 여러 AI를 계층적으로 조합해 쓸 수 있게 설정하는 도구.
- **[crewAI](https://github.com/sodam-ai/crewAI)** *(원본: [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI))* — 여러 AI에게 각자 역할(연구원, 작가 등)을 주고 한 팀처럼 협업시키는, 널리 쓰이는 오픈소스 AI 프레임워크.
- **[manager-orchestrator](https://github.com/sodam-ai/manager-orchestrator)** *(원본: [jung-wan-kim/manager-orchestrator](https://github.com/jung-wan-kim/manager-orchestrator))* — claude-code 안에서 여러 작업을 나눠 지휘하는 "관리자 AI" 역할 도구.
- **[paperclip](https://github.com/sodam-ai/paperclip)** *(원본: [paperclipai/paperclip](https://github.com/paperclipai/paperclip))* — 회사에서 여러 AI 에이전트를 직원처럼 관리할 때 쓰는 공개 프로그램.
- **[prime-agent](https://github.com/sodam-ai/prime-agent)** *(원본: [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent))* — 코딩 작업이나 오래 걸리는 작업을 하면서 스스로 개선해 나가는 실험적 AI 에이전트.
- **[openworker](https://github.com/sodam-ai/openworker)** *(원본: [andrewyng/openworker](https://github.com/andrewyng/openworker))* — 유명 AI 교육자 Andrew Ng이 공개한, 스스로 업데이트되는 베타 단계의 AI 업무 자동화 프로그램.
- **[herdr](https://github.com/sodam-ai/herdr)** *(원본: [herdrdev/herdr](https://github.com/herdrdev/herdr))* — 여러 코딩 에이전트가 실제 작업을 실행하고 살아갈 수 있는 "런타임(실행 환경)"을 제공하는 에이전트 운영 기반 도구.
- **[orca](https://github.com/sodam-ai/orca)** *(원본: [stablyai/orca](https://github.com/stablyai/orca))* — 여러 코딩 에이전트를 동시에 병렬로 띄우고 관리하기 위한 ADE(Agent Development Environment). 각 AI 서비스의 기존 구독을 활용해 데스크톱·모바일·VPS에서 에이전트 함대를 운영하는 것을 목표로 합니다.

---

## 8. AI 앱·워크플로우·에이전트 프레임워크 (7개)

AI 서비스와 복잡한 워크플로우를 개발·조립하기 위한 프레임워크와 플랫폼입니다.

- **[dify](https://github.com/sodam-ai/dify)** *(원본: [langgenius/dify](https://github.com/langgenius/dify))* — 코드를 거의 몰라도 AI 업무 자동화(워크플로우)를 화면에서 조립해 만들 수 있는 서비스형 플랫폼.
- **[langchain](https://github.com/sodam-ai/langchain)** *(원본: [langchain-ai/langchain](https://github.com/langchain-ai/langchain))* — 세계적으로 가장 널리 쓰이는 "AI 에이전트 제작 도구 모음" 중 하나.
- **[langent](https://github.com/sodam-ai/langent)** *(원본: [AlexAI-MCP/langent](https://github.com/AlexAI-MCP/langent))* — 데이터를 그래프로 시각화해주는 "Langent Nebula"라는 도구와 AI 에이전트 프레임워크.
- **[langflow](https://github.com/sodam-ai/langflow)** *(원본: [langflow-ai/langflow](https://github.com/langflow-ai/langflow))* — 위 langchain을 마우스로 블록 끼우듯 조립해서 AI 서비스를 만들 수 있게 해주는 화면 도구.
- **[langgraph](https://github.com/sodam-ai/langgraph)** *(원본: [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph))* — langchain 팀이 만든 것으로, 오류에 강하고 복잡한 절차도 안정적으로 처리하는 AI 에이전트를 만드는 도구.
- **[Revka](https://github.com/sodam-ai/Revka)** *(원본: [KumihoIO/Revka](https://github.com/KumihoIO/Revka))* — 대화 내용을 그래프 형태로 기억하는 AI 에이전트 실행 시스템(여러 프로그램 언어 조합으로 제작).
- **[semantica](https://github.com/sodam-ai/semantica)** *(원본: [semantica-agi/semantica](https://github.com/semantica-agi/semantica))* — AI가 상황(맥락)을 그래프 형태로 이해하고, 왜 그런 답을 냈는지 책임 추적이 가능하게 만드는 기반 기술.

---

## 9. AI 모델 게이트웨이·라우팅 (1개)

여러 AI 공급자와 모델을 하나의 연결점으로 묶고 자동 라우팅하는 도구입니다.

- **[OmniRoute](https://github.com/sodam-ai/OmniRoute)** *(원본: [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute))* — Claude Code·Codex·Cursor·OpenCode 등에서 여러 AI 공급자와 1,200개 이상의 모델을 하나의 연결점으로 사용할 수 있게 해주는 AI 게이트웨이. 사용량을 고려한 자동 대체와 토큰 절약 기능도 제공합니다.

---

## 10. AI 메모리·지식 그래프·컨텍스트 관리 (8개)

대화와 작업 기록을 오래 기억시키거나 자료의 관계를 지식 구조로 관리하는 도구입니다.

- **[claude-mem](https://github.com/sodam-ai/claude-mem)** *(원본: [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem))* — claude-code가 작업하면서 있었던 일을 요약해 저장해두고, 다음 대화(세션)를 시작할 때 그 기억을 다시 넣어주는 도구.
- **[agentmemory](https://github.com/sodam-ai/agentmemory)** *(원본: [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory))* — 여러 실험으로 성능이 검증된, AI 코딩 비서용 "장기 기억" 저장소.
- **[honcho](https://github.com/sodam-ai/honcho)** *(원본: [plastic-labs/honcho](https://github.com/plastic-labs/honcho))* — 상태(맥락)를 계속 유지하는 AI 에이전트를 만들 때 쓰는 기억 저장 부품(라이브러리).
- **[memory-bank](https://github.com/sodam-ai/memory-bank)** *(원본: [jung-wan-kim/memory-bank](https://github.com/jung-wan-kim/memory-bank))* — claude-code 대화 안에서 결정한 것, 선호하는 것 등을 자동으로 뽑아내 검색 가능하게 저장해두는 기억 도구.
- **[graphify](https://github.com/sodam-ai/graphify)** *(원본: [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify))* — 코드, 문서, 이미지 등 어떤 자료든 넣으면 서로 연결된 지식 지도로 만들어 검색할 수 있게 해주는 AI 도구.
- **[llm_wiki](https://github.com/sodam-ai/llm_wiki)** *(원본: [nashsu/llm_wiki](https://github.com/nashsu/llm_wiki))* — 내 문서들을 AI가 조금씩 읽어가며 서로 링크된 "위키백과"처럼 자동으로 만들어 쌓아주는 프로그램.
- **[knowledge-catalog](https://github.com/sodam-ai/knowledge-catalog)** *(원본: [GoogleCloudPlatform/knowledge-catalog](https://github.com/GoogleCloudPlatform/knowledge-catalog))* — 구글 클라우드에서 회사 자료를 정리·분류하는 데 쓰는 공식 도구와 예시 모음.
- **[knowledge-manager](https://github.com/sodam-ai/knowledge-manager)** *(원본: [treylom/knowledge-manager](https://github.com/treylom/knowledge-manager))* — 웹페이지·PDF·SNS 글을 자동으로 옵시디언(Obsidian)이나 노션(Notion) 같은 메모 프로그램에 정리해 넣어주는 AI 도구.

---

## 11. 검색·리서치·문서 이해·법률·공개 API (6개)

자료를 찾고 읽고 분석하거나 법률·공개 API처럼 특정 정보를 AI에서 활용하게 해주는 도구입니다.

- **[Docufinder](https://github.com/sodam-ai/Docufinder)** *(원본: [chrisryugj/Docufinder](https://github.com/chrisryugj/Docufinder))* — 한글 문서(HWPX), PDF, 오피스 파일 수천 개의 "내용"까지 1초 만에 찾아주는, 내 컴퓨터 안에서만 작동하는(완전 오프라인) 검색 프로그램.
- **[Understand-Anything](https://github.com/sodam-ai/Understand-Anything)** *(원본: [Egonex-AI/Understand-Anything](https://github.com/Egonex-AI/Understand-Anything))* — 아무 코드나 넣으면 그걸 눈으로 보고 질문할 수 있는 "지식 지도(그래프)"로 바꿔주는 도구.
- **[korean-law-mcp](https://github.com/sodam-ai/korean-law-mcp)** *(원본: [chrisryugj/korean-law-mcp](https://github.com/chrisryugj/korean-law-mcp))* — 대한민국 법제처의 법령·판례 정보를 AI가 바로 찾아볼 수 있게 연결해주는 도구.
- **[llama_index](https://github.com/sodam-ai/llama_index)** *(원본: [run-llama/llama_index](https://github.com/run-llama/llama_index))* — 내가 가진 문서를 AI가 읽고 답할 수 있게 만들어주는(문서 검색+글자 인식) 유명 오픈소스 도구.
- **[public-apis-4Kr](https://github.com/sodam-ai/public-apis-4Kr)** *(원본: [yybmion/public-apis-4Kr](https://github.com/yybmion/public-apis-4Kr))* — 한국에서 이용할 수 있는 공개 API들을 한곳에 모아 정리한 목록. 국내 서비스와 연결되는 API를 찾을 때 참고하는 자료 저장소입니다.
- **[insane-search](https://github.com/sodam-ai/insane-search)** *(원본: [fivetaku/insane-search](https://github.com/fivetaku/insane-search))* — claude-code가 막힌(차단된) 웹사이트에 접속해야 할 때, 별도의 접속 열쇠(API 키)를 발급받지 않고도 자동으로 우회를 시도해주는 도구.

---

## 12. 브라우저·컴퓨터 조작·웹 자동화 (7개)

AI가 브라우저나 컴퓨터 화면을 직접 조작하거나 웹 화면을 검사·복제하게 해주는 도구입니다.

- **[Wbrowser](https://github.com/sodam-ai/Wbrowser)** *(원본: [w-partners/Wbrowser](https://github.com/w-partners/Wbrowser))* — 내가 이미 로그인해 둔 크롬 브라우저를, 터미널이나 AI가 대신 조작(클릭·이동 등)하게 해주는 도구.
- **[ai-website-cloner-template](https://github.com/sodam-ai/ai-website-cloner-template)** *(원본: [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template))* — 명령 한 줄로 어떤 웹사이트든 그대로 베껴서 내 프로젝트로 만들어주는 AI 도구.
- **[antigravity-cli](https://github.com/sodam-ai/antigravity-cli)** *(원본: [professional-ALFIE/antigravity-ide-cli](https://github.com/professional-ALFIE/antigravity-ide-cli))* — "Antigravity"라는 코딩 프로그램(IDE)을 화면 없이 명령어로 원격 조작할 수 있게 해주는 도구.
- **[browser](https://github.com/sodam-ai/browser)** *(원본: [lightpanda-io/browser](https://github.com/lightpanda-io/browser))* — 사람이 보는 화면 없이("헤드리스") 아주 가볍고 빠르게 작동하도록 AI·자동화 전용으로 새로 만든 웹브라우저.
- **[cua](https://github.com/sodam-ai/cua)** *(원본: [trycua/cua](https://github.com/trycua/cua))* — 여러 운영체제에서 "컴퓨터를 대신 써주는 AI"를 훈련·평가하기 위한 공개 도구 모음.
- **[open-computer-use](https://github.com/sodam-ai/open-computer-use)** *(원본: [lineCode/open-computer-use](https://github.com/lineCode/open-computer-use))* — 컴퓨터 화면을 보고 마우스·키보드를 직접 조작해 업무를 처리하는 AI로, "OSWorld"라는 시험에서 82% 정답률을 낸 것으로 소개된 프로젝트.
- **[pokeit-extension](https://github.com/sodam-ai/pokeit-extension)** *(원본: [sejinxjung/pokeit-extension](https://github.com/sejinxjung/pokeit-extension))* — 웹사이트 화면에 이상한 부분(깨진 디자인 등)이 없는지 검사해주는 크롬 확장 프로그램.

---

## 13. 메신저·원격 제어·에이전트 통신 (11개)

텔레그램·디스코드·카카오톡 등에서 AI를 부르거나 에이전트끼리 메시지를 주고받게 하는 연결 도구입니다.

- **[agent-link-mcp](https://github.com/sodam-ai/agent-link-mcp)** *(원본: [mikusnuz/agent-link-mcp](https://github.com/mikusnuz/agent-link-mcp))* — 서로 다른 AI 프로그램들끼리 메시지를 주고받게 이어주는 MCP 연결 도구(5가지 기능 제공).
- **[buzz](https://github.com/sodam-ai/buzz)** *(원본: [block/buzz](https://github.com/block/buzz))* — 여러 사람(또는 여러 AI)이 마치 "한 벌집처럼" 소통하는 커뮤니케이션 플랫폼.
- **[cc-channel-mem](https://github.com/sodam-ai/cc-channel-mem)** *(원본: [AlexAI-MCP/cc-channel-mem](https://github.com/AlexAI-MCP/cc-channel-mem))* — 디스코드·텔레그램에서 claude-code와 나눈 대화를 기억해두는 상시 실행 프로그램.
- **[cc-telegram-bridge](https://github.com/sodam-ai/cc-telegram-bridge)** *(원본: [shacede/cc-telegram-bridge](https://github.com/shacede/cc-telegram-bridge))* — claude-code, codex 등을 텔레그램 채팅으로 그대로 옮겨와 쓸 수 있게 해주는 다리 프로그램(음성 입력도 지원).
- **[claude-code-discord-bridge](https://github.com/sodam-ai/claude-code-discord-bridge)** *(원본: [ebibibi/ebi-agent-chat-relay](https://github.com/ebibibi/ebi-agent-chat-relay))* — 디스코드 채팅방에서 claude-code에게 말을 걸고 답을 받을 수 있게 해주는 다리 프로그램.
- **[clawhip](https://github.com/sodam-ai/clawhip)** *(원본: [Yeachan-Heo/clawhip](https://github.com/Yeachan-Heo/clawhip))* — 여러 알림을 각 메신저 채널로 정리해서 보내주는 라우터(교통정리) 프로그램.
- **[cokacdir](https://github.com/sodam-ai/cokacdir)** *(원본: [kstost/cokacdir](https://github.com/kstost/cokacdir))* — 텔레그램 메시지 하나로 휴대폰에서도 AI가 코드를 실행하고 파일을 고치게 해주는 도구(터미널 파일 관리자 기능도 있음).
- **[hermes-CCC](https://github.com/sodam-ai/hermes-CCC)** *(원본: [AlexAI-MCP/hermes-CCC](https://github.com/AlexAI-MCP/hermes-CCC))* — hermes-agent를 claude-code의 "채널(대화창)" 기능으로 옮겨와 쓸 수 있게 만든 버전(로그인 절차 없이 46개 기능 내장).
- **[kakaocli](https://github.com/sodam-ai/kakaocli)** *(원본: [silver-flight-group/kakaocli](https://github.com/silver-flight-group/kakaocli))* — 카카오톡 메시지를 AI가 직접 읽고 보낼 수 있게 해주는 도구.
- **[openkakao-cli](https://github.com/sodam-ai/openkakao-cli)** *(원본: [JungHoonGhae/openkakao-cli](https://github.com/JungHoonGhae/openkakao-cli))* — 위와 비슷한 카카오톡 연결 도구지만, 제작자가 "더 이상 관리하지 않으며 최신 카카오톡에서는 로그인이 안 된다"고 직접 밝혀둔 상태입니다. ⚠️ 지금은 그대로 쓰기 어렵습니다.
- **[happy](https://github.com/sodam-ai/happy)** *(원본: [slopus/happy](https://github.com/slopus/happy))* — 휴대폰이나 웹 브라우저에서 codex·claude-code에 음성으로 말을 걸 수 있게 해주는 접속용 앱.

---

## 14. Hermes 생태계 보조도구·접속 환경 (5개)

Hermes Agent를 데스크톱·웹·CEO 콘솔 등 여러 방식으로 사용하거나 기능을 확장하는 도구입니다.

- **[gbrain](https://github.com/sodam-ai/gbrain)** *(원본: [garrytan/gbrain](https://github.com/garrytan/gbrain))* — 유명 스타트업 투자자 Garry Tan이 openclaw·hermes-agent용으로 만든 "AI 두뇌 설정".
- **[hermes-ceo-console-installer](https://github.com/sodam-ai/hermes-ceo-console-installer)** *(원본: [contentscoin/hermes-ceo-console-installer](https://github.com/contentscoin/hermes-ceo-console-installer))* — hermes-agent의 "CEO 콘솔"이라는 데스크톱 프로그램을 설치해주는 설치 도구.
- **[hermes-desktop](https://github.com/sodam-ai/hermes-desktop)** *(원본: [fathah/hermes-desktop](https://github.com/fathah/hermes-desktop))* — hermes-agent를 컴퓨터 바탕화면에서 쓸 수 있게 해주는 동반 프로그램.
- **[hermes-for-web](https://github.com/sodam-ai/hermes-for-web)** *(원본: [reallygood83/hermes-for-web](https://github.com/reallygood83/hermes-for-web))* — hermes-agent를 웹 브라우저에서 쓸 수 있게 만든 개인 맞춤 작업 공간.
- **[oh-my-hermes](https://github.com/sodam-ai/oh-my-hermes)** *(원본: [Salomondiei08/oh-my-hermes](https://github.com/Salomondiei08/oh-my-hermes))* — hermes-agent로 앱을 만들고 운영할 때 따르기 좋은 작업 방식(워크플로우) 모음.

---

## 15. 알림·HUD·작업 상태 모니터링 (3개)

AI 작업 완료 알림, 사용량, 비용, 진행률 같은 상태를 눈에 보이게 알려주는 도구입니다.

- **[claude-notifications-go](https://github.com/sodam-ai/claude-notifications-go)** *(원본: [777genius/claude-notifications-go](https://github.com/777genius/claude-notifications-go))* — claude-code 작업이 끝나면 컴퓨터 알림창, 슬랙, 텔레그램 등으로 "다 됐어요"라고 알려주는 알림 프로그램.
- **[claude-ultimate-hud](https://github.com/sodam-ai/claude-ultimate-hud)** *(원본: [hadamyeedady12-dev/claude-ultimate-hud](https://github.com/hadamyeedady12-dev/claude-ultimate-hud))* — 화면 맨 아래줄에 사용량 한도, 비용, 지금 하는 작업, 할 일 진행률을 한눈에 보여주는 표시줄.
- **[token-horse](https://github.com/sodam-ai/token-horse)** *(원본: [ratelworks/token-horse](https://github.com/ratelworks/token-horse))* — AI 사용량(토큰)에 따라 반응하는 작은 "말(horse)" 캐릭터를 상태 표시줄에 보여주는 재미용 도구.

---

## 16. UI·UX·웹 디자인·컴포넌트 (12개)

웹·앱 UI를 설계하고 디자인 품질을 높이거나 재사용 가능한 화면 부품을 제공하는 도구입니다.

- **[agents-UI-Design](https://github.com/sodam-ai/agents-UI-Design)** *(원본: [wshobson/agents](https://github.com/wshobson/agents))* — claude-code, codex, Cursor 등 여러 AI 코딩 비서에서 쓸 수 있는 부속 프로그램(플러그인) 장터. 원본 이름은 "agents"였는데, 포크하면서 "agents-UI-Design"으로 이름이 바뀌었습니다.
- **[StyleGallery](https://github.com/sodam-ai/StyleGallery)** *(원본: [changeroa/StyleGallery](https://github.com/changeroa/StyleGallery))* — 참고할 만한 디자인 스타일들을 모아 설명해 둔 모음집.
- **[awesome-claude-design](https://github.com/sodam-ai/awesome-claude-design)** *(원본: [VoltAgent/awesome-claude-design](https://github.com/VoltAgent/awesome-claude-design))* — claude-code로 화면(UI)을 만들 때 바로 갖다 쓸 수 있는 68가지 디자인 스타일 설명서 모음.
- **[awesome-design-md](https://github.com/sodam-ai/awesome-design-md)** *(원본: [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md))* — 유명 브랜드들의 디자인 방식을 정리한 문서 모음으로, 이 문서를 넣어주면 AI가 그 스타일에 맞는 화면을 만들어줍니다.
- **[design-diversity](https://github.com/sodam-ai/design-diversity)** *(원본: [epoko77-ai/design-diversity](https://github.com/epoko77-ai/design-diversity))* — AI가 만드는 결과물(발표자료·웹페이지)이 다 비슷비슷해지지 않도록, 여러 디자인 스타일 100가지를 모아둔 참고 목록.
- **[effective-html](https://github.com/sodam-ai/effective-html)** *(원본: [plannotator/effective-html](https://github.com/plannotator/effective-html))* — 뼈대 화면(와이어프레임), 시제품, 도표 등을 HTML로 뚝딱 만들어주는 AI 스킬 모음.
- **[hallmark](https://github.com/sodam-ai/hallmark)** *(원본: [Nutlope/hallmark](https://github.com/Nutlope/hallmark))* — AI가 만든 디자인이 흔히 티 나는 "AI스러운 느낌"이 나지 않도록 잡아주는 디자인 스킬.
- **[open-design](https://github.com/sodam-ai/open-design)** *(원본: [nexu-io/open-design](https://github.com/nexu-io/open-design))* — 내 컴퓨터에서 직접 돌아가는(클라우드 전송 없는) 무료 디자인 도구로, AI 코딩 비서를 디자인 엔진처럼 써서 시안·발표자료·영상까지 실제 파일로 뽑아줍니다.
- **[ui](https://github.com/sodam-ai/ui)** *(원본: [shadcn-ui/ui](https://github.com/shadcn-ui/ui))* — "shadcn/ui"라는 이름으로 널리 쓰이는, 버튼·입력창 같은 웹 화면 부품(컴포넌트)을 예쁘고 접근성 있게 미리 만들어둔 모음. 개발자가 복사해서 자기 웹사이트에 바로 갖다 쓰는 재료 상자입니다.
- **[ui-ux-pro-max-skill](https://github.com/sodam-ai/ui-ux-pro-max-skill)** *(원본: [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill))* — 웹사이트나 앱 화면(UI/UX)을 전문 디자이너 수준으로 만들 수 있게, AI에게 디자인 감각과 판단 기준을 넣어주는 스킬.
- **[threeui](https://github.com/sodam-ai/threeui)** *(원본: [MengTo/threeui](https://github.com/MengTo/threeui))* — 웹에서 바로 확인할 수 있는 인터랙티브 UI 컴포넌트와 전체 소스 코드를 모아둔 오픈소스 ThreeUI 커뮤니티 카탈로그.
- **[stitch-skills](https://github.com/sodam-ai/stitch-skills)** *(원본: [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills))* — Google의 Stitch MCP 서버와 함께 쓰도록 만든 Agent Skills 모음. Antigravity·Gemini CLI·Claude Code 등 여러 코딩 에이전트와 호환되는 공개 스킬 형식을 따릅니다.

---

## 17. 이미지·그래픽·폰트·로고·앱 스크린샷 (7개)

이미지 생성 보조, 폰트, 로고, 스프라이트, 앱스토어용 홍보 이미지 같은 그래픽 작업 도구입니다.

- **[comfyui-connection-helper](https://github.com/sodam-ai/comfyui-connection-helper)** *(원본: [ltdrdata/comfyui-connection-helper](https://github.com/ltdrdata/comfyui-connection-helper))* — AI 이미지 생성 프로그램 "ComfyUI"에서 여러 기능 상자(노드)를 선으로 연결할 때 도와주는 보조 도구.
- **[fontagent](https://github.com/sodam-ai/fontagent)** *(원본: [semoji-ai/fontagent](https://github.com/semoji-ai/fontagent))* — 원하는 분위기에 맞는 무료 글꼴(폰트)을 AI가 찾아서 설치해주고, 이미지 속 글자가 어떤 폰트인지도 알아내주는 도구.
- **[gongnyang-prompt-kit](https://github.com/sodam-ai/gongnyang-prompt-kit)** *(원본: [gongnyang/gongnyang-prompt-kit](https://github.com/gongnyang/gongnyang-prompt-kit))* — "이런 이미지 만들어줘" 같은 막연한 요청을, AI 이미지 생성기가 알아듣기 좋은 정교한 명령문으로 바꿔주는 도구.
- **[ip-as-logo-skill](https://github.com/sodam-ai/ip-as-logo-skill)** *(원본: [s1dashu/ip-as-logo-skill](https://github.com/s1dashu/ip-as-logo-skill))* — 심플하고 동글동글한 마스코트 캐릭터 로고를 만들어주는 AI 스킬.
- **[perfectpixel-studio](https://github.com/sodam-ai/perfectpixel-studio)** *(원본: [gykim80/perfectpixel-studio](https://github.com/gykim80/perfectpixel-studio))* — 글로 설명만 하면 게임 캐릭터가 8방향으로 움직이는 동작 그림(스프라이트)을 자동으로 만들어주는 도구.
- **[store-screenshots](https://github.com/sodam-ai/store-screenshots)** *(원본: [LeeHueeng/store-screenshots](https://github.com/LeeHueeng/store-screenshots))* — 앱의 원본 스크린샷을 앱스토어·구글플레이에 올릴 수 있는 마케팅 이미지로 바꿔주는 Claude Code·Codex용 AI 에이전트 스킬. 다양한 스마트폰·태블릿 기기 프레임을 지원합니다.
- **[watermarks-remover](https://github.com/sodam-ai/watermarks-remover)** *(원본: [guillaumemeyer/watermarks-remover](https://github.com/guillaumemeyer/watermarks-remover))* — 사용자가 소유한 콘텐츠에서 AI 워터마크를 제거하도록 만든 개인정보 보호 중심 앱. 저작권이나 이용약관을 지킬 수 있는 자기 소유 콘텐츠에 사용하는 것이 전제입니다.

---

## 18. 프레젠테이션·차트·다이어그램 (6개)

발표자료, 차트, 도식, 슬라이드를 만들고 편집·발표하는 데 특화된 도구입니다.

- **[PPTAgent](https://github.com/sodam-ai/PPTAgent)** *(원본: [icip-cas/PPTAgent](https://github.com/icip-cas/PPTAgent))* — 자료를 넣으면 AI가 스스로 검토해가며 파워포인트를 만들어주는 도구.
- **[deck-factory](https://github.com/sodam-ai/deck-factory)** *(원본: [gongnyang/deck-factory](https://github.com/gongnyang/deck-factory))* — 하고 싶은 말 한 줄만 입력하면, 발표자료 수준의 세련된 HTML 슬라이드를 만들어주는 claude-code 스킬.
- **[gongnangi-chart-skill](https://github.com/sodam-ai/gongnangi-chart-skill)** *(원본: [gongnyang/gongnangi-chart-skill](https://github.com/gongnyang/gongnangi-chart-skill))* — 컨설팅 회사(맥킨지 스타일)처럼 보이는 세련된 차트를 HTML로 만들어 이미지 파일로 내보내는 claude-code 스킬.
- **[html-slide-remote](https://github.com/sodam-ai/html-slide-remote)** *(원본: [truth0530/html-slide-remote](https://github.com/truth0530/html-slide-remote))* — 컴퓨터엔 청중이 볼 발표 화면을, 내 휴대폰엔 나만 보는 발표자 메모·리모컨을 띄워주는 발표 보조 도구.
- **[slides-grab](https://github.com/sodam-ai/slides-grab)** *(원본: [NomaDamas/slides-grab](https://github.com/NomaDamas/slides-grab))* — claude-code나 codex로 발표 슬라이드를 만들고, 편집하고, 오류까지 검사해주는 종합 도구.
- **[diagram-design](https://github.com/sodam-ai/diagram-design)** *(원본: [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design))* — Claude Code·Codex 등에서 편집용 다이어그램을 만들 때 참고할 수 있는 38가지 도식 디자인 유형 모음. HTML+SVG 방식으로 직접 그리는 구조입니다.

---

## 19. 영상·화면 녹화·모션·애니메이션 (9개)

영상 생성·편집, 화면 녹화, HTML 영상화, Lottie 애니메이션 같은 움직이는 콘텐츠 제작 도구입니다.

- **[OpenCut](https://github.com/sodam-ai/OpenCut)** *(원본: [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut))* — 유료 영상 편집 앱 "캡컷(CapCut)"을 대신할 수 있는 무료 오픈소스 영상 편집기.
- **[Recordly](https://github.com/sodam-ai/Recordly)** *(원본: [webadderallorg/Recordly](https://github.com/webadderallorg/Recordly))* — 편집 실력이 없어도 그럴듯한 데모 영상을 만들 수 있는 화면 녹화 프로그램(윈도우·맥·리눅스 지원).
- **[WinStudio](https://github.com/sodam-ai/WinStudio)** *(원본: [PromSereyreaksa/WinStudio](https://github.com/PromSereyreaksa/WinStudio))* — 윈도우 화면이나 창을 녹화하면 자동으로 확대(줌) 효과까지 넣어 데모 영상으로 만들어주는 프로그램.
- **[auto_kairos](https://github.com/sodam-ai/auto_kairos)** *(원본: [semoji-ai/auto_kairos](https://github.com/semoji-ai/auto_kairos))* — 주제 하나만 입력하면 자료 조사, 대본, 장면 구성, 음성(TTS), 이미지, 자막, 최종 영상까지 전부 자동으로 만들어주는 AI 영상 제작 파이프라인.
- **[claude-video](https://github.com/sodam-ai/claude-video)** *(원본: [bradautomates/claude-video](https://github.com/bradautomates/claude-video))* — claude-code에게 "이 영상 봐줘" 명령을 주면, 영상을 내려받아 장면을 뽑고 대사까지 글로 옮겨 전달해주는 도구.
- **[hyperframes](https://github.com/sodam-ai/hyperframes)** *(원본: [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes))* — HTML로 화면을 만들면 그걸 그대로 영상으로 바꿔주는, AI 전용으로 설계된 도구.
- **[lottie](https://github.com/sodam-ai/lottie)** *(원본: [diffusionstudio/lottie](https://github.com/diffusionstudio/lottie))* — 웹·앱에서 자주 쓰는 가벼운 애니메이션 파일(Lottie)을 claude-code나 codex로 바로 만들어주는 도구.
- **[video-use](https://github.com/sodam-ai/video-use)** *(원본: [browser-use/video-use](https://github.com/browser-use/video-use))* — AI 코딩 비서에게 영상 편집(자르기·합치기 등)을 직접 시킬 수 있게 해주는 도구.
- **[reelforge](https://github.com/sodam-ai/reelforge)** *(원본: [gongnyang/reelforge](https://github.com/gongnyang/reelforge))* — 간단한 브리프 하나에서 내레이션·자막·장면 편집이 가능한 숏폼/롱폼 영상을 만드는 AI 영상 제작 파이프라인. 한국어 우선 설계와 HTML 기반 렌더링을 내세웁니다.

---

## 20. 문서·오피스·기획서·전자책 제작 (3개)

워드·엑셀·파워포인트, PRD, 전자책처럼 업무·출판 문서를 만드는 데 쓰는 도구입니다.

- **[OfficeCLI](https://github.com/sodam-ai/OfficeCLI)** *(원본: [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI))* — 마이크로소프트 오피스(워드·엑셀·파워포인트)를 설치하지 않고도, AI가 그 파일들을 읽고 고칠 수 있게 해주는 프로그램.
- **[bookforge](https://github.com/sodam-ai/bookforge)** *(원본: [gongnyang/bookforge](https://github.com/gongnyang/bookforge))* — 주제 한 줄만 주면 상업용 전자책 수준의 한국어 PDF를 만들도록 돕는 Claude Code·Codex 겸용 에이전트 스킬. 여러 스타일 팩과 배치 규칙, 품질 점검 단계를 포함합니다.
- **[show-me-the-prd](https://github.com/sodam-ai/show-me-the-prd)** *(원본: [fivetaku/show-me-the-prd](https://github.com/fivetaku/show-me-the-prd))* — "이런 거 만들고 싶어" 한 문장만 말하면, AI가 질문을 던지며 기획 문서 4종을 완성해주는 도구.

---

## 21. 파일 변환·OCR·CAD·PDF 처리 (4개)

문서·도면 파일의 형식을 바꾸거나 글자를 인식하고 PDF를 압축하는 파일 처리 도구입니다.

- **[DWG-to-DXF-Converter](https://github.com/sodam-ai/DWG-to-DXF-Converter)** *(원본: [zheimr/DWG-to-DXF-Converter](https://github.com/zheimr/DWG-to-DXF-Converter))* — 캐드(AutoCAD) 설계 파일(DWG)을 다른 파일 형식(DXF)으로 바꿔주는 프로그램. 여러 개를 한 번에 바꾸는 기능도 있습니다.
- **[PDF-Compressor](https://github.com/sodam-ai/PDF-Compressor)** *(원본: [Cyapstaye/PDF-Compressor](https://github.com/Cyapstaye/PDF-Compressor))* — 화질은 최대한 유지하면서 PDF(포트폴리오 등) 파일 용량을 줄여주는 도구.
- **[Unlimited-OCR](https://github.com/sodam-ai/Unlimited-OCR)** *(원본: [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR))* — 중국 검색기업 바이두가 공개한, 사진이나 문서 속 글자를 아주 길게(대용량으로) 읽어내는 문자 인식(OCR) 기술.
- **[kordoc](https://github.com/sodam-ai/kordoc)** *(원본: [chrisryugj/kordoc](https://github.com/chrisryugj/kordoc))* — 한글 프로그램 파일(HWP 등), PDF, 엑셀, 워드 파일을 전부 마크다운(글자 문서) 형식으로 바꿔주는 도구. 예전 문서와 비교하거나 서식을 자동으로 채우는 기능도 있습니다.

---

## 22. 한국어 글쓰기·문체·콘텐츠 품질 (2개)

AI가 작성한 한국어를 더 자연스럽고 사람다운 문체로 다듬는 데 특화된 도구입니다.

- **[gn-voice](https://github.com/sodam-ai/gn-voice)** *(원본: [gongnyang/gn-voice](https://github.com/gongnyang/gn-voice))* — AI가 쓴 어색한 한국어 초안을 내 말투처럼 자연스럽게 다시 써주는 claude-code 스킬.
- **[im-not-ai](https://github.com/sodam-ai/im-not-ai)** *(원본: [epoko77-ai/im-not-ai](https://github.com/epoko77-ai/im-not-ai))* — AI가 쓴 티가 나는 한국어를 찾아내고, 번역투·기계적인 반복 표현 등을 사람 글처럼 자연스럽게 다듬어주는 Claude 스킬.

---

## 23. SEO·콘텐츠 마케팅·SNS 자동화 (3개)

검색 노출을 분석·개선하거나 SNS 콘텐츠 제작·게시를 자동화하는 도구입니다.

- **[claude-seo](https://github.com/sodam-ai/claude-seo)** *(원본: [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo))* — 기술 SEO, E-E-A-T, Schema, GEO/AEO, 백링크, 로컬 SEO, 의미 기반 키워드 묶기 등 SEO 작업을 Claude Code에 맡길 수 있게 하는 종합 SEO 스킬 세트.
- **[open-seo](https://github.com/sodam-ai/open-seo)** *(원본: [every-app/open-seo](https://github.com/every-app/open-seo))* — Semrush·Ahrefs 같은 상용 SEO 분석 서비스를 대체하는 것을 목표로 하는 오픈소스 SEO 도구.
- **[autoTHREADS](https://github.com/sodam-ai/autoTHREADS)** *(원본: [eisenjimmy/autoTHREADS](https://github.com/eisenjimmy/autoTHREADS))* — SNS "Threads"에 올릴 글을 AI가 초안부터 자동 게시까지 대신 해주는 자동화 도구.

---

## 24. 투자·금융·시장 정보·뉴스레터 자동화 (3개)

투자·증권·시장 정보 조회와 뉴스레터·보고서 자동화에 관련된 도구입니다.

- **[Vibe-Trading](https://github.com/sodam-ai/Vibe-Trading)** *(원본: [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading))* — "나만의 개인 트레이딩 비서"를 표방하는 AI 자동매매 실험 프로젝트.
- **[newsletter-automation](https://github.com/sodam-ai/newsletter-automation)** *(원본: [rjrlwksp-droid/newsletter-automation](https://github.com/rjrlwksp-droid/newsletter-automation))* — 한국어 뉴스레터, 시장 동향 요약, 주간 PDF 보고서, 기업 공시(DART) 감시까지 자동으로 만들어주는 도구.
- **[tossinvest-cli](https://github.com/sodam-ai/tossinvest-cli)** *(원본: [JungHoonGhae/tossinvest-cli](https://github.com/JungHoonGhae/tossinvest-cli))* — 토스증권 계좌 정보를 AI나 터미널에서 조회·주문할 수 있게 만든 "비공식" 도구입니다(토스에서 공식 지원하는 프로그램이 아니라는 점에 유의하세요).

---

## 25. 보안·권한·의존성 안전 점검 (3개)

보안 취약점, 접근 권한, 새 라이브러리의 위험성을 점검하는 안전 도구입니다.

- **[KESE-KIT](https://github.com/sodam-ai/KESE-KIT)** *(원본: [cdppcorp/KESE-KIT](https://github.com/cdppcorp/KESE-KIT))* — 국가 주요 정보통신 기반시설의 보안 취약점을 점검하는 공식 가이드를 바탕으로 만든 claude-code 스킬.
- **[kube-rebac-authorizer](https://github.com/sodam-ai/kube-rebac-authorizer)** *(원본: [luxas/kube-rebac-authorizer](https://github.com/luxas/kube-rebac-authorizer))* — 서버 여러 대를 관리하는 "쿠버네티스"라는 시스템에서, 누가 무엇에 접근할 수 있는지 더 정교하게 통제하는 보안 도구.
- **[safedeps](https://github.com/sodam-ai/safedeps)** *(원본: [aldegad/safedeps](https://github.com/aldegad/safedeps))* — AI가 새 부품(라이브러리)을 설치하려 할 때 위험한 부품인지 먼저 검사하고, 문제 있으면 되돌려주는 안전장치.

---

## 26. 터미널·쉘·AI 도구 전환·개발 작업환경 (7개)

터미널 창 관리, 셸 작업, 여러 AI 코딩 도구 전환, 개발용 글꼴 등 작업 환경을 편하게 만드는 도구입니다.

- **[otty](https://github.com/sodam-ai/otty)** *(원본: [otty-shell/otty](https://github.com/otty-shell/otty))* — 개발·운영 작업을 위한 터미널 중심의 작업 공간 프로그램.
- **[tmux](https://github.com/sodam-ai/tmux)** *(원본: [tmux/tmux](https://github.com/tmux/tmux))* — 터미널 화면 하나를 여러 칸으로 쪼개고, 창을 닫아도 작업이 계속 돌아가게 해주는 아주 오래되고 유명한 원조 프로그램.
- **[wmux](https://github.com/sodam-ai/wmux)** *(원본: [amirlehmam/wmux](https://github.com/amirlehmam/wmux))* — 위 tmux와 비슷한 기능을, 윈도우에서 AI 에이전트가 쓰기 좋게 새로 만든 버전.
- **[ghostty](https://github.com/sodam-ai/ghostty)** *(원본: [ghostty-org/ghostty](https://github.com/ghostty-org/ghostty))* — 빠른 속도와 GPU 가속, 운영체제 기본 UI를 활용하는 크로스플랫폼 터미널 에뮬레이터. AI 전용 도구는 아니지만 개발·에이전트 작업용 터미널로 활용할 수 있습니다.
- **[cc-switch](https://github.com/sodam-ai/cc-switch)** *(원본: [farion1231/cc-switch](https://github.com/farion1231/cc-switch))* — claude-code, codex 등 여러 AI 코딩 비서를 한 화면에서 골라 쓸 수 있게 해주는 마우스용 데스크톱 프로그램.
- **[cc-switch-cli](https://github.com/sodam-ai/cc-switch-cli)** *(원본: [SaladDay/cc-switch-cli](https://github.com/SaladDay/cc-switch-cli))* — 위 cc-switch의 터미널(글자 명령) 버전.
- **[yeomil-mono](https://github.com/sodam-ai/yeomil-mono)** *(원본: [taevel02/yeomil-mono](https://github.com/taevel02/yeomil-mono))* — 한글과 영어 모두 반듯하게 줄이 맞는, 개발자용 화면(터미널·코드 편집기) 전용 글꼴.

---

## 27. AI 연구·모델 성능·실험적 기반기술 (6개)

AI 모델의 추론·연산 성능이나 새로운 에이전트 구조를 시험하는 연구·실험 성격의 프로젝트입니다.

- **[HRM](https://github.com/sodam-ai/HRM)** *(원본: [sapientinc/HRM](https://github.com/sapientinc/HRM))* — "계층적 추론 모델"이라는 AI 연구 성과를 공개한 것으로, AI가 문제를 큰 단계→작은 단계로 나눠 생각하게 만드는 실험적 AI 모델.
- **[OpenAI-Plugins](https://github.com/sodam-ai/OpenAI-Plugins)** *(원본: [openai/plugins](https://github.com/openai/plugins))* — 예전에 챗GPT에 외부 기능을 연결하던 "플러그인" 방식의 공식 예시 코드 모음입니다(지금은 잘 쓰이지 않는 옛 방식입니다).
- **[OpenCrab](https://github.com/sodam-ai/OpenCrab)** *(원본: [AlexAI-MCP/OpenCrab](https://github.com/AlexAI-MCP/OpenCrab))* — AI 환경을 "온톨로지"(개념들을 체계적으로 정리한 지도) 구조로 만들려는 실험적인 MCP 부속 프로그램.
- **[OpenOyster](https://github.com/sodam-ai/OpenOyster)** *(원본: [Pandoll-AI/OpenOyster](https://github.com/Pandoll-AI/OpenOyster))* — 신호를 감지하고 → 가설을 세우고 → 행동한다는 흐름을 계속 유지하는 실험적인 AI 실행 엔진.
- **[flash-attention](https://github.com/sodam-ai/flash-attention)** *(원본: [kingbri1/flash-attention](https://github.com/kingbri1/flash-attention))* — AI 모델이 계산할 때 메모리를 아끼면서 더 빠르게 돌아가게 해주는, 개발자용 핵심 기술 부품(라이브러리).
- **[gajae-code](https://github.com/sodam-ai/gajae-code)** *(원본: [Yeachan-Heo/gajae-code](https://github.com/Yeachan-Heo/gajae-code))* — 아직 초기 시작 단계(MVP)인 것으로 보이는 코딩 관련 실험 프로젝트.

---

## 28. 생활·교육·개발자 행사·기타 유틸리티 (6개)

위 전문 분야에 속하지 않는 생활·교육·개발자 정보·윈도우 편의 도구입니다.

- **[Dev-Event](https://github.com/sodam-ai/Dev-Event)** *(원본: [brave-people/Dev-Event](https://github.com/brave-people/Dev-Event))* — 개발자를 위한 웨비나, 컨퍼런스, 해커톤 같은 행사 소식을 모아 알려주는 저장소.
- **[ExplorerPatcher](https://github.com/sodam-ai/ExplorerPatcher)** *(원본: [valinet/ExplorerPatcher](https://github.com/valinet/ExplorerPatcher))* — 윈도우 화면(작업표시줄 등)을 예전 방식으로 되돌리거나 더 편하게 고쳐주는 프로그램입니다(AI와는 무관한, 윈도우 꾸미기 도구입니다).
- **[gjdong](https://github.com/sodam-ai/gjdong)** *(원본: [cameleonh/gjdong](https://github.com/cameleonh/gjdong))* — 뒤죽박죽인 한국 주소 표기를 표준 형식으로 깔끔하게 정리해주는 도구.
- **[marktext](https://github.com/sodam-ai/marktext)** *(원본: [marktext/marktext](https://github.com/marktext/marktext))* — 윈도우·맥·리눅스에서 쓸 수 있는, 화면 그대로 보며 글을 쓰는 간단하고 깔끔한 마크다운 글쓰기 프로그램입니다(AI 기능은 없는 순수 글쓰기 편집기입니다).
- **[meetup-spots](https://github.com/sodam-ai/meetup-spots)** *(원본: [infinite-loop-lab/meetup-spots](https://github.com/infinite-loop-lab/meetup-spots))* — 스터디나 코딩 모임을 할 때 가기 좋은 장소를 추천받는(또는 추천하는) 저장소.
- **[partner-surprise-codex-skillset](https://github.com/sodam-ai/partner-surprise-codex-skillset)** *(원본: [Pandoll-AI/partner-surprise-codex-skillset](https://github.com/Pandoll-AI/partner-surprise-codex-skillset))* — 연인이나 배우자에게 깜짝 이벤트를 준비할 때 아이디어를 도와주는 codex용 스킬 모음.

---

## 참고 사항

- 이 문서는 **2026-09-11 기준**  [https://github.com/sodam-ai](https://github.com/sodam-AI?tab=repositories) 의 현재 공개 포크를 기준으로 다시 정리한 스냅샷입니다. 이후 포크를 추가·삭제하면 개수와 목록은 달라질 수 있습니다.
- 설명은 기존 문서에 정리된 GitHub 공개 요약·README 기반 쉬운 설명을 최대한 유지했고, 이번에 새로 확인된 `OmniRoute`, `agent-skills`는 현재 GitHub 저장소 메타데이터를 바탕으로 같은 형식의 쉬운 설명을 추가했습니다.
- 한 저장소가 여러 용도로 쓰일 수 있어도 **가장 대표적인 주된 목적 하나**를 기준으로 한 카테고리에만 배치했습니다. 그래서 전체 개수와 카테고리 합계가 정확히 일치합니다.
- 별표(⭐, star) 개수는 이번 정리에서 다루지 않았습니다.
