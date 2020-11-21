---
layout: page
title: "Personal Team Project Process Report"
date: 2020-11-21
excerpt: "Report of team project process"
tags: [report, team project, process, personal]
comments: true
---


##11/20 첫번째 미팅

* 시간 : AM 10:00 ~ PM 12:00
* 장소 : 산학협력관 러닝팩토리
* 미팅 주제 : 미팅 계획 수립, Litiengine 정보 공유, 활동 방향 설정, 활동 계획 수립

* 세부 내용

Litiengine은 게임 제작 툴을 제공하는 것이기 때문에 처음 사전조사때 생각했던 게임을 만들어 시각적으로 변화가 확실한 개발의 형태가 아니었다. 때문에 이 전 미팅때 논의했던 방향과는 다른 방향으로의 개발을 계획 후 진행해야했다. 이로 인해 미팅 전 조사했던 내용을 사용해 추가적인 조사와 논의가 이루어졌다.

Litiengine 프로그램을 다운로드받으려면 2가지 개발환경 중 하나를 선택해야한다. 하나는 Window이고, 다른 하나는 UNIX기반 OS인 MAC과 Linux였다. 결국 Litiengine을 파악하기 위해서는 두 가지의 OS를 모두 사용할 수 있었어야했는데  팀원들 대부분 Window OS를 사용하였지만 임소연 팀원은 Mac OS를 사용해 Window와 UNIX 두 환경 모두 사용할 수 있었다.

Litiengine 파악을 위한 환경이 갖춰진 것을 확인한 뒤 Litiengine의 사용자들이 가장 원하는 issue가 무엇인지 확인하기위해 Litiengine의 issue를 확인했다. issue 중 가장 눈에 띄는 것은 초보 개발자가 사용하기에 접근성이 떨어진다는 것이었다. 그 이유는 자세한 tutorial의 부재였다. Litiengine에서도 이를 인지하고 있어 tutorial의 contributor를 구하고 있었고, 학부생이면서 오픈 소스 초보 개발자인 팀원들이 가장 공감할 수 있는 issue이기도 했다. 팀원들의 논의를 통해 Litiengine을 사용하려는 초보 개발자들을 위한 tutorial을 작성해 Litiengine에 merge를 요청하는 방식으로 활동하기로 결정했다.

Litiening tutorial을 만들기 위해서 가장 먼저 확인해야할 것은 **현재 제공되고 있는 tutorial과 document는 어느 정도의 수준으로 작성되어 있는가**였다. 이를 확인해본 결과 tutorial은 introduction 수준의 내용만 제공하고 있었으며 document의 경우 타 오픈소스들의 document와 유사하게 오픈 소스를 사용해본 경력이 있는 개발자들의 수준에 맞는 진입장벽이 높은 document만을 제공했다. 팀원들은 이를 보고 Litiengine가 오픈 소스의 취지에 맞게 많은 사람들이 쉽게 접근하게 하려면 tutorial과 document가 가장 필요하다는 것을 확인할 수 있었다.

Tutorial과 document를 확인한 뒤 실질적은 역할분담과 앞으로의 대략적 계획을 세웠다. Litiengine은 GUI환경으로 게임의 map을 제작하면서 Litiengine이 제공하는 여러가지 Engine API를 관리할 수 있도록 utiLITI를 제공한다. 이는 게임 개발자들이 직접적으로 사용하는 IDE에 해당하고 이는 frontend의 역할을 한다. 또한 Litiengine은 게임이 실질적으로 작동하는 메커니즘을 게임 개발자들이 구현할 수 있도록 Engine API를 제공하는데 이는 backend의 역할을 한다. 따라서 팀원들은 frontend와 backend로 나뉘어 활동을 진행하는 것으로 역할을 분담했다. 이 중 내가 맡은 부분은 frontend로 frontend를 사용하는 방법에 대한 tutorial과 document를 작성하는 역할을 맡게 되었다.

Tutorial과 document의 전체 내용 중 60% 이상을 작성하게 되면 그 이후로 매주 Litiengine측에 merge를 요청하여 우리 팀이 작성한 tutorial과 document를 사용하도록 요청할 예정이며, 이를 위해 각 팀원들은 Litiengine의 사용법에 대해 숙지를 우선적으로 진행할 예정이다.
