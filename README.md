# 주석 다는 방법 (JSDoc 방식)

1. 컴포넌트를 만든다
2. 컴포넌트에 사용할 파라미터를 만든다
3. 해당 컴포넌트 위에 /\*\* \*/ 주석을 만들면 자동으로 데이터 타입과 설명을 채우라고 나온다
4. 컴포넌트를 만든 의도가 잘 담기게 설명을 작성해 주시면 됩니다!

_예시_

/\*\*  
 \* 버튼 컴포넌트 입니다  
 \* @param label - 버튼에 표시할 텍스트  
 \* @param onClick - 클릭 이벤트 핸들러  
 \* @param disabled - 비활성화 여부  
 \*/  
const Button = ({ label, onClick, disabled }) => (  
\<button onClick={onClick} disabled={disabled}>  
{label}  
\</button>  
);

# 테일윈드CSS
