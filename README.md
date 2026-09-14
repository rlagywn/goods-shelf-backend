# Goods Shelf Backend

굿즈 진열장 앱의 백엔드 API 서버.

## 개요

앨범, 포토카드, 피규어 등 수집품을 가상 진열장 슬롯에 등록·배치하는 iOS 앱 및 웹(Next.js) 클라이언트를 위한 REST API. 인증, 진열장/슬롯/굿즈 영속화, 미디어 업로드(presigned URL)를 담당한다.

## 문서

- [백엔드 설계 스펙](../docs/superpowers/specs/2026-09-10-goods-display-case-backend-design.md)
- [iOS 앱 설계 스펙](../docs/superpowers/specs/2026-09-10-goods-display-case-app-design.md)
- API 명세서: Notion (https://app.notion.com/p/API-3da7491eeb2081cb86c6d28a48886c59)

## 기술 스택

Spring Boot 3.x (Java) · Spring Security + JWT · Spring Data JPA + Hibernate · PostgreSQL · Flyway · S3 호환 오브젝트 스토리지 (presigned URL 업로드) · JUnit5 + Testcontainers

## 상태

설계 완료, 구현 시작 전.
