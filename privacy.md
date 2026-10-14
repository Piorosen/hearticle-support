---
title: 개인정보 처리방침 · Privacy Policy
permalink: /privacy/
---

# 논문밀당(Hearticle) 개인정보 처리방침

_최종 수정: 2026-10-14_

논문밀당(영어 이름 Hearticle)은 **차주형(JooHyoung Cha)**이 만든 iPhone 앱입니다.
이 방침에 대한 문의: [GitHub 이슈](https://github.com/Piorosen/hearticle-support/issues)

## 요약

논문밀당에는 회원 가입, 분석 도구, 광고, 추적이 없습니다.
개발자는 앱을 위한 서버를 운영하지 않으며, 여러분의 기록이나 사용 정보를 받지 않습니다.

## 기기 안에만 저장되는 정보

- **스와이프 기록**: 관심 표시하거나 넘긴 논문과, 추천에 쓰는 그 논문의 임베딩(숫자 벡터)
- **저장한 논문**과 직접 적은 **관심 주제**
- **취향 정보**: 고른 분야, 기록에서 계산한 취향 벡터, 받아 둔 논문 목록, AI가 붙인 주제 이름

이 정보는 앱 안에만 저장되고, 앱을 지우면 함께 지워집니다. 설정 › 취향 학습 초기화로 취향 정보를 지울 수 있습니다.

## 기기 안에서 하는 처리

- 취향 학습과 추천, 관심 주제 묶기, 키워드 추출은 iPhone 안에서 계산합니다.
- AI 요약, 주제 이름 붙이기, 관심 주제를 검색어로 바꾸기는 Apple Intelligence의 **기기 안 모델**로 처리합니다.
  Private Cloud Compute는 쓰지 않습니다.
- 초록 번역은 Apple의 기기 안 번역 기능을 씁니다. 처음 번역할 때 iOS가 번역 언어를 내려받을 수 있습니다.

## 앱 밖으로 나가는 요청

논문 정보를 받기 위해 앱은 **arXiv**(arxiv.org, export.arxiv.org, oaipmh.arxiv.org)에 요청을 보냅니다.
요청에는 고른 분야와, 주제로 찾을 때는 그 검색어(영어 키워드)가 들어갑니다.
다른 웹 요청과 마찬가지로 arXiv는 여러분의 IP 주소를 받으며, arXiv의 개인정보 처리방침이 적용됩니다.
논문 페이지나 PDF를 열면 arXiv 페이지를 앱 안의 브라우저로 불러옵니다.

이 밖에 개발자나 제3자에게 보내는 정보는 없습니다.

## 어린이

이 앱은 어린이를 대상으로 하지 않으며, 누구의 개인정보도 수집하지 않습니다.

## 바뀌는 경우

방침이 바뀌면 이 페이지와 위의 최종 수정일을 고칩니다.

---

# Hearticle Privacy Policy

_Last updated: 2026-10-14_

Hearticle (논문밀당) is an iPhone app by **JooHyoung Cha**.
It has no accounts, analytics, advertising or tracking. The developer runs no servers for the app and receives none of your data.

- **Stored only on your device:** your swipe history (papers you liked or passed, with their embeddings), saved papers, topics you type, your chosen fields and preference profile, cached paper lists and AI-generated topic names. Deleting the app deletes them.
- **Processed on your device:** recommendations, topic grouping and keyword extraction; summaries, topic names and search-term conversion use Apple Intelligence's on-device model (not Private Cloud Compute); translation uses Apple's on-device translation.
- **Sent off the device:** requests to arXiv (arxiv.org, export.arxiv.org, oaipmh.arxiv.org) for paper information, containing your chosen fields and, when you search a topic, its English search terms. arXiv receives your IP address as with any web request; arXiv's privacy policy applies. Nothing is sent to the developer or other third parties.

Questions: [GitHub issues](https://github.com/Piorosen/hearticle-support/issues).
