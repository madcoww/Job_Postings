# BigData_Final

> 이력서, 구인 공고, 지원 이력 데이터 등을 바탕으로 구인 공고 추천 알고리즘 개발

* DACON 제 1회 국민대학교 AI빅데이터 분석 경진대회 데이터 활용
* 데이터 설명 [링크](https://docs.google.com/spreadsheets/d/1rNQuOmfj3YWESN6ryAYsek9ukh8Jth9D/edit#gid=1276570507)
* 그 외 데이터 분석을 통한 시각화

## Project Progress

데이터 전처리 &rarr; 데이터 분석 &rarr; 결과 도출 / 시각화 / 데이터 스토리텔링

## Data Set

> 실제 이용한 데이터만 기술

|resume(이력서)|설명| 
|------|---|
|resume_seq|이력서번호|
|reg_date|이력서등록일|
|degree|최종학력|
|graduate_date|졸업년도|
|hope_salary|희망연봉|
|job_code_seq1|희망직무1|
|career_month|경력월|
|career_job_code|경력직무|

|recruitment(구인공고)|설명| 
|------|---|
|recruitment_seq|공고번호|
|address_seq1|근무지주소코드1|
|check_box_keyword|모집직무코드|
|education|요구학위|
|major_task|주업무코드|
|qualifications|자격요건난이도|
|text_keyword|모집직무키워드|

|company(회사)|설명| 
|------|---|
|recruitment_seq|공고번호|
|employee|종업원수|

|apply_train(지원이력)|설명| 
|------|---|
|resume_seq|이력서번호|
|recruitment_seq|공고번호|

## Data Preprocessing

