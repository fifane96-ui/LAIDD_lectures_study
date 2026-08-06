MD simulation

analytical하게 분자 시스템에서 입자의 속도와 위치를 출 수 없으므로
시뮬레이션으로 간다.

많이 쓰이는 분자에대해 force field는 잘되어있지만 
ligand는 종류가 너무 많아 그러지 못하고 있다.

-solvents(주변 입자, 물..)
explicit하게 기술할 수도 있지만 계산량이 많고 정확하다 
implicit한 모델로 근사해 계산량을 줄이고 덜 정확하게 갈 수 있다.

-고전역학 기반 MD의 한계점
1) force field가 가진 시스템적 에러(fixed atomic charges, fixed molecular structures->화학반응 고려x)
2) limited sampling -> 계산을 많이 해야한다.

-conformation selection and MD simulation
protein ligand docking/virtual screening에 사용

Binding affinity calculation
