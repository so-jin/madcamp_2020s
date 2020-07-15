# madcamp_2020s

tree Tab menu
3개의 fragment를 만들어서 tab구조를 구현
Fragment1
json file에 있는 contact 정보 읽어오기
Recyclerview를 통해 contact item 띄우기
Filterable interface implement해서 filter method를 이용한 search 기능 구현
Item 선택 시 intent를 통해 itemActivity로 전환
-> itemActivity에서 전화 버튼을 통해 dial application으로 전환
Item에 있는 delete 버튼에 대해 contact 삭제 기능 구현
하단의 FloatingActionButton으로 contact add기능 구현
-> button 선택 시 AddActivity로 전환 
-> AddActivity에서 name과 number입력 후 onActivityResult method를 통해 result Intent받아서 number_list에 추가
