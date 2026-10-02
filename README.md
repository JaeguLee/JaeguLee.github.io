# Jaegu Lee

기계공학 엔지니어. 진동과 댐퍼를 다루고, 수치해석과 시험 데이터 분석을 한다.

요즘은 AI 코딩 에이전트(Claude Code, Codex)로 공학 계산을 하면서, 그 결과를 사람이 확인할 수 있게 만드는 작업 방식을 다듬고 있다.

## 하는 일

**수치해석**
- 고점도 유체 속에서 진동하는 피스톤 댐퍼를 FEM으로 푼다. 축대칭 Stokes에서 시작해 전단 담화 점성(Carreau–Yasuda), 비정상 해석, 자유표면(ALE)까지 한 단계씩 쌓고 있다.
- 같은 문제를 PINN으로도 풀어 FEM 결과와 비교한다.
- Gmsh, scikit-fem, CalculiX 같은 오픈소스 도구를 엮어 2D·3D 해석을 돌려 보는 개인 학습용 파이프라인을 만들고 있다.

**시험 데이터 분석**
- 댐퍼 정현파 가진 시험에서 이력 곡선을 그리고, 감쇠계수와 등가강성을 뽑는다.

## 쓰는 도구

Python (NumPy, SciPy, scikit-fem, PyTorch) · Gmsh · CalculiX · Claude Code · Codex CLI · Obsidian · Git

## 예전 작업

- 2D 비정형 bin packing (2019–2022)
