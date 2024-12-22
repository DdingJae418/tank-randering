tank.glb, shell.obj 파일과 동일한 디렉토리에서 "Control the Tank.html" 파일을 실행합니다.
텍스처 파일의 경우 "./textures/" 경로에서 불러왔습니다.

구현 사항:
- 월드 공간 좌표 x,y,z 축 출력 완료
- 지면 그리드 출력 완료
- 탱크 로컬 좌표 x,y,z 축 구현 완료
- 방향키로 탱크 이동 구현 완료
- w,a,s,d 키를 눌러 turret 회전 및 barrel 회전 구현 완료
- 요구 사항에 맞춰 탱크 및 포탄 각각에 모두 텍스터 매핑 완료
    -> Diffusive Reflection 적용
    -> Ambient occlusion 적용
    -> Specular reflection 'shininess' 적용
    -> Specular reflection 'metalness' 적용
    -> Normal map 적용
- 스페이스바 클릭 시 barrel에서 포탄 발사 기능 구현 완료
    -> 발사 각도에 맞춰 포탄 생성 후 발사
    -> 발사된 포탄은 포물선을 그리며 이동
    -> 포탄의 월드 y 좌표가 0이하가 될 경우 씬에서 삭제
    -> p를 누를 경우, 날아가는 포탄들이 공중에서 정지
