---
database-plugin: basic
---

```yaml:dbfolder
name: new database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: true
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  __tags__:
    key: __tags__
    id: __tags__
    input: metadata_tags
    label: File Tags
    accessorKey: __tags__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: false
    position: 4
    isHidden: true
    sortIndex: -1
    width: 190
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  ⚡-alias:
    input: text
    accessorKey: ⚡-alias
    key: ⚡-alias
    id: ⚡-alias
    label: ⚡Alias
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 121
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      custom_link_alias: 
      content_alignment: text-align-left
  📟-device:
    input: tags
    accessorKey: 📟-device
    key: 📟-device
    id: 📟-device
    label: 📟Device
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 127
    options:
      - { label: "◈ Rtr,⌘ Sw", value: "◈ Rtr,⌘ Sw", color: "hsl(59, 95%, 90%)"}
      - { label: "◈ Rtr", value: "◈ Rtr", color: "hsl(29,69%,52%)"}
      - { label: "⌘ Sw", value: "⌘ Sw", color: "hsl(220,63%,61%)"}
      - { label: "⌘ Sw (L3)", value: "⌘ Sw (L3)", color: "hsl(157, 95%, 90%)"}
      - { label: "⌘ Sw (L2/L3)", value: "⌘ Sw (L2/L3)", color: "hsl(256, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  📶-mode:
    input: tags
    accessorKey: 📶-mode
    key: 📶-mode
    id: 📶-mode
    label: 📶Mode
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 116
    options:
      - { label: "➋ Priv #", value: "➋ Priv #", color: "hsl(42,56%,56%)"}
      - { label: "➊ User >", value: "➊ User >", color: "hsl(210,26%,55%)"}
      - { label: "🔄 Multi", value: "🔄 Multi", color: "hsl(270,17%,55%)"}
      - { label: "⚙️ Config", value: "⚙️ Config", color: "hsl(139, 95%, 90%)"}
      - { label: "⚙️ Sub-Config", value: "⚙️ Sub-Config", color: "hsl(122, 95%, 90%)"}
      - { label: "➋ Priv", value: "➋ Priv", color: "hsl(53, 95%, 90%)"}
      - { label: "⚙️ Config-Line", value: "⚙️ Config-Line", color: "hsl(61, 95%, 90%)"}
      - { label: "⚙️ Config-If", value: "⚙️ Config-If", color: "hsl(256, 95%, 90%)"}
      - { label: "⚡ Exec (Privileged)", value: "⚡ Exec (Privileged)", color: "hsl(78, 95%, 90%)"}
      - { label: "⚙️ Config-Router", value: "⚙️ Config-Router", color: "hsl(113, 95%, 90%)"}
      - { label: "⚡ Exec (Privileged", value: "⚡ Exec (Privileged", color: "hsl(249, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  🗂️-category:
    input: tags
    accessorKey: 🗂️-category
    key: 🗂️-category
    id: 🗂️-category
    label: 🗂️Category
    position: 7
    skipPersist: false
    isHidden: true
    sortIndex: -1
    width: 50
    options:
      - { label: "🕹️ Mgmt", value: "🕹️ Mgmt", color: "hsl(0,29%,53%)"}
      - { label: "⚙️ Sys", value: "⚙️ Sys", color: "hsl(0,3%,93%)"}
      - { label: "🩺 Diag", value: "🩺 Diag", color: "hsl(132,20%,49%)"}
      - { label: "🛡️ Sec", value: "🛡️ Sec", color: "hsl(345, 95%, 90%)"}
      - { label: "🔌 Lines", value: "🔌 Lines", color: "hsl(1, 95%, 90%)"}
      - { label: "🔌 Interfaces", value: "🔌 Interfaces", color: "hsl(351, 95%, 90%)"}
      - { label: "🛣️ Routing", value: "🛣️ Routing", color: "hsl(194, 95%, 90%)"}
      - { label: "🏗️ Architecture", value: "🏗️ Architecture", color: "hsl(226, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  📝-description:
    input: text
    accessorKey: 📝-description
    key: 📝-description
    id: 📝-description
    label: 📝Description
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 670
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
  💻-command:
    input: text
    accessorKey: 💻-command
    key: 💻-command
    id: 💻-command
    label: 💻Command
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 188
    isSorted: false
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: true
  source_data: tag
  source_form_result: "#🌐/cisco/cmd"
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 35
  font_size: 14
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```
