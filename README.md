# git-command

### 📍 특정 Branch만 clone하고 싶을 때
보통 `git clone <git URI>` 명령어를 사용하면 `default Branch`를 받아오는 경우가 있다. 하지만 `default Branch`말고 다른 특정 `Branch`를 `clone`하고 싶다면 다음 명령어로 `clone` 할 수 있다.

```bash
# 명령어
git clone -b <branchName> --single-branch <git clone URL>

# example
git clone -b maintenance --single-branch https://github.com/YWTechIT/<repository>.git
```
