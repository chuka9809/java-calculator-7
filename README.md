#java-calculator-precourse

구현 기능 목록

#### 1. 구분자와 숫자를 포함한 문자열 입력받기

    > camp.nextstep.edu.missionutils.Console의 readLine()을 활용

#### 2. 입력받은 문자열이 공백인 경우 0반환

#### 3. 문자열 앞부분 확인하여 //인 경우 커스텀 구분자 메소드 실행

#### 4. 커스텀 구분자 메소드

    > 커스텀 구분자를 추출, 입력받은 문자열에서 커스텀 구분자 부분을 제거 후 둘 다 반환

#### 5. 입력받은 문자열에서 구분자를 기준으로 숫자를 추출

#### 6. 추출한 결과를 정수형 리스트로 변환

#### 7. 변환 과정에서 입력 값 오류 시 : IllegalArgumentException 오류 발생 시키기

    > 음수이거나 숫자가 아닌 경우

#### 8. 정수형 리스트 숫자 합 계산

#### 9. 결과 값 출력

커스텀 구분자 종류 처리 해야 할 것

1. [o] ## 문자 1개일 경우 ex) &

2. [o] ## 문자 여러개일 경우 ex) &%

3. [o] ## 같은 문자 여러개일 경우 ex) %%

4. [x] ## ~~숫자일 경우 ex) 3~~  구분자가 숫자이면 기준이 모호해짐

5. [o] ## 메타문자일 경우 ex) [^


