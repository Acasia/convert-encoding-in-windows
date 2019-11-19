# convert-encoding-on-windows

국민대학교 과제 정보검색과 데이터 마이닝 수업중, encoding문제가 발생하여 이를 해결하려함.

문제 : windows에서 encoding한 cp949의 파일이 mac에서 압축풀기와 읽을 수 없어 변환하는 과정이 필요했음.

1. 파일이름에 띄어쓰기와 한자, 특수문자등을 제거하기 위해 순서대로 index.txt로 변경.
2. 파일 encoding을 cp949 -> utf-8로 변경
