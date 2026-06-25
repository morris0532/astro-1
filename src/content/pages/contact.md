---
_schema: default
title: 联系我们 | HexaCore Solutions
description: >-
  联系 HexaCore Solutions，获取蜂窝板 product 咨询、技术支持和定制化解决方案。
  我们的专业团队随时准备为您服务。
pageSections:
  - _component: page-sections/ctas/cta-form
    id:
    eyebrowIcon: {}
    eyebrowText: 联系我们
    heading: 需要更多信息？<br /><span class="highlight-text">立即联系</span>
    subtext: >-
      我们的专业团队随时准备为您提供产品咨询、技术支持和定制化解决方案。
      无论您是建筑师、工程师还是采购经理，我们都能为您提供专业的服务。
    formAction: ./
    formBlocks:
      - _component: building-blocks/forms/input
        label: 姓名
        name: name
        type: text
        required: true
      - _component: building-blocks/forms/input
        label: 邮箱
        name: email
        type: email
        required: true
      - _component: building-blocks/forms/input
        label: 公司名称
        name: company
        type: text
        required: false
      - _component: building-blocks/forms/input
        label: 电话
        name: phone
        type: tel
        required: false
      - _component: building-blocks/forms/textarea
        label: 咨询内容
        name: message
        required: true
      - _component: building-blocks/forms/submit
        text: 提交咨询
        variant: primary
        size: md
        iconPosition: before
        hideText: false
        disabled: false
    buttonSections: []
    reverse: false
    maxContentWidth: 2xl
    paddingVertical: 4xl
    colorScheme:
    backgroundColor: highlight-grid
    contentBackground: true
    verticalOffset:
      size: none
      direction: front
    rounded: true
---
