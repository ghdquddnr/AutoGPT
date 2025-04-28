# AutoGPT: AI 에이전트 구축, 배포 및 실행

[![Discord Follow](https://dcbadge.vercel.app/api/server/autogpt?style=flat)](https://discord.gg/autogpt) &ensp;
[![Twitter Follow](https://img.shields.io/twitter/follow/Auto_GPT?style=social)](https://twitter.com/Auto_GPT) &ensp;
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**AutoGPT**는 복잡한 워크플로우를 자동화하는 연속 AI 에이전트를 생성, 배포 및 관리할 수 있는 강력한 플랫폼입니다. 

## 호스팅 옵션 
   - 자체 호스팅을 위한 다운로드
   - 클라우드 호스팅 베타 버전을 위한 [대기자 명단 참여](https://bit.ly/3ZDijAI)

## 자체 호스팅 설정 방법
> [!NOTE]
> AutoGPT 플랫폼을 직접 설정하고 호스팅하는 것은 기술적인 과정입니다. 
> 바로 작동하는 것을 원하신다면, 클라우드 호스팅 베타 버전의 [대기자 명단에 참여](https://bit.ly/3ZDijAI)하는 것을 추천드립니다.

### Updated Setup Instructions:
완전히 유지보수되고 정기적으로 업데이트되는 문서 사이트로 이동했습니다.

👉 [공식 자체 호스팅 가이드를 여기서 확인하세요](https://docs.agpt.co/platform/getting-started/)


이 튜토리얼은 Docker, VSCode, git 및 npm이 설치되어 있다고 가정합니다.

### 🧱 AutoGPT Frontend

AutoGPT 프론트엔드는 사용자가 우리의 강력한 AI 자동화 플랫폼과 상호작용하는 곳입니다. AI 에이전트를 활용하고 참여할 수 있는 여러 방법을 제공합니다. 이 인터페이스에서 AI 자동화 아이디어를 실현할 수 있습니다:

   **에이전트 빌더:** 커스터마이징을 원하는 사용자를 위한 직관적인 로우코드 인터페이스로 자체 AI 에이전트를 설계하고 구성할 수 있습니다. 
   
   **워크플로우 관리:** 자동화 워크플로우를 쉽게 구축, 수정 및 최적화할 수 있습니다. 각 블록이 단일 작업을 수행하는 블록을 연결하여 에이전트를 구축합니다.
   
   **배포 제어:** 테스트부터 프로덕션까지 에이전트의 수명 주기를 관리합니다.
   
   **즉시 사용 가능한 에이전트:** 직접 구축하고 싶지 않으신가요? 사전 구성된 에이전트 라이브러리에서 선택하여 즉시 사용할 수 있습니다.
   
   **에이전트 상호작용:** 자체 구축한 에이전트든 사전 구성된 에이전트든, 사용자 친화적인 인터페이스를 통해 쉽게 실행하고 상호작용할 수 있습니다.

   **모니터링 및 분석:** 에이전트의 성능을 추적하고 자동화 프로세스를 지속적으로 개선하기 위한 인사이트를 얻을 수 있습니다.

[이 가이드](https://docs.agpt.co/platform/new_blocks/)를 읽고 자체 커스텀 블록을 구축하는 방법을 알아보세요.

### 💽 AutoGPT Server

AutoGPT 서버는 우리 플랫폼의 핵심입니다. 여기서 에이전트가 실행됩니다. 배포되면 에이전트는 외부 소스에 의해 트리거될 수 있으며 지속적으로 작동할 수 있습니다. AutoGPT가 원활하게 실행되도록 하는 모든 필수 구성 요소를 포함하고 있습니다.

   **소스 코드:** 에이전트와 자동화 프로세스를 구동하는 핵심 로직입니다.
   
   **인프라:** 안정적이고 확장 가능한 성능을 보장하는 견고한 시스템입니다.
   
   **마켓플레이스:** 다양한 사전 구축된 에이전트를 찾고 배포할 수 있는 종합적인 마켓플레이스입니다.

### 🐙 예제 에이전트

AutoGPT로 할 수 있는 두 가지 예시를 소개합니다:

1. **트렌딩 토픽에서 바이럴 비디오 생성**
   - 이 에이전트는 Reddit의 토픽을 읽습니다.
   - 트렌딩 토픽을 식별합니다.
   - 그런 다음 콘텐츠를 기반으로 자동으로 숏폼 비디오를 생성합니다.

2. **소셜 미디어용 비디오에서 최고의 인용구 식별**
   - 이 에이전트는 귀하의 YouTube 채널을 구독합니다.
   - 새 비디오가 게시되면 자동으로 전사합니다.
   - AI를 사용하여 가장 영향력 있는 인용구를 식별하여 요약을 생성합니다.
   - 그런 다음 소셜 미디어에 자동으로 게시할 포스트를 작성합니다.

이러한 예시는 AutoGPT로 달성할 수 있는 것의 일부일 뿐입니다! 어떤 사용 사례든 맞춤형 워크플로우를 만들어 에이전트를 구축할 수 있습니다.

---
### 미션과 라이선스
우리의 미션은 귀하가 중요한 것에 집중할 수 있도록 도구를 제공하는 것입니다:

- 🏗️ **구축** - 놀라운 것의 기반을 마련합니다.
- 🧪 **테스트** - 에이전트를 완벽하게 조정합니다.
- 🤝 **위임** - AI가 귀하를 위해 일하게 하고, 귀하의 아이디어를 실현하게 합니다.

혁명의 일부가 되세요! **AutoGPT**는 AI 혁신의 최전선에서 계속해서 존재할 것입니다.

**📖 [문서](https://docs.agpt.co)**
&ensp;|&ensp;
**🚀 [기여하기](CONTRIBUTING.md)**

**라이선스:**

MIT 라이선스: AutoGPT 저장소의 대부분은 MIT 라이선스 하에 있습니다.

Polyform Shield 라이선스: 이 라이선스는 autogpt_platform 폴더에 적용됩니다.

자세한 정보는 https://agpt.co/blog/introducing-the-autogpt-platform 을 참조하세요.

---
## 🤖 AutoGPT 클래식
> 아래는 AutoGPT의 클래식 버전에 대한 정보입니다.

**🛠️ [자체 에이전트 구축하기 - 빠른 시작](classic/FORGE-QUICKSTART.md)**

### 🏗️ Forge

**자체 에이전트를 구축하세요!** &ndash; Forge는 자체 에이전트 애플리케이션을 구축하기 위한 즉시 사용 가능한 도구 키트입니다. 대부분의 보일러플레이트 코드를 처리하여 *귀하의* 에이전트를 차별화하는 것에 모든 창의성을 집중할 수 있게 합니다. 모든 튜토리얼은 [여기](https://medium.com/@aiedge/autogpt-forge-e3de53cc58ec)에 있습니다. [`forge`](/classic/forge/)의 구성 요소는 개별적으로 사용하여 에이전트 프로젝트의 개발 속도를 높이고 보일러플레이트를 줄일 수 있습니다.

🚀 [**Forge로 시작하기**](https://github.com/Significant-Gravitas/AutoGPT/blob/master/classic/forge/tutorials/001_getting_started.md) &ndash;
이 가이드는 자체 에이전트를 생성하고 벤치마크 및 사용자 인터페이스를 사용하는 과정을 안내합니다.

📘 [자세히 알아보기](https://github.com/Significant-Gravitas/AutoGPT/tree/master/classic/forge) Forge에 대해

### 🎯 벤치마크

**에이전트의 성능을 측정하세요!** `agbenchmark`는 에이전트 프로토콜을 지원하는 모든 에이전트와 함께 사용할 수 있으며, 프로젝트의 [CLI]와의 통합으로 AutoGPT 및 forge 기반 에이전트와 함께 사용하기가 더욱 쉬워졌습니다. 벤치마크는 엄격한 테스트 환경을 제공합니다. 우리의 프레임워크는 자율적이고 객관적인 성능 평가를 가능하게 하여 에이전트가 실제 환경에서 준비되도록 합니다.

<!-- TODO: 벤치마크를 보여주는 시각적 자료 삽입 -->

📦 [`agbenchmark`](https://pypi.org/project/agbenchmark/) PyPI에서
&ensp;|&ensp;
📘 [자세히 알아보기](https://github.com/Significant-Gravitas/AutoGPT/tree/master/classic/benchmark) 벤치마크에 대해

### 💻 UI

**에이전트 사용을 쉽게 만듭니다!** `frontend`는 에이전트를 제어하고 모니터링할 수 있는 사용자 친화적인 인터페이스를 제공합니다. [에이전트 프로토콜](#-에이전트-프로토콜)을 통해 에이전트에 연결되어 우리 생태계 내외부의 많은 에이전트와의 호환성을 보장합니다.

<!-- TODO: 프론트엔드 스크린샷 삽입 -->

프론트엔드는 저장소의 모든 에이전트와 즉시 작동합니다. [CLI]를 사용하여 원하는 에이전트를 실행하세요!

📘 [자세히 알아보기](https://github.com/Significant-Gravitas/AutoGPT/tree/master/classic/frontend) 프론트엔드에 대해

### ⌨️ CLI

[CLI]: #-cli

저장소에서 제공하는 모든 도구를 가능한 한 쉽게 사용할 수 있도록 저장소 루트에 CLI가 포함되어 있습니다:

```shell
$ ./run
Usage: cli.py [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  agent      에이전트 생성, 시작 및 중지 명령
  benchmark  벤치마크 시작 및 테스트 및 카테고리 목록 명령
  setup      시스템에 필요한 종속성 설치
```

저장소를 클론하고 `./run setup`으로 종속성을 설치하면 바로 시작할 수 있습니다!

## 🤔 질문이 있으신가요? 문제가 있으신가요? 제안이 있으신가요?

### 도움 받기 - [Discord 💬](https://discord.gg/autogpt)

[![Discord에 참여하세요](https://invidget.switchblade.xyz/autogpt)](https://discord.gg/autogpt)

버그를 보고하거나 기능을 요청하려면 [GitHub Issue](https://github.com/Significant-Gravitas/AutoGPT/issues/new/choose)를 생성하세요. 동일한 주제에 대해 다른 사람이 이슈를 생성하지 않았는지 확인해 주세요.

## 🤝 자매 프로젝트

### 🔄 에이전트 프로토콜

현재 및 미래의 많은 애플리케이션과의 원활한 호환성을 보장하기 위해 AutoGPT는 AI Engineer Foundation의 [에이전트 프로토콜](https://agentprotocol.ai/) 표준을 사용합니다. 이는 에이전트에서 프론트엔드 및 벤치마크로의 통신 경로를 표준화합니다.

---

## 스타 통계

<p align="center">
<a href="https://star-history.com/#Significant-Gravitas/AutoGPT">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Significant-Gravitas/AutoGPT&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Significant-Gravitas/AutoGPT&type=Date" />
    <img alt="스타 히스토리 차트" src="https://api.star-history.com/svg?repos=Significant-Gravitas/AutoGPT&type=Date" />
  </picture>
</a>
</p>

## ⚡ 기여자

<a href="https://github.com/Significant-Gravitas/AutoGPT/graphs/contributors" alt="기여자 보기">
  <img src="https://contrib.rocks/image?repo=Significant-Gravitas/AutoGPT&max=1000&columns=10" alt="기여자" />
</a>
