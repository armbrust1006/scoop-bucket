# Scoop Bucket
**scoop 버킷 추가 명령어:**
```PowerShell
scoop bucket add custom-bucket https://github.com/armbrust1006/scoop-bucket.git
```
main 브랜치는 전체 버킷 조회 및 최신 버킷을 제공하고 있습니다.

특정 버전의 경우, 각각 별도의 브렌치가 존재하니 확인 후 인스톨하시면 됩니다.

---

## Gradle Release Checksums
[Gradle hash 값 경로](https://gradle.org/release-checksums)

---

## PNPM 해시 코드 생성
**파일 다운로드 및 재생성:**
```PowerShell
Invoke-WebRequest "https://github.com/pnpm/pnpm/releases/download/v10.34.5/pnpm-win-arm64.exe" -OutFile p.exe
```

**해시 코드 생성:**
```PowerShell
Get-FileHash p.exe -Algorithm SHA256
```
