# Tongdoc

## Tongdoc
### Tongdoc
#### Tongdoc




## 2021.12.21 댓글에 댓글쓰기

댓글 리스트 배열을

(1)1번째 댓글 <br>
 ㄴ (2) 1번째 댓글의 1번째 대댓글<br>
&nbsp;  ㄴ (4) 1번째 댓글의 1번째 댓글의 대댓글<br>
 ㄴ (5) 1번째 댓글의 2번째 대댓글<br>
(3)2번째 댓글<br>
(6)3번째 댓글<br>

을 배열해주는 데이터베이스 조건문이 필요함
 - ORDER BY if(ISNULL(comment_parent_no), comment_no, comment_parent_no), depth 
 - : 부모댓글이 null이면, 댓글순으로 정렬, null이 아니면 부모댓글 출력 이후 depth순으로 정렬

<br>
## 2021.12.22 스크립트를 활용과 ajax

스크립트 사용법
fun
