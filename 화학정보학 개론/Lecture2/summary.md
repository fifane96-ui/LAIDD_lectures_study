1. Target Identification
Bioactive compound의 molecular target 예측
이 물질(보통 단백질)을 건들이면 질병이 낫는다. 에서 이 물질을 찾는 과정
내가 할 수 있는 건 knowledge graph 기반으로 target identification하기 정도

3. Target validation

찾아낸 위에서의 이 물질이 정말로 병을 낫게 하는지/병과 관련있는지 확인하는 과정
① 인과성: 이 target을 건드리면 병이 정말 바뀌나?
② 방향과 크기: 켜야 하나 꺼야 하나? 몇 % 억제해야 효과가 나나?
③ 안전성: 껐을 때 다른 데가 망가지지 않나?

이 세가지가 확인되어야 한다.

축 2: 무슨 도구로 건드리나
                유전자 | 화합물 | 항체 | 올리고
              ┌───────┼───────┼──────┼──────┐
축 1   in silico │       │       │      │      │
검증의  in vitro  │   ●   │   ●   │  ●   │  ●   │
수준   in vivo   │   ●   │   ●   │  ●   │  ●   │
      clinical  │       │       │      │      │
              └───────┴───────┴──────┴──────┘

- target druggability: Likelihood of being able to modulate a target with a small molecule drug
Target validation이 "건드리면 병이 낫는가"였다면, druggability는 "애초에 건드릴 수 있는가"입니다. 순서상 validation과 병렬로 봅니다.

용어	뜻	기준
Ligandability	뭐라도 붙기는 하나?	화합물이 결합하기만 하면 OK
Druggability	약다운 분자가 붙어서 기능을 바꾸나?	결합 + 약물성 + 효과
Tractability	어떤 방식으로든 접근 가능한가?	저분자, 항체, ASO 전부 포함


5. Lead Discovery & Optimization
-structure based virtual screening
-ligand based virtual screening

6. Preclinical testing
- ADMET
- PBPK simulation
