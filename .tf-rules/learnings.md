## Recent
[chat] Horizon's assets/base.css has a global `img { width: 100%; height: auto }` rule that overrides inline HTML width/height attributes. Any small inline icon (SVG cashback, badge, etc.) rendered via custom-liquid MUST have an explicit CSS width/height/max-width override scoped to its parent — otherwise it stretches to 100% of its container.
