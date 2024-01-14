# How To Use Submodule

## 서브모듈 내용 수정시
   - 해당 프로젝트에 대한 수정은 현재 폴더로 이동 한 후 staging 및 commit 필요.
   

## 서브모듈 데이터 fetching 방법

```bash
# root 경로에서 
git submodule init # 서브모듈 내역 삭제
git submodule update # 서브모듈 내역 새로 업데이트
```

해당 cli는 상위 프로젝트를 clone 받은 후에도 실행시켜주어야 정삭적으로 서브 모듈 프로젝트를 받아 올 수 있다. 

혹은 clone 시에 `--recurse-submodules` 옵션을 cli에 추가해주면 한번에 초기화가 가능하다.
