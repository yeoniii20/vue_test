# 🎥Movit 🖤

---

Movie + love it 두 단어가 결합되어 만들어진 **Movit**은 영화에 대한 애정의 의미를 담고 있습니다. 

**Movie:** 단순한 영화가 아닌, 사용자가 사랑하고 즐기는 스토리와 감동을 의미합니다. Movit은 사람들이 좋아하는 영화, 새로운 영화, 다양한 영화 정보를 제공합니다.

**Love it**: 영화 감상의 매 순간을 사랑하고 즐기는 것을 의미합니다. Movit은 사용자들이 영화를 더욱 즐겁게 감상할 수 있도록 돕습니다.

Movit을 통해 영화에 대한 경험을 더욱 특별하고 즐겁게 경험했으면 좋겠습니다. 💟


<br/>
<br/>
<br/>


### 🛠️기술 스택 🛠️

| Framework |   Vue.js |
| --- | --- |
| local DB |   IndexedDB (idb library) |
| 상태관리 |   Vuex |
| Style |   Scoped CSS |
| API |   TMDB API |
| HTTP Client |   Axios |

<br/>
<br/>

### 🤖로컬 데이터베이스 (Indexed DB) 사용

⇒ IndexedDB는 클라이언트 측에서 대용량 구조화된 데이터를 저장할 수 있는 저수준 API입니다. db 라이브러리를 사용하여 IndexedDB의 비동기 API를 간소화 했습니다.

<br/>
<br/>

**주요 기능**

- IndexedDB 데이터베이스 초기화 및 업그레이드
- profile 데이터 저장 및 조회 기능 구현
- 데이터베이스 스키마 설계 (스토어, 키, 인덱스 등)

### 🍿영화 정보 API 사용

⇒ TMDB API를 사용하여 영화 정보를 받아오고 Vue 컴포넌트에서 이를 표시합니다. Axios를 사용하여 HTTP 요청을 보내고 데이터를 받아옵니다.

<br/>
<br/>

**주요기능**

- Axios를 사용한 TMDB API 호출
- 영화 정보 파싱 및 저장
- API 호출 에러 처리
