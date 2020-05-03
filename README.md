# VueDjangoTodo
Inflearn 강의(https://www.inflearn.com/course/vue-js-2/)


## URL 설계
url 패턴 | 뷰 이름 | 템플릿 파일명
--------|-------|----------
/admin/ |(장고 기본 제공)| 
/|HomeView(TemplateView)|home.html
/todo/|TodoTV(TemplateView)|todo_index.html(Vue.js 코드 포함)
/api/todo/list/|ApiTodoLV(BaseListView)|불필요
/api/todo/create/|ApiTodoCV(BaseCreateView)|불필요
/api/todo/99/delete/|ApiTodoDelV(BaseDeleteView)|불필요
