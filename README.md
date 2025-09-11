# 주석 다는 방법 (JSDoc 방식)

1. 컴포넌트를 만든다
2. 컴포넌트에 사용할 파라미터를 만든다
3. 해당 컴포넌트 위에 /\*\* \*/ 주석을 만들고 엔터 한번 누르면 자동으로 빈줄, @param {\*} param0 이런 주석이 생성
4. 빈줄에 컴포넌트를 만든 의도가 잘 담기게 설명을 작성
5. { } 안에 데이터 타입, param0 -> 속성 이름으로 바꿔준다

_예시_

/\*\*  
 \* 버튼 컴포넌트 입니다  
 \* @param {string} label - 버튼에 표시할 텍스트  
 \* @param {function} onClick - 클릭 이벤트 핸들러  
 \* @param {boolean} disabled - 비활성화 여부  
 \*/  
const Button = ({ label, onClick, disabled }) => (  
\<button onClick={onClick} disabled={disabled}>  
{label}  
\</button>  
);

# 테일윈드CSS
