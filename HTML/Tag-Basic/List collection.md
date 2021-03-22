# 목록을 표현하는 목록
## 순서가 중요한 목록
  - ol 태그
    ```html
    <ol>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ol>
    ```
## 순서가 중요하지 않은 목록
  - ul 태그
    ```html
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    ```
### HTML5에서 목록 기호는 type속성을 궝장하지 않고 CSS속성을 권장한다.
  - 목록 중첩하기
    ```html
    <ul>
        <li>메인 목록 리스트1
            <ul>
                <li>서브 목록</li>
                <li>서브 목록</li>
            </ul>
        </li>
        <li>메인 목록 리스트2
            <ol>
                <li>서브 목록</li>
                <li>서브 목록</li>
            </ol>
        </li>
    </ul>
    ```
    ```html
    <ol>
        <li>메인 목록 리스트1
            <ol>
                <li>서브 목록</li>
                <li>서브 목록</li>
            </ol>
        </li>
        <li>메인 목록 리스트2
            <ul>
                <li>서브 목록</li>
                <li>서브 목록</li>
            </ul>
        </li>
    </ol>
    ```