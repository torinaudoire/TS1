<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Miss Mu and the Canary</title>

<style>
    body {
        font-family: system-ui, sans-serif;
        max-width: 700px;
        margin: 40px auto;
        line-height: 1.6;
        padding: 0 15px;
    }

    /* Footnote marker */
    .fn {
        color: #005bbb;
        cursor: pointer;
        font-weight: bold;
        font-size: 0.8em;
        vertical-align: super;
        margin-left: 2px;
    }

    /* Hidden panel container */
    .footnote-panel {
        max-height: 0;
        overflow: hidden;
        background: #f0f4ff;
        border-left: 3px solid #005bbb;
        padding: 0 12px;
        margin: 6px 0 12px;
        transition: max-height 0.25s ease, padding 0.25s ease;
    }

    /* Active (expanded) state */
    .footnote-panel.open {
        padding: 12px;
        max-height: 300px; /* Enough for several lines; can increase */
    }

    .footnote-label {
        font-size: 0.85em;
        font-weight: bold;
    }
</style>
</head>

<body>

<h1>Miss Mu and the Canary</h1>

<p>
“<span class="fn" data-fn="1">Yan’er</span>,
