---

copyright:
  years: 2016

---
<!-- Copyright info at top of file: REQUIRED
    The copyright info is YAML content that must occur at the top of the MD file, before attributes are listed.
    It must be surrounded by 3 dashes.
    The value "years" can contain just one year or a two years separated by a comma. (years: 2014, 2016)
    Indentation as per the previous template must be preserved.
-->

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# 파이프라인 관리
{: #deliverypipeline_managing}
마지막 업데이트 날짜: 2016년 11월 17일
{: .last-updated}

IBM&reg; Bluemix&reg; {{site.data.keyword.deliverypipeline}} 통합을 관리, 구성 및 확장할 수 있습니다.
{:shortdesc}

파이프라인을 관리, 구성 및 확장하려면 다음 태스크를 완료하십시오. 

## 환경 특성 및 리소스
{: #deliverypipeline_envprop}

환경 특성 및 사전 설치된 리소스를 사용하여 {{site.data.keyword.deliverypipeline}} 서비스와 상호작용할 수 있습니다. 예를 들어, 이들을 작업 스크립트 또는 테스트 명령에 통합할 수 있습니다. 자세한 정보는 [{{site.data.keyword.deliverypipeline}} 서비스의 환경 특성 및 리소스](./deploy_var.html)를 참조하십시오. 

해당 **환경 특성** 탭에서 단계에 고유의 환경 특성을 추가할 수 있습니다. 단계의 모든 작업에서 환경 특성을 사용할 수 있습니다. 

환경 특성 탭에서 다음 네 가지 유형의 특성을 추가할 수 있습니다. 
* **텍스트**: 단일 행 값을 갖는 특성 키입니다. 
* **텍스트 영역**: 다중 행 값을 갖는 특성 키입니다. 
* **소스**: 단일 행 값을 갖는 특성 키입니다. 이 값은 별표로 표시됩니다. 
* **특성**: 프로젝트의 저장소에 있는 파일입니다. 이 파일에는 여러 특성이 포함될 수 있습니다. 각 특성은 자체 고유의 행에 위치해야 합니다. 키-값 쌍을 구분하려면 등호 부호(=)를 사용하십시오. 

## 파이프라인의 기능 확장
{: #deliverypipeline_extend}

지원되는 서비스를 사용하도록 작업을 구성하여 파이프라인의 기능을 확장할 수 있습니다. 예를 들어, 테스트 작업은 정적 코드 스캔을 실행할 수 있고 빌드 작업은 문자열을 글로벌화할 수 있습니다. 

파이프라인 기능 확장에 대한 자세한 정보는 [{{site.data.keyword.deliverypipeline}} 서비스의 기능 확장](./deliverypipeline_extension.html)을 참조하십시오. 

