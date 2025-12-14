name: Bug Report
description: 报告一个系统或模块中的问题
labels: [bug]
body:
  - type: textarea
    id: description
    attributes:
      label: 问题描述
      description: 请清晰描述你遇到的问题
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: 重现步骤
      description: 请提供可复现步骤
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: 预期行为
    validations:
      required: true

  - type: textarea
    id: logs
    attributes:
      label: 日志或截图
      description: 如果有，请附上日志或截图
