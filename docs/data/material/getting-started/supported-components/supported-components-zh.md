# 支持的组件

<p class="description">以下是 Material Design 组件和功能的列表. Those currently supported by MUI are highlighted ✓.</p>

虽然我们尽量遵循一些可行的指南（当指南有争议性的时候我们会更多地依赖于常识，而这种情况会比您想象中的发生更多），但是我们并不指望能够做到支持每一个组件或者每一个组件下的功能。我们更倾向于通过提供一些以及搭建好的模块，让开发者创造更实用的用户界面以及用户体验。

如果您希望加对一个组件或一个未高亮显示的功能加以支持, 请搜索相关的 [GitHub 问题 ](https://github.com/mui/material-ui/issues)，或创建一个新的问题来讨论该方法，然后再提交 pull request。

- **[Expansion Panels](https://material.io/archive/guidelines/components/expansion-panels.html) ✓** (_旧 Material v1_)
- App bars（应用栏）
  - **[Top](https://material.io/design/components/app-bars-top.html) ✓**
  - **[Bottom](https://material.io/design/components/app-bars-bottom.html) ✓**
- **[横幅(Banners)](https://material.io/design/components/banners.html)** ([可组装](https://medium.com/material-ui/introducing-material-ui-design-system-93e921beb8df))
- **[Bottom navigation（底部导航栏）](https://material.io/design/components/bottom-navigation.html) ✓**
- **[Buttons（按钮）](https://material.io/design/components/buttons.html) ✓**
  - **[Text & contained buttons（原为 flat & raised）](https://material.io/design/components/buttons.html) ✓**
  - **[Toggle buttons](https://material.io/design/components/buttons.html#buttons-toggle-buttons) ~** ([实验室](/components/about-the-lab/))
  - **[Icon toggle buttons](https://material.io/design/components/buttons.html#toggle-button) ✓** (自定义 Checkbox)
- **[Buttons: Floating Action Button（按钮：浮动操作按钮）](https://material.io/design/components/buttons-floating-action-button.html) ✓**
  - Transitions（过渡动画）：
    - **[Speed dial](https://material.io/design/components/buttons-floating-action-button.html#types-of-transitions) ~** ([实验室](/components/about-the-lab/))
    - [Menu](https://material.io/design/components/buttons-floating-action-button.html#types-of-transitions)
    - [变形（Morph）](https://material.io/design/components/buttons-floating-action-button.html#types-of-transitions)
    - [全屏（Full screen）](https://material.io/design/components/buttons-floating-action-button.html#types-of-transitions)
  - **[Extended FAB（扩展的浮动操作按钮）](https://material.io/design/components/buttons-floating-action-button.html#extended-fab) ✓**
    - Speed dial（快速拨号）
- **[Cards（卡片）](https://material.io/design/components/cards.html) ✓**
- **[Chips（纸片）](https://material.io/design/components/chips.html) ✓**
  - **[Input（输入）](https://material.io/design/components/chips.html#input-chips) ✓**
  - [Choice（选择项）](https://material.io/design/components/chips.html#choice-chips)
  - [Filter（筛选）](https://material.io/design/components/chips.html#filter-chips)
  - [Action（操作）](https://material.io/design/components/chips.html#action-chips)
- **[Data tables（数据表格）](https://material.io/design/components/data-tables.html) ✓**
  - **Sortable（可排序的）✓**
  - **Selectable（可选择的）✓**
  - **Pagination（分页） ✓**
- **[Dialogs（对话框）](https://material.io/design/components/dialogs.html) ✓**
  - **[Alert dialog（警告对话框）](https://material.io/design/components/dialogs.html#alert-dialog) ✓**
  - **[Simple dialogs](https://material.io/design/components/dialogs.html#simple-dialog) ✓** （可以用 Dialog 和 List 组成。）
  - **[Confirmation dialogs（确认对话框）](https://material.io/design/components/dialogs.html#confirmation-dialog) ✓**
  - **[Full screen dialogs（全屏对话框）](https://material.io/design/components/dialogs.html#full-screen-dialog) ✓**
- **[Dividers（分隔线）](https://material.io/design/components/dividers.html) ✓**
  - **[Full bleed（等屏宽分隔线）](https://material.io/design/components/dividers.html#types) ✓**
  - **[Inset（内凹分隔线）](https://material.io/design/components/dividers.html#types) ✓**
  - **[Middle（中段分隔线）](https://material.io/design/components/dividers.html#types) ✓**
  - **[Subheader（副标题分隔线）](https://material.io/design/components/dividers.html#types) ✓**
- \***\*[Image lists](https://material.io/design/components/image-lists.html) ✓** (又名 Grid Lists)****\*\*****
- **[Lists（列表）](https://material.io/design/components/lists.html) ✓**
  - [类型:](https://material.io/design/components/lists.html#types)
    - **Single line （单行）✓**
    - **Two line（两行）✓**
    - Three line（三行）
  - **Avatar（头像）✓**
  - **Icon（图标）✓**
  - Thumbnail（缩略图）
  - **Controls（控件）✓**
    - **Checkbox（复选框）✓**
    - **Expand/collapse ✓** (又名 Nested)
    - **Switch（开关）✓**
    - Reorder（重新排序）
- **[Menus（菜单）](https://material.io/design/components/menus.html) ✓**
  - ** [下拉菜单](https://material.io/design/components/menus.html#dropdown-menu) ✓ ** （可以组成）
    - [Cascade（级联菜单）](https://material.io/design/components/menus.html#dropdown-menu)
  - [Exposed dropdown menus（公开的下拉菜单）](https://material.io/design/components/menus.html#exposed-dropdown-menu)
    - **Text field dropdown menu（文本框下拉菜单）** ✓（Select 选择框）
    - Editable dropdown menu（可编辑的下拉菜单）
  - **Contextual（上下文相关的）✓**
- **[Progress indicators（进度条指示）](https://material.io/design/components/progress-indicators.html) ✓**
  - **[Linear（线性进度条）](https://material.io/design/components/progress-indicators.html#linear-progress-indicators) ✓**
  - **[Circular（环状进度条）](https://material.io/design/components/progress-indicators.html#circular-progress-indicators) ✓**
  - **[Loading](https://material.io/archive/guidelines/components/progress-activity.html) ✓** (_旧 Material v1_)
- **[Selection controls（选择控件）](https://material.io/design/components/selection-controls.html) ✓**
  - **[Checkbox（单选按钮）](https://material.io/design/components/selection-controls.html#checkboxes) ✓**
  - **[Radio button（单选按钮）](https://material.io/design/components/selection-controls.html#radio-buttons) ✓**
  - **[Switch（切换开关）](https://material.io/design/components/selection-controls.html#switches) ✓**
- **[Sliders（滑块控件）](https://material.io/design/components/sliders.html) ✓**
  - **[Continuous（连续滑块）](https://material.io/design/components/sliders.html#continuous-slider) ✓**
  - **[Discrete（间续滑块）](https://material.io/design/components/sliders.html#discrete-slider) ✓**
- **[Snackbars](https://material.io/design/components/snackbars.html) ✓** (_旧 Material v1_)
- **[Subheaders](https://material.io/archive/guidelines/components/subheaders.html) ✓** (_旧 Material v1_)
  - **[Lists（列表副标题）](https://material.io/archive/guidelines/components/subheaders.html#subheaders-list-subheaders) ✓**
  - **[ Grid（网格副标题）](https://material.io/archive/guidelines/components/subheaders.html#subheaders-list-subheaders) ✓**
  - [Menu](https://material.io/archive/guidelines/components/subheaders.html#subheaders-list-subheaders)
- **[Steppers](https://material.io/archive/guidelines/components/steppers.html) ✓** (_旧 Material v1_)
  - **[Horizontal（横向的步骤条）](https://material.io/archive/guidelines/components/steppers.html#steppers-types-of-steppers) ✓**
  - **[Vertical（垂直的步骤条）](https://material.io/archive/guidelines/components/steppers.html#steppers-types-of-steppers) ✓**
  - **[Mobile steps（移动设备上的步骤条）](https://material.io/archive/guidelines/components/steppers.html#steppers-types-of-steps) ✓**
- **[Tabs（选项卡）](https://material.io/design/components/tabs.html) ✓**
  - **[Fixed tabs（固定的选项卡）](https://material.io/design/components/tabs.html#fixed-tabs) ✓**
  - **[Scrollable tabs（可滚动的选项卡）](https://material.io/design/components/tabs.html#scrollable-tabs) ✓**
- **[Text fields（文本框）](https://material.io/design/components/text-fields.html) ✓**
  - **[Standard](https://material.io/archive/guidelines/components/text-fields.html) ✓** (旧 Material v1)
  - **[Filled（填充的文本框）](https://material.io/design/components/text-fields.html#filled-text-field) ✓**
  - **[Outline（描边的文本框）](https://material.io/design/components/text-fields.html#outlined-text-field) ✓**
  - [类型](https://material.io/design/components/text-fields.html#input-types):
    - **Single-line（单行文本框）✓**
    - **Multi-line（多行文本框）✓**
    - Text-area（文本区域）
    - **Full-width（全宽文本框）✓**
  - [Assistive elements（辅助的元素）：](https://material.io/design/components/text-fields.html#anatomy)
    - **Helper text（帮助文本）✓**
    - **Error message（错误消息）✓**
    - **Icons（图标）✓**
    - 字符计数器（Character counter）
- **[Toolbars](https://material.io/archive/guidelines/components/toolbars.html) ✓** (旧 Material v1)
- **[Tooltips（工具提示）](https://material.io/design/components/tooltips.html) ✓**
- **Desktop（桌面 ）✓**
- **移动设备（Mobile）✓**
