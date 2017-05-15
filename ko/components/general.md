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

### VACallout

경고출력문입니다.

**사용법**

```
<va-callout
  type="danger"
  title="I am a danger callout!"
  text="There is a problem that we need to fix. A wonderful serenity has taken possession of my entire soul, like these sweet mornings of spring which I enjoy with my whole heart."
></va-callout>
```

**속성**

* type:String \(default: `success`\): 경고출력문의 종류입니다.
* dismissible:Boolean \(default: `false`\): 닫기버튼의 출력여부입니다.

### VACustomTab

```
<va-custom-tab>

  <li slot="nav"
      class="dropdown">
    <a class="dropdown-toggle"
      data-toggle="dropdown"
      href="#">
                            Dropdown <span class="caret"></span>
                          </a>
    <ul class="dropdown-menu">
      <li role="presentation"><a role="menuitem"
          tabindex="-1"
          href="#">Action</a></li>
      <li role="presentation"><a role="menuitem"
          tabindex="-1"
          href="#">Another action</a></li>
      <li role="presentation"><a role="menuitem"
          tabindex="-1"
          href="#">Something else here</a></li>
      <li role="presentation"
          class="divider"></li>
      <li role="presentation"><a role="menuitem"
          tabindex="-1"
          href="#">Separated link</a></li>
    </ul>
  </li>

  <li slot="nav"
      class="pull-right"><a href="#"
      class="text-muted"><i class="fa fa-gear"></i></a></li>

  <div slot="content"
      class="active"
      id="tab_1"
      title="Tab 1">
    <b>How to use:</b>

    <p>Exactly like the original bootstrap tabs except you should use the custom wrapper <code>.nav-tabs-custom</code> to achieve this style.</p>
    A wonderful serenity has taken possession of my entire soul, like these sweet mornings of spring which I enjoy with my whole heart. I am alone, and feel the charm of existence in this spot, which was created for the bliss of souls like mine. I am so happy, my dear friend, so absorbed in the exquisite sense of mere tranquil existence, that I neglect my talents. I should be incapable of drawing a single stroke at the present moment; and yet I feel that I never was a greater artist than now.
  </div>
  <!-- /.tab-pane -->
  <div slot="content"
      id="tab_2"
      title="Tab 2">
    The European languages are members of the same family. Their separate existence is a myth. For science, music, sport, etc, Europe uses the same vocabulary. The languages only differ in their grammar, their pronunciation and their most common words. Everyone realizes why a new common language would be desirable: one could refuse to pay expensive translators. To achieve this, it would be necessary to have uniform grammar, pronunciation and more common words. If several languages coalesce, the grammar of the resulting language is more simple and regular than that of the individual languages.
  </div>
  <!-- /.tab-pane -->
  <div slot="content"
      id="tab_3"
      title="Tab 3">
    Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
  </div>
  <!-- /.tab-pane -->

</va-custom-tab>
```

속성

* tabsClass:String \(default: ` `\): 커스텀탭 배치클랙스



