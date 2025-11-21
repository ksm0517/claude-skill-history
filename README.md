# claude-skill-history
클로드 skills를 통해 사업계획서 pptx를 만들기 위해 시도해본 것들의
history가 담긴 자료


## history
### 템플릿
- jihye_company_ppt_example.pptx: AI에게 해당 ppt 템플릿을 참고하여 작업하게 명령
### ppt
- 사업계획서_v1.pptx: skill 2nd 
  - 레이아웃이 입력해둔 템플릿과 다름.
- 사업계획서_v2.pptx: skill 2nd + 피드백
  - 레이아웃이 다소 개선되었으나 SWOT 등의 내용이 빠지기도 했으며, 전반적인 내용의 개선이 필요
  - 프롬프트에 skills가 아웃풋 자료임을 명시하지 않았더니 skill을 바로 생성하지 않고 해당 pptx를 바로 생성
- 사업계획서_v3.pptx: skill 3rd
  - 레이아웃이 약간 깨진 감이 있으나 내용적으론 충분해진 것을 확인
- 사업계획서_v4.pptx: skill 4th?
  - 4번 째 스킬 생성시 발생
- 사업계획서_v5.pptx: skill 5th
  - 스킬 등록시 에러가 해결된 상태로 업로드 한 skill
  - 거의 이전 결과물과 비슷하게 유지되는 것을 확인(조금 더 나아짐)


### skill
- jihye-brand-guideline-1st.skill: 용량 제한 오버로 사용 불가
- jihye-brand-guideline-2nd.skill: 용량을 줄인 상태로 다시 만들어 달라고 요청
- jihye-brand-guideline-3rd.zip: 아래 명령어를 사용하여 제작된 skill </br> <img width="660" height="632" alt="image" src="https://github.com/user-attachments/assets/a376e864-2358-413c-89da-f05560fc77b8" />
- jihye-brand-guideline-4th.zip: 아래 명령어를 사용하여 제작된 skill </br> <img width="679" height="339" alt="image" src="https://github.com/user-attachments/assets/3e4aa1eb-eb29-4f79-a322-3259aa5e404d" />
  - 업로드시 "unexpected key in SKILL.md frontmatter: properties must be in ('name', 'description', 'license', 'allowed-tools', 'metadata')" 에러 발생
- jihye-brand-guideline-5th.zip: 아래 명령어로 해결 </br> <img width="675" height="142" alt="image" src="https://github.com/user-attachments/assets/731b3d0e-eb8e-4234-86b8-0f78c8c4f4bb" />
