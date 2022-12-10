name: Bug 反馈
labels:
  - bug
assignees:
  - IlyaIvanovsky
description: 报告一个 Bug
body:
  - type: input
    id: mc-version
    attributes:
      label: Minecraft 版本
      placeholder: 比如 1.19.2
    validations:
      required: true
  - type: input
    id: version
    attributes:
      label: 你使用的 Enhance Resources 版本.
      placeholder: 比如 1.0.0
    validations:
      required: true.
  - type: textarea
    attributes:
      label: Bug 描述
      placeholder: 描述你遇到的问题.
    validations:
      required: true
  - type: textarea
    attributes:
      label: 重现步骤
      description: |
        描述如何重现这个 Bug.
      placeholder: |
        1. First step
        2. Second step
        3. etc...
  - type: textarea
    attributes:
      label: 其他信息
      description: |
        Bug 的其他你认为有价值的信息.
