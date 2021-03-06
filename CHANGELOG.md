## 0.4.4

`2016-12-01`

- [Component] Album: `CHANGED` `thumbPlacement` support `bottom/top` 
- [Component] Album: `NEW` add direct method to Album which can make the component be using easily more widely.
- [Component] Calendar: `FIXED` can not reset input value if value is null in React@15.x
- [Component] Carousel: `CHANGED` support new props `largeArrowsAndDots` & `centerDots`
- [Component] Carousel: `CHANGED` update react-slick to ~0.14.0
- [Component] CascadeSelect: `CHANGED` another efficient way to fix issue #7
- [Component] CascadeSelect: `CHANGED` subMenu won't be hide before selected options's length is larger than cascadeSize when cascadeSize is not equal to options level. [#7](https://github.com/uxcore/uxcore-cascade-select/issues/7)
- [Component] CascadeSelect: `FIXED` add support for browsers that does not implement array.prototype.find. 
- [Component] CascadeSelect: `CHANGED` beforeRender default value optimazition
- [Component] CascadeSelect: `FIXED` input height bug
- [Component] Dialog: `CHANGED` remove loading props on button  
- [Component] Dialog: `NEW` props `htmlClassName`
- [Component] Dialog: `FIXED` if html overflow is scroll, dialog can be scrolled as well.
- [Component] Form: `CHANGED` add subComp TextAreaCount for TextAreaFormField
- [Component] Form: `CHANGED` RadioFormField support `jsxdisabled`
- [Component] Form: `CHANGED` EditorFormField jsxcontent is deprecated. use jsxvalues directly.
- [Component] Form: `CHANGED` getValues method will return a promise if asyncValidate is true 
- [Component] Form: `FIXED` searchFormField lineHeight bug
- [Component] Form: `NEW` add new prop `asyncValidate`
- [Component] Mention: `FIXED` click on the contentEditable's placeholder, the editor can't focus. 
- [Component] Menu: `CHANGED` to rc-menu@4.13.0
- [Component] Message: `CHANGED` change `z-index` to 1070
- [Component] Pickable: `CHANGED` small style change in hook mode 
- [Component] Popover: `FIXED` prop `delay` fail to work
- [Component] Popover: `CHANGED` new scaffold
- [Component] Popover: `CHANGED` airbnb javascript style lint
- [Component] Radiogroup: `CHANGED` support new props `disabled`
- [Component] Steps: `FIXED` style bug when only one step set description
- [Component] Table: `FIXED` setState may be triggered in componentWillMount
- [Component] Table: `FIXED` rowData passed in method `addRowClassName` may be undefined
- [Component] Table: `FIXED` SelectCellField: bug when value is undefined
- [Component] Table: `FIXED` multiline reset is not thorough
- [Component] Table: `CHANGED` set default labelInValue in SelectCellField 
- [Component] Table: `CHANGED` new empty data
- [Component] Table: `CHANGED` action will not render if render function return false [#158](https://github.com/uxcore/uxcore-table/issues/158)
- [Component] Table: `FIXED` props `levels` fail to work [#157](https://github.com/uxcore/uxcore-table/issues/157)
- [Component] Tabs: `FIXED` brick & filter style bug
- [Component] Tabs: `FIXED` fix border-bottom style bug ([#13](https://github.com/uxcore/uxcore-tabs/issues/13))
- [Component] Tabs: `CHANGED` set the height of the tabpane to 0 when inactive
- [Component] Tabs: `NEW` support switch when the number of items is too large
- [Component] Tree: `FIXED` loading icon missing
- [Component] Uploader: `FIXED` fix file.response.getJson bug when upload fails.

## 0.4.3

`2016-11-02`

- [Component] Table: `CHANGED` actionBar button type (the first is outline  & others are secondary)
- [Component] Table: `CHANGED` change header title font-size to 14px
- [Component] Table: `CHANGED` lint (reduce errors numbrt to 24)
- [Component] Table: `CHANGED` change tree icon in subComp mode.
- [Component] Table: `CHANGED` `column.collapseNum` will support string
- [Component] Table: `CHANGED` new action column
- [Component] Table: `CHANGED` new column picker
- [Component] Table: `CHANGED` js style standardization `Cell/index`, `ActionBar`, `SearchBar`
- [Component] Table: `CHANGED` replace `deepcopy` with `lodash/cloneDeep`
- [Component] Table: `CHANGED` order icon change
- [Component] Table: `NEW` add link bar
- [Component] Table: `FIXED` columnPicker can hide all columns.
- [Component] Table: `FIXED` treeIcon cell should not has right border when className is kuma-uxtable-border-line.
- [Component] Table: `FIXED` body width calculation bug when there is fixed columns & width is not defined.
- [Component] Table: `FIXED` bodyHeight calculation bug [#132](https://github.com/uxcore/uxcore-table/issues/132)
- [Component] Table: `FIXED` emptyText lineHeight calculation bug [#133](https://github.com/uxcore/uxcore-table/issues/133)
- [Component] Album: `NEW` Add thumbnails
- [Component] Calendar: `FIXED` text-indent cause scroll issue.
- [Component] Carousel: `CHANGED` update react-slick to ~0.14.0
- [Component] Dialog: `CHANGED` set `vertical-center-dialog` as default wrapClassName
- [Component] Mention: `FIXED` inputEditor & textareaEditor trigger change event when mention addded.
- [Component] Mention: `FIXED` issue when mention's 'matchRange' props start from 0.
- [Component] Mention: `CHANGED` change panel's position with inputEditor & textareaEditor.
- [Component] Mention: `FIXED` fixed 'onChange' not trigger in inputEditor & textareaEditor.  
- [Component] Steps: `FIXED` missing react import
- [Component] Tabs: `NEW` support switch when the number of items is too large
- [Component] Tree: `FIXED` fix arraysEqual missing 
- [Component] Tree: `CHANGED` rewrite rc-tree render logic, move supportSvg judge to `render`
- [Component] Uploader: `FIXED` fix file.response.getJson bug when upload fails.

## 0.4.2

`2016-10-25`

- [Component] Form: `NEW` add new FormField `PickableFormField`
- [Component] Form: `CHANGED` update `PickableFormField` to ~0.2.0
- [Component] Form: `CHANGED` CascadeSelectFormField support `allowClear`
- [Component] Form: `CHANGED` update `uxcore-date-form-field` to ~0.4.0
- [Component] Calendar: `NEW` new props `showSecond` `showHour`
- [Component] Calendar: `FIXED` missing method `getTimeConfig` 
- [Component] Calendar: `CHANGED` add prop `timezone` to fix calendar timezone
- [Component] Calendar: `CHANGED` all panel support clear icon

## 0.4.1

`2016-09-20`

- [General] `NEW` add new component `Album` 

## 0.4.0

`2016-09-01`

- [Component] Calendar: `FIXED` fix select time btn style bug
- [Component] Carousel: `FIXED` fix issue [#2](https://github.com/uxcore/uxcore-carousel/issues/2)
- [Component] Carousel: `CHANGED` new style
- [Component] Carousel: `CHANGED` update react-slick to ~0.12.0
- [Component] Collapse: `CHANGED` update UI
- [Component] Dropdown: `CHANGED` add animation
- [Component] Form: `CHANGED` support Child is null
- [Component] Form: `CHANGED` doValidate support param `always` which make doValidate always set the field error state to true/false.
- [Component] Form: `FIXED` fix server render bug 
- [Component] Formatter: `CHANGED` date method can handle undefined/null properly  
- [Component] Menu: `CHANGED` style change
- [Component] Pagination: `CHANGED` update dependency `uxcore-select` to ~0.3.0
- [Component] Pagination: `FIXED` fix pagination size changer style bug
- [Component] Pickable: `NEW` add new type hook
- [Component] Rate: `FIXED` always style bug [#8](https://github.com/uxcore/uxcore-rate/issues/8)
- [Component] Rate: `NEW` add prop tipShow
- [Component] Rate: `CHANGED` all stars before the one hovered should be acitve. (#4)
- [Component] Select: `FIXED` selected value text overflow (uxcore [#13](https://github.com/uxcore/uxcore/issues/13))
- [Component] Select: `FIXED` placeholder style bug in multiple mode
- [Component] Select: `FIXED` dropdown menu will be hidden when drag scrollbar in IE. [#15](https://github.com/uxcore/uxcore-select2/issues/15)
- [Component] Select: `FIXED` fix selected value style bug
- [Component] Select: `CHANGED` update dependency `rc-select` to ~6.4.0
- [Component] Steps: `FIXED` export bug
- [Component] Steps: `FIXED` add props `className`.
- [Component] Steps: `FIXED` style issue under IE8.
- [Component] Table: `CHANGED` change default fitResponse 
- [Component] Table: `CHANGED` support column.collapseNum
- [Component] Table: `CHANGED` table will listen props.fetchParams change.
- [Component] Table: `FIXED` fetchData caused by fetchParams change will pass the out-dated params.
- [Component] Table: `FIXED` saveRow bug [#155](https://github.com/uxcore/uxcore-table/issues/155)
- [Component] Table: `FIXED` missing deepcopy protect when passing parma in column.action. [#154](https://github.com/uxcore/uxcore-table/issues/154)
- [Component] Tabs: `NEW` support prop className 
- [Component] Totop: `CHANGED` new style
- [Component] Transfer: `FIXED` fix bug in locateItem and _removeJustMoved
- [Component] Transfer: `CHANGED` apply new style
- [Component] Transfer: `CHANGED` add `height` props
- [Component] Tree: `CHANGED` update rc-tree to ~1.1.0
- [Component] Uploader: `FIXED` fix `preventDuplicate`

`2016-08-11`

- [Component] Dialog: `NEW` upgrade to rc-dialog@0.6.2
- [Component] Dialog: `NEW` support center vertically 
- [Component] Dialog: `FIXED` when confirmbox's title or content is english words, the line would not break.  
- [Component] Table: `NEW` new tree select mode (support checked/unchecked/halfchecked)
- [Component] Table: `NEW` add new prop `onSearch` `onOrder` `onPagerChange`
- [Component] Table: `NEW` add new prop `isMiniPager` & `showPagerSizeChanger`
- [Component] Table: `NEW` support column group
- [Component] Table: `NEW` support column tilte custom render 
- [Component] Table: `CHANGED` tree mode style improve
- [Component] Table: `CHANGED` remove props.passedData support
- [Component] Table: `CHANGED` little change in tree mode style
- [Component] Table: `CHANGED` replace half-checked icon with svg
- [Component] Table: `CHANGED` recover the logic about passedData in fetchData method.
- [Component] Table: `CHANGED` update `uxcore-select2` to ~0.3.0
- [Component] Table: `CHANGED` column.renderChildren will pass rowData to user.
- [Component] Table: `CHANGED` jQuery free!
- [Component] Table: `FIXED` even row calculation bug
- [Component] Table: `FIXED` fix bug in `column.isDisable`
- [Component] Table: `FIXED` fix bug that columnPicker can make all coloumns hidden (#140)
- [Component] Table: `FIXED` fix bug that columnPicker will show checkbox row when checkbox is user-defined.
- [Component] Form: `NEW` add renderView prop in InputFormField
- [Component] Form: `NEW` add SwitchFormField
- [Component] Form: `CHANGED` CascadeFormField support multiple placeholders.
- [Component] Form: `CHANGED` Form doValidate will pass the field whose jsxshow is false.
- [Component] Form: `CHANGED` remove ve support !
- [Component] Form: `CHNAGED` change dependency `uxcore-select2` to ~0.3.0
- [Component] Form: `CHNAGED` change dependency `uxcore-select-form-field` to ~0.2.0
- [Component] Form: `CHANGED` change dependency `uxcore-date-form-field` to ~0.3.0
- [Component] Form: `CHANGED` add labelMatchInputHeight support (style) [#111](https://github.com/uxcore/uxcore-form/issues/111)
- [Component] Form: `FIXED` fix label style bug in IE/FireFox
- [Component] Calendar: `NEW` add polish support.
- [Component] Calendar: `NEW` add new prop `inputWidth` for adjusting the trigger width.
- [Component] Calendar: `CHANGED` update dependency `rc-calendar` to ~6.0.0
- [Component] Select: `CHANGED` new dev tool
- [Component] Select: `CHANGED` repository
- [Component] Select: `CHANGED` update dependency `rc-select` to ~6.4.0
- [Component] Select: `FIXED` fix selected value style bug
- [Component] Select: `FIXED` dropdown menu will be hidden when drag scrollbar in IE. [#15](https://github.com/uxcore/uxcore-select2/issues/15)
- [Component] Mention: `FIXED` fixed the select panel's position error when the page is scrolled.
- [Component] Mention: `CHANGED` Separate editor from mention component with three types
- [Component] Mention: `NEW` props `delimiter` `readOnly` `defaultValue` `onAdd`
- [Component] Mention: `NEW` add `tinymce` support
- [Component] Mention: `NEW` add `placeholder` supports





## 0.3.3

`2016-07-29`

- [General] `FIXED` fix bug imported from rc-dropdown

## 0.3.2

`2016-07-27`

- [General] `FIXED` move uxcore component from devDependency to dependency

## 0.3.1

`2016-07-22`

- [General] support import single component from uxcore

## 0.3.0

`2016-07-05`

- [Component] Dialog: `FIXED` remove console
- [Component] Dialog: `NEW` add polish support.
- [Component] Uploader: `CHANGED` queueCapacity will concern props.fileList
- [Component] Uploader: `FIXED` fix issue [#15](https://github.com/uxcore/uxcore-uploader/issues/15) [#16](https://github.com/uxcore/uxcore-uploader/issues/16) [#17](https://github.com/uxcore/uxcore-uploader/issues/17)
- [Component] Uploader: `CHANGED` add className for download & preview button
- [Component] Uploader: `CHANGED` remove Progress.isSupport
- [Component] Uploader: `NEW` add server render support
- [Component] Uploader: `CHANGED` add download property in download link
- [Component] Uploader: `FIXED` fix response process bug.
- [Component] Uploader: `CHANGED` cancel icon style fix (#24)
- [Component] Uploader: `NEW` add polish support.
- [Component] Tag: `NEW` add polish support
- [Component] Calendar: `NEW` add polish support.
- [Component] Form: `CHANGED` do not trigger jsxonChange when resetValues() & setValues() & jsxvalues change.


## 0.2.3

`2016-06-29`

- [Component] TextAreaFormField: `FIX` fix server render bug
- [Component] Form: `CHANGED` update tinymce dependency to ~0.2.0
- [Component] Form: `CHANGED` add warning in ButtonGroupFormField
- [Component] Form: `FIX` fix server render bug

## 0.2.2

`2016-06-24`

- [General] build kuma with component
- [Component] add new component tag, tree-select, multi-select & animate

## 0.2.1

`2016-06-07`

- [General] change libraryTarget config in webpack config.

