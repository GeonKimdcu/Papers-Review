# TextRank: Bringing Order into Texts

| Writers | Journal/Conference | Year |
|---------|--------------------|------|
| **Rada Mihalcea and Paul Tarau** | EMNLP | 2004 |

### Abstarct
본 논문에서는 **TextRank** 개념을 소개한다. TextRank는 텍스트 처리를 위한 그래프 기반의 ranking model이다. 특히, 본 논문에서는 키워드와 문장 추출을 위한 두 가지 혁신적인 비지도 학습 방법을 제안하며, 이전에 발표된 연구 결과와 벤치마크를 통해 비교했을 때, 더 나은 성능을 보여주었다.

### 1. Introduction
**Kleinberg's HITS algorithm (Kleinberg, 1999)**이나 **Google's PageRank (Brin and Page, 1998)**와 같은 그래프 기반의 ranking algorithms은 인용구 분석, 소셜 네트워크, 그리고 World Wide Web의 연결 구조 분석에 성공적으로 사용되어 왔다. 논쟁의 여지 없이, 이러한 알고리즘은
