---
type: ProjectFeedLayout
title: Projects
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/img1.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 50
projectFeed:
  type: ProjectFeedSection
  colors: colors-f
  showDate: false
  showDescription: true
  showReadMoreLink: true
  showFeaturedImage: true
  variant: variant-a
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
styles:
  title:
    textAlign: left
bottomSections:
  - type: ContactSection
    backgroundSize: full
    title: "让我们讨论讨论... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: 姓名
          hideLabel: true
          placeholder: 姓名
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: company
          label: 单位
          hideLabel: true
          placeholder: 单位
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: 邮箱
          hideLabel: true
          placeholder: 邮箱
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: 信息
          hideLabel: true
          placeholder: 请告诉我关于您的项目
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: 接受以便于我能收到您的信息
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "提交 \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
