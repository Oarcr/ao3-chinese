name: 功能请求 / Feature request
title: "[Feature] "
description: 提出你的功能请求 / Propose your feature request
labels: ['enhancement']

body:
  - type: markdown
    attributes:
      value: |
        ## 在提交问题之前，请确认以下事项：
        1. 请务必给 issue 填写一个简洁明了的标题，以便快速检索。
        2. 请确保 [已有的问题](https://github.com/V-Lipset/ao3-chinese/issues?q=is%3Aissue) 中没有人提交过相似 issue，否则请在已有的 issue 下进行讨论。
        3. 请务必按照模板规范详细描述问题，否则 issue 将会被直接关闭。
        ## Before submitting the issue, please make sure of the following checklist:
        1. Please be sure to fill in a concise and clear title for the issue so that others can quickly search.
        2. Please make sure there is no similar issue in the [existing issues](https://github.com/V-Lipset/ao3-chinese/issues?q=is%3Aissue).
        3. Please describe the problem in detail according to the template specification, otherwise the issue will be closed directly.

  - type: textarea
    id: description
    attributes:
      label: 功能描述 / Feature description
      description: 详细清晰地描述你的功能请求 / A clear and concise description of what the feature is
    validations:
      required: true

  - type: textarea
    id: use-case
    attributes:
      label: 使用场景 / Use case
      description: 请描述你的功能请求的使用场景 / Please describe the use case of your feature request
    validations:
      required: true

  - type: checkboxes
    id: target-module
    attributes:
      label: 适用模块 / Target Module
      description: 请选择该功能适用的脚本模块（至少选择一个） / Please select the module(s) for this feature request (select at least one)
      options:
        - label: 界面汉化 / UI Translation
        - label: 作品翻译 / Text Translation (Works/Comments)
        - label: 术语表与替换 / Glossary & Replacements
        - label: 作品屏蔽 / Content Blocker
        - label: 文章格式化 / Formatting
        - label: 设置面板与交互 / Settings Panel & UI
        - label: 其它 / Other
    validations:
      required: true
