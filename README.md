# GitPrefix

###git commit 메시지의 접두사 종류

Git commit 메시지에서 사용하는 대표적인 접두사 종류는 다음과 같습니다:

1. **WIP** (Work In Progress): 아직 작업이 완료되지 않았음을 나타내는 접두사로, 임시 커밋이나 미완성 코드를 커밋할 때 사용됩니다.
   
   ```
   WIP: Add user authentication feature
   ```

2. **feat** (Feature): 새로운 기능을 추가하는 커밋에 사용됩니다.
   
   ```
   feat: Implement login functionality
   ```

3. **fix**: 버그를 수정하는 커밋에 사용됩니다.
   
   ```
   fix: Resolve issue with user profile loading
   ```

4. **refactor**: 코드 리팩토링 (기능 변화 없이 코드 구조를 개선하는 작업) 시 사용됩니다.
   
   ```
   refactor: Simplify authentication logic
   ```

5. **chore**: 코드 변경 이외의 작업, 예를 들어 빌드 과정의 변경이나, 패키지 업데이트 등에서 사용됩니다.
   
   ```
   chore: Update dependencies to latest version
   ```

6. **docs**: 문서 작업에 관련된 커밋에 사용됩니다.
   
   ```
   docs: Update API documentation
   ```

7. **style**: 코드의 스타일을 변경할 때 사용됩니다 (공백, 포맷팅, 세미콜론 추가/제거 등 기능에 영향을 미치지 않는 변경).
   
   ```
   style: Format code according to style guide
   ```

8. **test**: 테스트 관련 작업에 사용됩니다 (테스트 추가 또는 수정).
   
   ```
   test: Add unit tests for user service
   ```

9. **perf** (Performance): 성능을 개선하는 변경에 사용됩니다.
   
   ```
   perf: Improve database query performance
   ```

10. **ci** (Continuous Integration): CI 설정이나 스크립트 변경 시 사용됩니다.
    
    ```
    ci: Update Travis CI configuration
    ```

11. **revert**: 이전 커밋을 되돌릴 때 사용됩니다.
    
    ```
    revert: Revert "feat: Add user authentication"
    ```

이러한 접두사들은 커밋의 의도를 명확히 하고, 나중에 코드 변경 내역을 추적할 때 유용하게 사용됩니다.
