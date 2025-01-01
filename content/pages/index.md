---
type: PageLayout
title: 个人作品集
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/img1.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      As an experience interaction designer, I am familiar with figma, Axure, PS and other design software
    subtitle: >-
      这是我的信息——我与你们分享这一切，希望我的作品集能够给你留下深刻印象。如果您印象深刻，您可以继续向下滚动以查看有关我的更多详细信息和证书。
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-20
          - mb-0
          - ml-10
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: 查看所有项目
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-20
          - mb-0
          - ml-10
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-end
    subtitle: '项目'
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: 精选项目
    showFeaturedImage: false
    actions:
      - type: Link
        label: 查看所有项目
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "你有好玩的项目吗?敬请联系我...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: full name
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
          width: 1/2
          type: EmailFormControl
        - name: address
          label: 地址
          hideLabel: true
          placeholder: 地址
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: 接受地址并更新
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
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
---
