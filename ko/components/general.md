## General Components

### VAColorPaletteSet

AdminLTE에서 컬러셋을 나타내고 있는 컴포넌트입니다.

사용법

```
<va-color-palette-set
    :color="color"
></va-color-palette-set>
```

속성

* color:String \(default:`Primary`\): 목록에 있는 색상중에서 선택합니다.
  * Primary, Info, Success, Warning, Danger, Gray, Navi, Teal, Purple, Maroon, Black



### VAAlert

경고 및 알림 등을 나타내는 알림창입니다.

**사용법**

```
<va-alert
  type="danger"
  :dismissible="true">
  <div slot="header">
    <h4><i class="icon fa fa-ban"></i> Alert!</h4>
  </div>
  <div slot="body">
    Danger alert preview. This alert is dismissable. A wonderful serenity has taken possession of my entire
    soul, like these sweet mornings of spring which I enjoy with my whole heart.
  </div>
</va-alert>
```

**속성**

* type:String \(default: `success`\): 알림창 종류입니다.
  * success, info, warning, danger
* dismissible:Boolean \(default: `false`\): 닫기버튼의 출력여부입니다.







