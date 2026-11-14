Dawn Stage 적용 안내

포함 파일
index.html: 부모 Dawn Stage 채팅 화면.
poster-instructions.md: Copilot Studio 포스터 에이전트 안내 전체 교체문.
skill1.txt: 기존 skill1의 이름·설명·안내 교체문.

적용
1. 포스터 에이전트의 안내 전체를 poster-instructions.md의 '역할'부터 끝까지로 교체합니다. 기존 끝부분의 카피라이터 역할과 '파일은 만들지 않습니다' 문구를 남기지 않습니다.
2. 기존 skill1을 skill1.txt 내용으로 수정합니다.
3. 포스터 에이전트 도구에 Canva MCP를 추가하고 OAuth 인증을 완료합니다. ChatGPT의 Canva 설치와 별도 연결입니다.
4. 부모 Dawn Stage가 승인된 공연 정보를 포스터 에이전트에 전달하고 실제 결과 링크를 반환받도록 설정합니다.
5. 저장·게시 후 테스트합니다. 실제 Canva 디자인 링크, 정확한 문구, 미리보기 검수와 수정 저장 여부를 확인합니다.
6. GitHub에 이 파일들을 저장해도 Copilot Studio 설정은 자동으로 바뀌지 않습니다. index.html은 채팅 화면만 표시합니다. GitHub Pages 등 호스팅 설정은 별도입니다.

지식 PDF
공연인쇄홍보물제작.pdf는 현재 내용을 제공받지 않아 검토하지 않았습니다. 기존 지식은 유지하되 구형 Create·PowerPoint 전용 안내가 새 제작 방식과 충돌하지 않는지 확인하세요.
API 키·OAuth 비밀값은 HTML·공개 저장소에 저장하지 마세요.

GitHub 연결 확인
https://github.com/settings/installations 에서 ChatGPT Codex Connector의 Configure를 엽니다.
설치 계정이 저장소 소유자인 wujin-han인지 확인합니다.
Repository access에서 Only select repositories를 선택하고 wujin-han/-를 포함해 Save합니다.
Permissions에서 Contents 쓰기 권한을 확인하고 추가 권한 승인 요청이 있다면 검토합니다.
일반 사용자가 타사 앱의 권한 목록을 직접 편집하는 화면은 아닙니다. 필요한 권한을 요청하지 않는 앱이라면 올바른 Codex 연결 앱 설치·재인증이 필요합니다.
앱이 없다면 https://github.com/apps/chatgpt-codex-connector 에서 설치 대상 계정과 저장소를 선택합니다.

