{{#docs-viewer as |viewer|}}
  {{#viewer.nav as |nav|}}
    {{nav.section "Introduction"}}
    {{nav.item "What is Playground?" "docs.index"}}
    {{nav.item "test" "docs.test"}}
    {{nav.item "Usage" "docs.usage"}}
  {{/viewer.nav}}

  {{#viewer.main}}
    {{outlet}}
  {{/viewer.main}}

{{/docs-viewer}}
