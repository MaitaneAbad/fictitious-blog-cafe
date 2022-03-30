{
  "requestedUrl": "https://maitaneabad.github.io/fictitious-blog-cafe/",
  "finalUrl": "https://maitaneabad.github.io/fictitious-blog-cafe/",
  "lighthouseVersion": "9.3.0",
  "userAgent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) HeadlessChrome/98.0.4758.102 Safari/537.36",
  "fetchTime": "2022-03-30T16:15:53.512Z",
  "environment": {
    "networkUserAgent": "Mozilla/5.0 (Linux; Android 7.0; Moto G (4)) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/98.0.4695.0 Mobile Safari/537.36 Chrome-Lighthouse",
    "hostUserAgent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) HeadlessChrome/98.0.4758.102 Safari/537.36",
    "benchmarkIndex": 812.5
  },
  "runWarnings": [],
  "configSettings": {
    "emulatedFormFactor": "mobile",
    "formFactor": "mobile",
    "locale": "en-US",
    "onlyCategories": [
      "pwa",
      "performance",
      "accessibility",
      "best-practices",
      "seo"
    ],
    "channel": "lr"
  },
  "audits": {
    "list": {
      "id": "list",
      "title": "Lists contain only `<li>` elements and script supporting elements (`<script>` and `<template>`).",
      "description": "Screen readers have a specific way of announcing lists. Ensuring proper list structure aids screen reader output. [Learn more](https://web.dev/list/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "link-text": {
      "id": "link-text",
      "title": "Links have descriptive text",
      "description": "Descriptive link text helps search engines understand your content. [Learn more](https://web.dev/link-text/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "summary": {},
        "items": [],
        "headings": []
      }
    },
    "diagnostics": {
      "id": "diagnostics",
      "title": "Diagnostics",
      "description": "Collection of useful page vitals.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "type": "debugdata",
        "items": [
          {
            "totalByteWeight": 391719,
            "numTasksOver25ms": 1,
            "numTasksOver100ms": 0,
            "rtt": 0.8999999999999999,
            "numFonts": 4,
            "mainDocumentTransferSize": 2318,
            "numTasksOver50ms": 1,
            "maxRtt": 0.8999999999999999,
            "numStylesheets": 3,
            "numRequests": 18,
            "numTasksOver500ms": 0,
            "numTasks": 149,
            "throughput": 36867642327.961136,
            "numTasksOver10ms": 3,
            "totalTaskTime": 149.73600000000002,
            "numScripts": 1,
            "maxServerLatency": null
          }
        ]
      }
    },
    "aria-tooltip-name": {
      "id": "aria-tooltip-name",
      "title": "ARIA `tooltip` elements have accessible names",
      "description": "When an element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more](https://web.dev/aria-name/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "robots-txt": {
      "id": "robots-txt",
      "title": "robots.txt is valid",
      "description": "If your robots.txt file is malformed, crawlers may not be able to understand how you want your website to be crawled or indexed. [Learn more](https://web.dev/robots-txt/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "unsized-images": {
      "id": "unsized-images",
      "title": "Image elements do not have explicit `width` and `height`",
      "description": "Set an explicit width and height on image elements to reduce layout shifts and improve CLS. [Learn more](https://web.dev/optimize-cls/#images-without-dimensions)",
      "score": 0,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [
          {
            "key": "node",
            "itemType": "node"
          },
          {
            "itemType": "url",
            "text": "URL",
            "key": "url"
          }
        ],
        "items": [
          {
            "node": {
              "nodeLabel": "Imagen Blog",
              "path": "1,HTML,1,BODY,1,DIV,0,MAIN,1,ARTICLE,0,DIV,0,PICTURE,1,IMG",
              "snippet": "<img loading=\"lazy\" src=\"https://maitaneabad.github.io/fictitious-blog-cafe/img/blog1.webp\" alt=\"Imagen Blog\">",
              "selector": "article.post > div.post__img > picture > img",
              "boundingRect": {
                "top": 702,
                "height": 223,
                "left": 18,
                "bottom": 925,
                "width": 324,
                "right": 342
              },
              "type": "node",
              "lhId": "page-0-IMG"
            },
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog1.webp"
          },
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog2.webp",
            "node": {
              "nodeLabel": "Imagen Blog",
              "type": "node",
              "boundingRect": {
                "height": 223,
                "width": 324,
                "left": 18,
                "bottom": 1704,
                "top": 1482,
                "right": 342
              },
              "lhId": "page-1-IMG",
              "snippet": "<img loading=\"lazy\" src=\"https://maitaneabad.github.io/fictitious-blog-cafe/img/blog2.webp\" alt=\"Imagen Blog\">",
              "path": "1,HTML,1,BODY,1,DIV,0,MAIN,2,ARTICLE,0,DIV,0,PICTURE,1,IMG",
              "selector": "article.post > div.post__img > picture > img"
            }
          },
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog3.webp",
            "node": {
              "nodeLabel": "Imagen Blog",
              "selector": "article.post > div.post__img > picture > img",
              "boundingRect": {
                "bottom": 2517,
                "height": 223,
                "left": 18,
                "width": 324,
                "top": 2295,
                "right": 342
              },
              "snippet": "<img loading=\"lazy\" src=\"https://maitaneabad.github.io/fictitious-blog-cafe/img/blog3.webp\" alt=\"Imagen Blog\">",
              "path": "1,HTML,1,BODY,1,DIV,0,MAIN,3,ARTICLE,0,DIV,0,PICTURE,1,IMG",
              "lhId": "page-2-IMG",
              "type": "node"
            }
          }
        ]
      }
    },
    "pwa-page-transitions": {
      "id": "pwa-page-transitions",
      "title": "Page transitions don't feel like they block on the network",
      "description": "Transitions should feel snappy as you tap around, even on a slow network. This experience is key to a user's perception of performance. [Learn more](https://web.dev/pwa-page-transitions/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "splash-screen": {
      "id": "splash-screen",
      "title": "Is not configured for a custom splash screen",
      "description": "A themed splash screen ensures a high-quality experience when users launch your app from their homescreens. [Learn more](https://web.dev/splash-screen/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "Failures: No manifest was fetched.",
      "details": {
        "type": "debugdata",
        "items": [
          {
            "failures": [
              "No manifest was fetched"
            ],
            "parseFailureReason": "No manifest was fetched",
            "isParseFailure": true
          }
        ]
      }
    },
    "aria-progressbar-name": {
      "id": "aria-progressbar-name",
      "title": "ARIA `progressbar` elements have accessible names",
      "description": "When a `progressbar` element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more](https://web.dev/aria-name/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-meter-name": {
      "id": "aria-meter-name",
      "title": "ARIA `meter` elements have accessible names",
      "description": "When an element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more](https://web.dev/aria-name/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "meta-description": {
      "id": "meta-description",
      "title": "Document has a meta description",
      "description": "Meta descriptions may be included in search results to concisely summarize page content. [Learn more](https://web.dev/meta-description/).",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "aria-required-children": {
      "id": "aria-required-children",
      "title": "Elements with an ARIA `[role]` that require children to contain a specific `[role]` have all required children.",
      "description": "Some ARIA parent roles must contain specific child roles to perform their intended accessibility functions. [Learn more](https://web.dev/aria-required-children/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "meta-viewport": {
      "id": "meta-viewport",
      "title": "`[user-scalable=\"no\"]` is not used in the `<meta name=\"viewport\">` element and the `[maximum-scale]` attribute is not less than 5.",
      "description": "Disabling zooming is problematic for users with low vision who rely on screen magnification to properly see the contents of a web page. [Learn more](https://web.dev/meta-viewport/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "valid-lang": {
      "id": "valid-lang",
      "title": "`[lang]` attributes have a valid value",
      "description": "Specifying a valid [BCP 47 language](https://www.w3.org/International/questions/qa-choosing-language-tags#question) on elements helps ensure that text is pronounced correctly by a screen reader. [Learn more](https://web.dev/valid-lang/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "service-worker": {
      "id": "service-worker",
      "title": "Does not register a service worker that controls page and `start_url`",
      "description": "The service worker is the technology that enables your app to use many Progressive Web App features, such as offline, add to homescreen, and push notifications. [Learn more](https://web.dev/service-worker/).",
      "score": 0,
      "scoreDisplayMode": "binary"
    },
    "label": {
      "id": "label",
      "title": "Form elements have associated labels",
      "description": "Labels ensure that form controls are announced properly by assistive technologies, like screen readers. [Learn more](https://web.dev/label/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "non-composited-animations": {
      "id": "non-composited-animations",
      "title": "Avoid non-composited animations",
      "description": "Animations which are not composited can be janky and increase CLS. [Learn more](https://web.dev/non-composited-animations)",
      "score": null,
      "scoreDisplayMode": "notApplicable",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "efficient-animated-content": {
      "id": "efficient-animated-content",
      "title": "Use video formats for animated content",
      "description": "Large GIFs are inefficient for delivering animated content. Consider using MPEG4/WebM videos for animations and PNG/WebP for static images instead of GIF to save network bytes. [Learn more](https://web.dev/efficient-animated-content/)",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "headings": [],
        "overallSavingsMs": 0,
        "overallSavingsBytes": 0,
        "type": "opportunity",
        "items": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "tabindex": {
      "id": "tabindex",
      "title": "No element has a `[tabindex]` value greater than 0",
      "description": "A value greater than 0 implies an explicit navigation ordering. Although technically valid, this often creates frustrating experiences for users who rely on assistive technologies. [Learn more](https://web.dev/tabindex/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "server-response-time": {
      "id": "server-response-time",
      "title": "Initial server response time was short",
      "description": "Keep the server response time for the main document short because all other requests depend on it. [Learn more](https://web.dev/time-to-first-byte/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "displayValue": "Root document took 120 ms",
      "details": {
        "type": "opportunity",
        "items": [
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/",
            "responseTime": 123.153
          }
        ],
        "overallSavingsMs": 23.153000000000006,
        "headings": [
          {
            "valueType": "url",
            "key": "url",
            "label": "URL"
          },
          {
            "key": "responseTime",
            "label": "Time Spent",
            "valueType": "timespanMs"
          }
        ]
      },
      "numericValue": 123.153,
      "numericUnit": "millisecond"
    },
    "definition-list": {
      "id": "definition-list",
      "title": "`<dl>`'s contain only properly-ordered `<dt>` and `<dd>` groups, `<script>`, `<template>` or `<div>` elements.",
      "description": "When definition lists are not properly marked up, screen readers may produce confusing or inaccurate output. [Learn more](https://web.dev/definition-list/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-allowed-attr": {
      "id": "aria-allowed-attr",
      "title": "`[aria-*]` attributes match their roles",
      "description": "Each ARIA `role` supports a specific subset of `aria-*` attributes. Mismatching these invalidates the `aria-*` attributes. [Learn more](https://web.dev/aria-allowed-attr/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "frame-title": {
      "id": "frame-title",
      "title": "`<frame>` or `<iframe>` elements have a title",
      "description": "Screen reader users rely on frame titles to describe the contents of frames. [Learn more](https://web.dev/frame-title/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "unminified-css": {
      "id": "unminified-css",
      "title": "Minify CSS",
      "description": "Minifying CSS files can reduce network payload sizes. [Learn more](https://web.dev/unminified-css/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsMs": 0,
        "type": "opportunity",
        "items": [],
        "overallSavingsBytes": 0,
        "headings": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "first-contentful-paint": {
      "id": "first-contentful-paint",
      "title": "First Contentful Paint",
      "description": "First Contentful Paint marks the time at which the first text or image is painted. [Learn more](https://web.dev/first-contentful-paint/).",
      "score": 0.88,
      "scoreDisplayMode": "numeric",
      "displayValue": "1.9 s",
      "numericValue": 1860,
      "numericUnit": "millisecond"
    },
    "csp-xss": {
      "id": "csp-xss",
      "title": "Ensure CSP is effective against XSS attacks",
      "description": "A strong Content Security Policy (CSP) significantly reduces the risk of cross-site scripting (XSS) attacks. [Learn more](https://web.dev/csp-xss/)",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "type": "table",
        "items": [
          {
            "description": "No CSP found in enforcement mode",
            "severity": "High"
          }
        ],
        "headings": [
          {
            "itemType": "text",
            "text": "Description",
            "subItemsHeading": {
              "key": "description"
            },
            "key": "description"
          },
          {
            "itemType": "code",
            "subItemsHeading": {
              "key": "directive"
            },
            "text": "Directive",
            "key": "directive"
          },
          {
            "itemType": "text",
            "key": "severity",
            "text": "Severity",
            "subItemsHeading": {
              "key": "severity"
            }
          }
        ]
      }
    },
    "total-blocking-time": {
      "id": "total-blocking-time",
      "title": "Total Blocking Time",
      "description": "Sum of all time periods between FCP and Time to Interactive, when task length exceeded 50ms, expressed in milliseconds. [Learn more](https://web.dev/lighthouse-total-blocking-time/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "0 ms",
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "errors-in-console": {
      "id": "errors-in-console",
      "title": "No browser errors logged to the console",
      "description": "Errors logged to the console indicate unresolved problems. They can come from network request failures and other browser concerns. [Learn more](https://web.dev/errors-in-console/)",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "image-size-responsive": {
      "id": "image-size-responsive",
      "title": "Serves images with appropriate resolution",
      "description": "Image natural dimensions should be proportional to the display size and the pixel ratio to maximize image clarity. [Learn more](https://web.dev/serve-responsive-images/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "pwa-cross-browser": {
      "id": "pwa-cross-browser",
      "title": "Site works cross-browser",
      "description": "To reach the most number of users, sites should work across every major browser. [Learn more](https://web.dev/pwa-cross-browser/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "js-libraries": {
      "id": "js-libraries",
      "title": "Detected JavaScript libraries",
      "description": "All front-end JavaScript libraries detected on the page. [Learn more](https://web.dev/js-libraries/).",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "headings": [
          {
            "key": "name",
            "itemType": "text",
            "text": "Name"
          },
          {
            "itemType": "text",
            "key": "version",
            "text": "Version"
          }
        ],
        "summary": {},
        "type": "table",
        "debugData": {
          "type": "debugdata",
          "stacks": [
            {
              "id": "modernizr",
              "version": "3.6.0"
            }
          ]
        },
        "items": [
          {
            "version": "3.6.0",
            "npm": "modernizr",
            "name": "Modernizr"
          }
        ]
      }
    },
    "form-field-multiple-labels": {
      "id": "form-field-multiple-labels",
      "title": "No form fields have multiple labels",
      "description": "Form fields with multiple labels can be confusingly announced by assistive technologies like screen readers which use either the first, the last, or all of the labels. [Learn more](https://web.dev/form-field-multiple-labels/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "geolocation-on-start": {
      "id": "geolocation-on-start",
      "title": "Avoids requesting the geolocation permission on page load",
      "description": "Users are mistrustful of or confused by sites that request their location without context. Consider tying the request to a user action instead. [Learn more](https://web.dev/geolocation-on-start/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "inspector-issues": {
      "id": "inspector-issues",
      "title": "No issues in the `Issues` panel in Chrome Devtools",
      "description": "Issues logged to the `Issues` panel in Chrome Devtools indicate unresolved problems. They can come from network request failures, insufficient security controls, and other browser concerns. Open up the Issues panel in Chrome DevTools for more details on each issue.",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "performance-budget": {
      "id": "performance-budget",
      "title": "Performance budget",
      "description": "Keep the quantity and size of network requests under the targets set by the provided performance budget. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/budgets).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-command-name": {
      "id": "aria-command-name",
      "title": "`button`, `link`, and `menuitem` elements have accessible names",
      "description": "When an element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more](https://web.dev/aria-name/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "screenshot-thumbnails": {
      "id": "screenshot-thumbnails",
      "title": "Screenshot Thumbnails",
      "description": "This is what the load of your site looked like.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "scale": 3000,
        "type": "filmstrip",
        "items": [
          {
            "data": "data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRQBAwQEBQQFCQUFCRQNCw0UFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFP/AABEIANUAeAMBEQACEQEDEQH/xAGiAAABBQEBAQEBAQAAAAAAAAAAAQIDBAUGBwgJCgsQAAIBAwMCBAMFBQQEAAABfQECAwAEEQUSITFBBhNRYQcicRQygZGhCCNCscEVUtHwJDNicoIJChYXGBkaJSYnKCkqNDU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6g4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2drh4uPk5ebn6Onq8fLz9PX29/j5+gEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoLEQACAQIEBAMEBwUEBAABAncAAQIDEQQFITEGEkFRB2FxEyIygQgUQpGhscEJIzNS8BVictEKFiQ04SXxFxgZGiYnKCkqNTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqCg4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2dri4+Tl5ufo6ery8/T19vf4+fr/2gAMAwEAAhEDEQA/AP1ToAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgAoAKACgD//Z",
            "timestamp": 1011786612134,
            "timing": 300
          },
          {
            "data": "data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRQBAwQEBQQFCQUFCRQNCw0UFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFP/AABEIANUAeAMBEQACEQEDEQH/xAGiAAABBQEBAQEBAQAAAAAAAAAAAQIDBAUGBwgJCgsQAAIBAwMCBAMFBQQEAAABfQECAwAEEQUSITFBBhNRYQcicRQygZGhCCNCscEVUtHwJDNicoIJChYXGBkaJSYnKCkqNDU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6g4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2drh4uPk5ebn6Onq8fLz9PX29/j5+gEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoLEQACAQIEBAMEBwUEBAABAncAAQIDEQQFITEGEkFRB2FxEyIygQgUQpGhscEJIzNS8BVictEKFiQ04SXxFxgZGiYnKCkqNTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqCg4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2dri4+Tl5ufo6ery8/T19vf4+fr/2gAMAwEAAhEDEQA/APiKJXVR0rIuxc3fKABk0FM7f4KfDO7+MfxP0XwdaXsOly6iJ2+2XCM6RLFBJMxKryfliIwO5pokg+J37M/2t/Dfijwh4y07xf4Q1vxDB4Sk1SO1ns5LDUnVXWKWCVQzKYmDh4yw+V1O0hd3RDY5pq54j8Q/AN74K+J3iTwUG/tTU9E1W70p2tI2PnvBK8bOi/ewdhPriupPQzaOVSAyOECs0jEBVUZJPpSbRNr6Hrv7OP7PA+Pfi3xTpOoeJIvBtj4a0C68Q6lf3VjJcmK3t3iWQeUhDFgJd2BzhSACSBQ5W2LSsX/jD+y1cfDv4e6b8R/C3jDRfiP8N7+9bTU1zR/MgmtLkIHEV3aygPCzDcQPm4ALbd6blzXdiZLS6PIX0TUFt7OZ7C5WO9BFrI0TBZ8NtOw4+bDccZ54p3Isz7d8Z/s2ad8GvCQsvGXxD0jTPiFb2MV03hG1tZ7tk3qGEUl1GDHHLjPynj7pDFXVjwy1Z3xdkeSfYJo4IJ3ikEM5IikK4WQjrtJ4OPapsDdz074qfA6L4T2Wl2l/4ns77xlOIHvfDFpbytLYpNGZIy0+PKc42BlVsguMbh8xYjnviz4K0XwF42vtA0LxFJ4pt7I+VNqJ09rNDKM7lRWZiyjgbuATnGRhigOPEZPtU2KHKrZ4osgOPjuP3eduKVyrFq0O993rTGfQn7DDKP2pPCDhVdki1HCOu5XJ0+5AUjvkkDFAmSfETxL/AMSn4e3njzw/pPwm8SaR4902SDQNOL6VBfWBXdcajdaa7bY3jaNY/tn/AC0BMZz5II6InNPcz/Gmi/EbRPiL+0m/w8h1vSfiJcePYtStY9GkkttXvtEkn1QvJaohE09s0r2bv5QZCBE54QEbXVkiOrMe4vvE0/xC+Ji+DNSu7n4zDwl4dhafQbtpdQnuY4LIasttJAxdrsSL++2MXIS8JyNwoA+ivAmi+KPGnxEj0jULmbWfHOs/s0XVi7X14HnuL2XUJEEck0jf6wO2xt7fKwIYjBpbJDszzX4c+HNM/ZF+E9l4A+L2o6C+u+OfHXh+e/8ACs19BeLoul2l5FNNd3m0vEolVdhXOGjZSWbDqib5ndCSsrM7z9qH42a98MNa1rWvEngHVfFngK/8ZaDq+geIdQ8V2l/pUUVpMLqL+yrNbVDAJrRJIpCrPjedzMSd6Sv6g9ir+0T+zR4l8V/EXxP8SdA1fSPEXw41a5/tE+Ko9XtzBao7YeNv3mT5bfIBGGyNuOSVXna1Ojoey/ELSte8DfBX4qJceJNe8U3VlDoer6Fr2p+IIL7zzHcIz31jbRgvZxozA5LtuG3nhqaA0J/G17rP7Xnj3Q7vWZrme38HMvheyk1CK2ZNQntLQkWkkqssU7gy4bB4LkgqCKYHyt+1NrGv6rrfhLSvEvhvU9H17S9GWFrjWdZi1S/vYDLI0TTPHGm1l+cYcbyCCc5DGAPFmsZYRGXT/WjKgcsR9OtAWuNmRYo9qlWmZcnGCAPSuWrUvKyO+nSVrs85Ecjj0xW1jlNO0jZIsnriqAsWExWbb6/rQB5b41V18QXCE4VcYXPAzzXZDY4ZtuTOdK46ADtkdT9fWttkSmzc8H+JtP8AC+sPeap4W0nxfE0RRbTWZbyOONiwPmKbW4gfcMEYLFcMflzghW0GnZmt8Ufi/rHxX1fR7vUbaw0y10TSoNE0nTdMhZILKyh3eXCpdnkfl3YtI7sS5yTxilFRVhu5ykV8JsJIuTn7w/z7ChOxi0W5kjXPA3etGm4r2R7/AKKgOk2gIyPKXp06Vwvc9FLQ0Mf/AKqBDreFp5NqY6ck9gKVwL0bqqFbdSkYxumY8ngdfy/meKzcuVXLjBydkRXOqw28Dqsu2QjJbjOcVyyqSex2Kmo/Ecc/ifT5rK8nDMXtPnmIHIQnG73GTj8KnkbV2UpRi7IzrNWMQJHU12HGXY1AHJ47CgCS2th5vmAY9zQB5V41GfE17g5HHI+ldsNkefNanNS/erUlaEaxvcTJFGNzuQqjOOT/ACoLWpqan4P1zRpr6K90m9tpdPVmvo5YGVrTbMYCJhj92RKNhDY+YgdSMu6KZPa+BfEkmqfYF8Pas999oW0+yrYymXzmUssWzbneQCQuM4GcUjFjp/Cut2tqt1caPqFvbGBLoTS2johhdzGkmSMbWcFQ3QkEdaLktdD6BttOu9Kt4rO+tpbO8gAjlt54yjxsOCGU8g+xrhe56S2LEMTSuqgH5jjOKVwsW5lCt9nt06EZbjLH3oe1xJXdjh/F3i1o1e2tpBHaRLh5uhPrXKr1Wd+lNHls/jCJrxsCSVAf9YT+oFehTwzS1OKpX6LUn8B6h9mm1ydpSm+EbflyGPmA7T9QD+VXXj7sbGdFq7uerRWaDgKMVxl8xZitUXA2gmgq5YS0+YjAAx0poLnjnjm28nxNdr0+6f0rtj8Jwz3OWuFGSRVoz3GW0ptJo5lALIwYZ6cVdgvY7/w58ede8K6a1rYWenJO1iLBr3ZKJm4uozKcSBfNMF7PBu28IQwAlHmVHKXzEGqfF+fV4Psj+GtCttO+0xS/YrWO4ii8lBEDbnbNu2uYI2ebPnswJM3zNlqAnIk0/wCMOrWEtxNHY2InaCyhimQzo1uLa3W3VkKyg72iXaWbJUktH5bYIrlsZuR7P9tXV1iuYrO206F4kEdnZIVhhUDAVdxLEAYGWJJ6kkkk8DWp6C2J1QWtu0pBDsdqN6DHJqWO9jmT8R9ANzLYrqCCdgUSbkRE9OH6e2envVzo1OS6RVGcXOzPI/HupXSymw8to0PzSMB154B/LNPCU18ReJqW0RxBGw16vmcN7o7Xw7OmleANXne286TULiK3hkI/1PlneTn/AGgxA/3TXLNXlYtaHsaDrXmmpYjXLD1oKLMLAu4x04zVbAjx74jrt8V3OehVT/47XXHscc9zjZuGIPStTJ6FaVuMDpTEei+AvCui6/4LvVuU0GO/nnmhOoajrq2l1aMI4zaCGCSSNCkszMkkj+aFQMxEATzHlM1SuUdN8F6KLS6+0XgvL+20m8u5o4NVs4IYpo5vLTbI7Hz8gbhDEC7grsOCWXS7QmtDs/GHwk8I6H4f1i90nxTaahJawQSxxNqlsXLtcmERoqBjcM8QS5O3YsCuYnd5Fw0uTehm0rXO40SHOm2cacs0aAc1xPQ71sT67pv9pafeWkchgklge2EhGGXKkZOPc5/L0rNSV1cq19D55uvhZ4kt7iaOWxAiiUs9wXHlbR3z/Tr7V6ftIWsc3I0zPfxHcvdltSBmZjlmwM04w5VZEyvN3K+oRW93GZbcjP8AdA5/EVd7bkLQ9G1/w+dD+FEUe+KeaK5RnaPP7sqzqVbsSskkvzDqrJnoMc696Vzd6HZLOwXJ6+wrzrnRYs2twDjOaQywJ1Eny53GgVro8b+ILM3iu5zk4C8+vyiuyn8Jy1l+8djk7jcW6V0RMmQEDDdcgZoYt2dHf/DbxHY3BjWwXUiqwM8mj3EWoRxGZisSSPbs6pIzDaI2IfPBUGiLG9Bknw88TwWEd9J4e1OOzae4tvPa0cKJYI1lnQnHBSNg7A9F5PQ1pdE9C/Z+BPFEmjjVIfD2py6e0tvAlwtpIUd5zIsIU4+YuYpQuM5KEdaV0Qe86HHLDbW6vADLDCC8MowBhTwR2NedLc9OPwo0oUyO+0dMmotco5L4k61H/wAInLFaTq5mmWGQL6DLEfmBVwj7xlUlaJ4bqVqrgjGeOSa9FO5w7aj/AAZ4fuL/AFWS7tXeJ7BftEbxuFYSLlkIJ6AbSxP+zgfMy5Jy5DeLurns91410i28L3SaxbLDF5Ato4NpZJFC7UQADjgAfhnNYXbd0MsiMemfauCx1jonjXhk2/UVGxVrlkQqSGQjmkykrHjPjif7L4pvldVcZUj/AL5FehTWiOCo/eMK0KX92qsoUHtnvW8rpGN7s05dGjs33gFXGCD6HrWak3uNpLY7/T/2gbrwg/h/+x/Cnh7T49B1eLXNNhjN6ywXYe3aV/nuSXEws7dXVyQBH+7EZZmOtkKTZP4d/ab16x1fQdRuvDvhrWG0L7IbCHUrSV1hlt7bT4ElDLKGDldKtSxDDP71eEkZCcqJuzN0v42avottcwW2l6ULe7W2W9hdZ2F35NtdWpLEy5Tfb3s8REZQKCpjEbKGD5UJu57Fp97N4gubzUbgILi8ia4k254YkE8kkn8ST9a8yT1PTh8KCZVhiZiQFCkk0kW3oeReOL+3g8P2yIyBHvZpgcgZyqqPr90100lfY4qrPMFnl1a5S0tVMsr5IGQBgDJJJ4AABJJ4ABJ4Fd1uVXOdQd9WepaTpsHh7SJdOtlJuQkf2+YIQS5ZmEeWAcYwNynABVQV3IWPHNubOuKSVjj/ABn4mhu7drSKJTFC2Fc4Id8ckf7vT64ranTe5lLex6U2vQRXTRMjja2M4rzeZI7bG3iORUGBhuh9aTaY0nYijvYUujCeGTn60nYpJnh3xDnVvFt7tXZkr1PX5RzXo0vhTOCabdznVmeKVXU4YHIIrZ6mZsS+KpbiNUdfujrip5UIz7i8FxnKj86aViXqT6YUkkUYICnJNDYFmdgsbe+aE3qJ2SPpbw1MEtbMs/lo8IRm9AVx/OvNluepFWikaWoWxmtZoMoHZSjLKDjBGKhtLqUk2ef/ABj8Jz33h/QodNs98on8gJDGTu3/AHeQMAAhsknuM100KkY3uzmrQlfRGd4Q+G8egKRBJDdap/y0uQuVt2DA7Vz/ABKUBDDBUk9SBtJ1nI0jS7mX4zuZ/B9vNpNtFGU1GICS4iPIIbOxP9rgknsD1ya0pe+7yMppx0R5LqDSvPtYBSowIwSQg9Oa74djBO+rPaZcSyPLNjJGTivAep6FzTtLyO+0Nkhl+aEEemMdKe25a1Q/RtJEkXnzyhQcnr/M0Cs+pyBlt4NZ1CM3Dyaarvc3TMAwIC7SMd/ulcHPb1rJuU5qKLUVGLkzy+9njnvJ5YohBE8jMkQOdgJ4X8Ole4r2VzynuV6YhFY7hQOxtafHi2GOSx5/Ope5m9xb5sJgMD7VSWhm3fQ+lNJ/5BFmP+mS8fhXmy0keutUmaMCvJaOMB1V1ZiX2lAehA78E557e+K8TFRcZcz2PRw7vokYo1nw/FqenCyhgurl5dsZmDMrsVYAcjj5snnkqrcZow1J1PeWxVaqoe7Lch8ffCvUdW0m5dfEhW3gj8yW1S1IE5GDhn3liOBgYwMDjNevSko7nn1eZ6nLaV8A9VSxgubC+S2tbtAZfJmFw8ikZG1Xjj2cH+8evtXX7eK0MHTk1cxNY+FTWljK1rHII4GKSS3G0Ozg4OeTzkHvWsaq3OecHc3LlF8qTPQLXnpHWWP2c/CsHjj4r+HPDV9LcJp2sa9aadcNbsBIsUs6RuUJBAYKxxkEZ7VU1ewot6n1b4v/AGVvC8OkeAbi70jxX4JPiT4gW/hB9D1i9imnuLORgDeQs1vGUPDfKyuDnPTrCjqi9z5q8HfsveMfiz4Qubnw9eeG7B9Q1KTTtPs9c1uC0vNVmiCP9ltY5MF5MSREklV5Xmnh43lzsqtP93yoxrL9iP4lv8Pr7xXq0OkeGPs+n3urRaDr2oLaaxeWlortcSw2bDzCEEbfeC54IyCCfSc1c8/l0OK+DXwI1v41Ta1JYanofh3SNGhjl1DXfE2oLYafbNIxWGN5mBAeQhgi99jelXJqIlG57h8S/wBgDWI/jn468L+BtTsbDwloWqWmiWGreNdWhtG1DUZ7SOdLKJ9irNcNvOEVRxtz1yYU9NS+U8g+G/wI8Y+OPiVrXgK3tLbTdZ0P7UdZm1O5SG10iK1YrczXU2SscUbDDOCRyAMkgFyaWrMnG7sdr4b/AGM/FHj/AMWa54b8PeNvh1qusWFx9mtLW38V27Pq7+Qs2LNesoCsQWIVdyuuco2K50kZqGp9TaH+y/bXvwO+HN9pN5b63408ZLI9tFHrtvDb2cUeXbdEYy0gSKOXzWDp5TgJhjwfOn3PTg9LHB/Fz4Yaj4H1zR/s1vZHw3fadutNU0vU11G11OSIFZ5VkHGfMDAxgfuy6rluGbxcXD284U+h6VCoqVOU+pF4q/Y98ex/EHwzafa/DUepxyvf6xpqaxF9o0WAQtI9zfKOIIghTLnOS6DJLAV7lCnGjR9mePVnKtU52evD9nTxDDf6lFd3nhy202ztbW+bVp9XiSyktriVoopllPylSyOOdpOBgHIzy8jOtzTPNPiB4Yuvhp4sbw7ez2n2i2ki8xraYPE6Oqujow6qyOrA+jDIB4pNWZHMjwX4r2MkPiG9FpcmC2ulWXETblc45YgHAOc/lmu6jJNbHFVXvaFK5tSIJdo3FlIGOc1znWy38Etck+HHxF0HxLJYPdDSNXttTNszGPzhFMshQMQcZ24zg9aqfQmKseyeKP2ufD9rq/gnwn4O8EXmn6Zofjq18dXsuq6z5895cRAs0SgRBYU2tt3AMTgcZU7spOzVjZR0ucvpv7Xnw08I69Yxv8LtY1eLwb4mm8ReDftXifYLWSSC3jMNztg+eMS24uFx8wKJGSVLl/QjStHQ43J3PZbf466B8YPgVf8AxQ+I+r+B7X4gReBPEXhm3aDxYY9TnFws0dtGdIEHDlm2hvNI2StIwPyCMaa0C90fFvwc+LnhTwh4K8Z+DfHHhW98TeHPEEtjfqdL1EWN1bXdoZvKKu0ci7HW4ljfcjEAgrhgDWrjfUlM+jrn/gpn/bN/8QUuPDHiHQNM8Ta3b+IrZ/Cvif7Ff2twllDaSQPO1u6yQSLboceWpQlvvHaVj2Y+Y8Q+DH7S9v8ADj4y+NvE+r6HdeJfD/jaz1LSdasLrUj9vazvZA8pW6CDdMCqkuUG75vubsro4pq1yG0tWeyfB/8Ab38KfACwOn+Bvhdd2kEOsx6jHNN4jK3F7ALdIZIbx1g/egkSSqq7I0kaM7GEbeZLjz9TKM0tkdb8Kf2k5/Cuk/CCG18OfbpPBdtqMDj7e8JvUvmfftZEzEUWUhSN3IB+WvMr1FTi2z06MeZi/Gr4vXvj/WtOaxOtva6PE6W8/iDVBfzSFv3kkgIRAgPyphc52Z615vNecEdTXLCVjt7z9q/wnd+N9e8Wv8OrmfVPFumPo/iVH1orHJaPCsUiWwWIGNmMcblm3YwVAGdw9dSuee9zlPHH7Sdl4g8E+IPCOleF59O0e+0TSdBtJLnUvOmijsbyS5E0p8sCR5DKwIG0L2yOKYjzTx74vX4geJYtWNmbErp9jY+SZvN/49rWK335wPveVuxjjdjJxkyLcwtQ0ddXskQAGSMkgE9Qeo+vA/L3qouwOPMczLdRwW7TtFGUXH3R834f/rrPmidSjYv+HvAXi74u6xeaD4ZtdPaK106bUdYvdQ1AWVvptiCqNPNLI6qAN+cDc3yk7cAmmtdTKTs7HQeAP2L/AB54gFld6bFpEy6w93b6M1n4psw+qm1lYXH2ECXdKsZjYllONpUgkMQHa429LHMfED9jv4htYah4ljtdGWGHw2niz7E+t2Y1G6005L3a2ofeERfvHavIIGW4rrhNKOpzSV2cdqX7KHxAsfFnhjwnb22lan4w15EePw7ZatbvfWm6D7QpuE3jyl8n94XJ2gdSDxWqnEnl7nQ6P+yd4hsIPEV3qujnxRo8XhHVPEela14X1+0+wutnIkc05ldX82OF2KSQIFkYsu0gHcRyQ7Ht9p+xV4h07RhJJ4N0qK7ZrRbnSDqFu2o2IumSO3M0bP5ke93UDOGUnLBeTXE5SudCjGx5/wDFb4Sz/BzVIrHVPEEsb7pop4NJ8QRTtZSRELJHMiBmRlY4+brtJUtgkVz9DN00kN8U/Cfxd8MNR8RxeJofEGmnw/eWmn3rTa7DMouLqBriCNCgIkJhVnO0kKB82CQKu7asjN6aHqfgz4IeLrzQdB1U3dpC2vNbnSNM1XV4Pt97HPIIopktywbymdiNxx93d90Zrz6zu0mehSuk2T3XwW8aysIbWxUSN4k/4RPbDdxxD+0VXPk/fPGP4/uds0qcLScgnLoSr8DPFL6JqeqXF5pZ0uwvF05rqTxDamGa6MCztBE4kKu6o4yAcZBUEsMV0owN+y/Zh1+08O2+rXOkWvmTWseoHT/tkMt9HaSsqxzmEEuEJdQeMqc7gAM0tRyUeh578ZPhnN8KvEEem3dxp7XLtJ5trZ30dxJayKE3RyKpyhG7HPBIIBO04pEPTc4y0n2t8p5olsETh7iMtYxxjlnZcfz/AKVz9Ds2Zu/Cz47xfBzxB8RtL1jQpvEvhnxjoX9jahYW90LSWNdgZJ45fKlw6bpCFKY+YE5Awdk9DnlGzcmetfBj9svwvoEfw9Fh8L75D4BbVW8PmfxOsuEvCxdbk/ZAZdrsxXYYwBgYPJOso2djFS5pHmnxD/a9Y+N4pT4TKvZfC5/hruGpcsXilX7b/quxmz5X+z9/njeENCJbsteFf2908D2vw3i0/wAIatrkng3U5LyG88VeI1vrtLSayezn0+znjtIntYSkgdRl9rRxnB2gVfIxHVfCj9oTR/EGhfGzxFrXivxBbabD8ONS8MafpXjnxn/bWo31/qMybGs0aGH5AIVEoRDtAjY5ycTJPRAek2v7XGjfFLTr3xLd+BZbPxZ4qs9Mg1zU7LXHSJmtJoXka3i8omFpPs8a53ts2KRk7i3HLQ6o6nFftQfGmD4t6J4dsjot1BdaHa3cL6tqmoJf39+khUoJZBBFuEWCBuBPznnOSc1K8kEoWV7nOftP/G6e6+Evwu+HR1nRPEes2EK6z4n1rQbuO6jvbsIbWxSSZQN80NlHGkjZOS2M5TJ9CMU7s4Jy6Hong/8AaG03UvCnw717UfCc8viTwVa2FhY6jDq3l21xbWtyJIxJAYidxXcm4SDJbd2Cjx600p3fQ9WjGUo8vc39a/a40x9VspdI8GT2scPjhfHFyJ9Z8/7TclXEkSsIFEaHKBTtYjYSd27jeMlJXRlOLTsZHwG+O9l8ObXUrG60bUfEFvfSTvPpVxqyjSLhZERV82ze3cF0ZNwkRkY/dPHW7uJMdz0u5/aStdWt57qXw7NB4kvPDsXhy81VdRUwyW6uplbyDBw8iqFzuIXggdcq5pynlnxs+Lkfxsh0qyOj6vbT+H7m5tm1a9vU1W5uIpfKlVZJFiify48nYDvPztz66p6GLXM7M8ju9JuNNZ3DC4t1ODInBTjOHXqp5HWkxWscJeXKWccEsr+XFGrM0n90cAn8iaxOxrW5maTo3hjxXpsc+p+II9Ekku3kv7lt/wBpjt3bYiCPaUZYRCGLhgxN0EAbYSu9KN2ctWXQ7D4b+DfA9laadLHrtxcQrpxubt2mjiKTHTkuhAqlCfnuWe3DfME8kk58xQtTepMErmb8cfBPwp0XQbltI8Yya54kttTvIPtlsmw39strbNBP5MjKsSLOs8PlhjI4l89dyKsbdFNvlIkvePJdY0bQIdASW0Mh1JbGGeVBfwyBJmlKshXClsoVfCZMZ+Vw3LDXUzOp+IHhTwHF4n8RDwzrMR0dbvVWsC9+fLFvE5Nq6jy3lYSKTCEPzEoJWdI2OC7Gew/BbTvCkvgdTNq7WEllbtJDb+fHKb2QszyDf/y7hFySJR0B54JPn1F7x00/hOqtNN8C+JPEul2+t3N7Dos8rQz3lldxSMEM8cbcKjspWNpWyVYOY/lA3fLktCmuZWZ5v4j+C3w7tYGOm6trC3zRZSKfYAG2xE4JXMhWRpYdqAFjEZvljdBW8a846IzeHjJanoun2Xw/8NpfWl/rs7aJpdpKLW7WZAdUljgdol8rYTbGVlBHmn5N3lsC3I8mcOebb6noQmoRsi5ZW3wx1LTlF1rRtriO/v1W6F2kck9rHDE9riNhtIkZZUDjAVn3NlQBXRCMoKxhJqTKGky+DrO1ll/tKc6l9rvrcWcEqyeVHGkXkSMdg3q7O/zLt4hPyjcCul2LlXQ7nRtP8PSPfyXepPYxxKpiR5Y5mAMbMzZT5ZBvCR/KQf3ocgBGWrQPQ87v7TRdRknu7a4ni3xXMsbyXsUQ3J/qx5YUuGwoQKM7ywO9VVmrQ5m9Sp4d1+41C6MF3M00gi2xTiLfKoAHy8DLjAyQ2STkg5xSZUdXqeF/EHUJBFbaZAN013tUDHzcNnj3yF/I1nCPc2bscZc+FdcnuZo1sjtA2IwIVSo4yNx78k/U13wskkck7uR6j4N0p9M02RJSN8h24HYDgVzVHubQjpc8q8czLL4ovmUYG4cH6CuuirQRhPcoaD4evvE+otZadD59wltcXbLvVMRQQvNK2WIHyxxu3XnGBk4FdF0tyDuT+zX8SxrP9kHwneLqf2iW2+zs8YO6MxiRsl8BAZoh5h+TLY3ZGKLoZo6T8JvEGp/B/VNXj0/z7Wx1Y27zxTRsFlNqJ+zZIESSsxAIUL82M4rjn8R0weljmtX8DeJoNLt7loUk04wNcJLHextGmILeVgTvwrbLq2Uofm3yLHjzBsFJJ7oJOy0NvQvg98SVhvbrSYD5ds7o0llrFsRMUnihJhKzfv186eJMx7hubHJFVaHQy53syy3hP4l6LoFhfTST6Pp121l9je8u47aGUXUEk0MgldhGqbEBJZhtMiAgE0WgCn3OG8U6LrnhfUol1m1m03ULmFb3ypGCybJMkMyg5Qn0ODjBwMiqSJv1IU8Q6ha2kQjvbhUJPyLMwHvxmjlRalZXPR/hJqbafqV5vjMn2+I2QkJ3bQyksfwKpz6E1yVl1RstEd0LYQqkYbIQBRke1Zowe5NFO1rPHKhKSIwKsDyD2NUNaHm1+ou/iJbAxj/Q7QyE4654H5F6TNrHQu5I4prUmxo6ZlvLXHbP61DNVtY8R8aQyDxNqOImC+Zwdpx0FdtKSUUjjnuZFjqV1pkzy2lzLazNFJCzwuUYxyIY5EJH8LIzKR0IYg8Gui6ehBdvfFeu6lHcR3mtahdrcTy3MwuLp5PMllKGWRsnlnMURZjyxjTJO0U9FoM6/wAKeKtZg8Ca1DBqt9B5F7aXKeXcuuyXe22QEHIZcNgjkbjjrXLUVpm0HochqHinUL6Gyi8020NrZLYxxQEqPKEhlIbnLbpWZzk8E4GAFA1SE3cD4s1uSwnsn1i+a0uPM86A3LlJd7xu+5c4bc8MTnOctGhOSow9DLqXbn4g6/f2F9bXmp3F615cWtzLdXUzyXG+3jkjhxITuwqSsMZ7LjG0U9BGTdareamIFu7qa6W3Ro4RM5fylLtIVUnoC7u2PV2PUmhIBJyPssCjGQWP8qdgPWPhzbl7vTkGOJ5pGOf4VjViM1xVux2LY76SUBuozmsVuYu1yewsjql0sW7y4sFpJeyIOrH/AD1Iq7Ajx2x1mefxvLNdRxqrxBFaN8rGmMjJOM5xyfWs29Lo1vrY6ZNcsp7sW0UwkcxtJuTlcLjPP401sBWuPiLp+jzW3lBrvep5B2BT0wcjP6U1FsaZnxeONS1aG5ubS0sHijcD5mbcfUYPt34q72Znypm34b13SfFSShtPjjnj4eOSNSM5xwf8QK05mHIjXfwTod4MvpdqfcJt/lRzyJ5DG8U+FNP0Hwbq/wDZ9uLbeI5ZMOzbtrfL1Jx940uZyd2Uo2R4nJ98n1rpWxkhnakOwhJNAWRInAFaIzHyNlVHYA4pvYaPVPBl/Pa3KpHazSwW4MgeIAkmQqmDkjvt+gJNcM7vc6paLQ9AtWEkoa9SfT4WyyGaMbnHsAxrFbmNurEl8SXOoBrPwxp7C0jYfatQvISRKQT8o65xnOOB64xk9HKktWZc8r6I8P0iM28F8LwKts2WRDHvjD4znaTWF0dXLZlBbryo1up01BWZcRSbx5ZA44BXoOOAatIkZa+ILu28yVRHEXjMfmCMjcM5IyKu1h3YyyNnqkpjujJbzyMcSLjy8+rA8/kaHzR1iFrl2S51LT28iae2ntpDsV5wrIR65xkVKUXq9x2a3Oi0LxfdaBbup1q0mThVidXlVFHQrjG3jjnI46U+UDfXxHfeL/C+vZs/KsooiFuSw+8NrYJ7np0A+lGiHY8pvUhRYUiBEiKRJns2Tx+VbQ2M5FTrzVkiDGeaa3EyTcMVoZi9RxQ9ho9v+EtuL3UCJCfKWJmdVYru424OD/tGvPqaM6uU9es9E09CGW0Rtv8AfJb+dYp6l2tuaykAALgAdAOKT3HZPY+J5L8XS7Jr26ZO6lQQf/Hq6OWRneBee/0iZLdJJNRkSJQAjqhUfhmnZon3SrmzDMIr67jiJ+75Q/8AisUnOptYajDqxjxaYqnYbuQ+p2r/AI1KlVe5fLTFht7Dbho5mY9MygAf+O0c07j5Idzb0C1s4nkP2WOY7cZuFEgH0B4/SsqkpdzSNOJ6Tpdm8XgS+kkfJuIpJQnPC4wMfgAaS33IPGNRiCMzBcEyMN3rg13w2OeoigK1ZCAgUkMKYnYmiGVzQ9ibanvHwOjJtbyYAOwCx/N6H/661xT7HVFnr0byIBtCj2xWFmbXRZSU7stsH0FPlYro+F89a7jjEUEGluNEhYrRZF2JFfPtRZAhQ5U9aXKVfU6bwlBLqN4lvEMtI2Dj06n9K5qi1NYy0ueq6jqMscDab9nWASR+QihTtwVx8pJGSPcY460GF2eT614O1aG7nH2SSQq5DKi5Ze/KjJH8q6ISSE/eRztzZy2kpjlQxyDqjAgj8DW6dzLYhwaZQoRicAE0C3NrRPCur642ywsJ7oE43Ih2j8egqW0NJrU9X+GF+nhTRbmO5m/etLkNGQF2gDHLFcjJPIyDXDLmbujdStudvbfETTpWC/2rDnJG0yJ26/xUrS7GnNE0bXxvp8+duq2zkDcQCpwPfGfWpfMugNx7nyERsYr1ruOQKkBQce9O4CE5ouA5WzxTHc7vwJJp2mxpNfxTtJdN5MRMJ8oDPJzjnn06YNZSVy1LQ6iDxnbyXstoEuY4vKaRZJnXDYYg4LNjr0JI6VPKRcmuvitp8NjZ71nuJQnNuzgA4P8AEwBz0x1Occ03BvYpOxzepeJo9WuTfw2mkeXI+37HcQIzphQMltgYgnJ+99KWsdAujZl0Oz1LSkvtM0mwUzxCRYZIT69AQ2cdecdvemprqJrQ6rSbHw7pml2sWp6TG9zs3SPFaCSMN6D5Sf0z9apyXczj5kn/AAkGnaXrNxJbvcHTPJAgsI7QxrG/G5gWwefoBz071ndF2ZjXOsi8vLqS5YtBMwJjRWfYMcEkLgnvnHp6Cs/aMfIi7B4a0W/UbDJERwEI2L9AMDjtx9PWrVaSL9ki7D4PtbOArFeLCgIJMyq6/iD/AJ6dgBTdaTJ9jE+buTW1ySRIZGUsEYgdTikAiqXYKvUnAoEK8bxMQ6lSOxoACo8lW53EnP6Y/rVIY/LtEFYJsBwMgAn8eppiL8Ks87RJd/ZouWZ4gwUe2KkNTpNNutLXR7n7QlvOFVE2ncrOQDzznB6n6saiTd7I0ik9WVLHVNJvbwxz6ckVko+RQ+CuSMknqe/ek01qP3W7G3H41MOpNEptW0yIjCxghmTOOM9CBzis3T6kqV2ddFr+gymF7fVI4GkTeF39AOxHY+1ZNSRuuUq6r420/RlDfa4dSkfjaoHHuc59hTjCUtROSudJp16NU0u3vI7K2lhmXcCPkbryfxPpWTlbdGiinsyLUb200hEe5i+xRluCs+0MfTHf8KcXzbCdo7jLXxBpd3cZivV+1HGOFkbH4c/4VbjJEppnzwgwC+RwQMd67DmJ43LgLvOT0Cg5pPTUpIe4gSPY8ckcw6g9DU3uDViNMysqK+4k9HwBTvYm1yR4pLF8homyM/3sfnVX0KtZ2NCe3jsoY5mPm3b4KJgHH1AqOaTdi2klcqXE11LGJpQqo56gAfpWqaMmmRW8UEr4nnMSkj5wueO9JtvcNjRv4dPtUCWfnyufuyzIAH+gobbEtNSotiIVhmk/exH78Y4YUr3C1tRDL513i2GzPAJxwPeqSfUeltCezs3IM8iRzW7tsaXAYr7+1K9hI09P1/VLaeGz0+6+yIuWQsBg8dx6cVDipblRk4vQTV9cu9TK2utzm4aNsQzJgeVn7xwOvQcH0pKChsXKbluZ8zNouswyRXJnWF1kSUArkZzWlrozcuV6FYNdwWQClDb5PBwevWstGV7xJaWUt7A8ix7I4hneTgUmxpX3LiX9tHDGZbgyXCHOMFh147VnZ3ujXmSVjZuvF9nqekS29xGpkcBQoHHbnPbFJRad2K8TASzs5I5NjFZeNjtKCB+FaX1JaXQU6XCLNpnlka4Y/KVxsY/lVXFZEUFlBGq/bHkJY4VImHHqSSKrmJsJqcFnZTMtpKtzERwXJDL9cYGatN9SGtS9/aVpKkBFzKLiMA+Yw4XHYCoauaxaGW2oXd9qUMsZjJiPyvKnGcUbE83Mxs+q31vI7reR7uc7QAT+lCs9wlfdFMa1cCZ5fkLtwfl607IzvIjjuEu7xGvHYR4wzIOcf/rq7iJPKgbzVjvRHFnI3ocn8qRRAglLGOMmZF53bTx7072DXof0kn9lv4MEYPwj8C49P+Easv8A41WBY9f2Yvg6sZQfCfwOEP8ACPDlnj/0XQBF/wAMsfBb/okPgP8A8Jqy/wDjVACj9lr4ML0+EXgQfTw1Zf8AxqgBP+GWPgv/ANEi8Cf+E1Zf/GqAJP8Ahl/4NmNY/wDhU3gby15C/wDCN2eB9P3VADT+y58GSMH4SeBcf9i1Zf8AxqgBp/ZY+C5/5pF4E/8ACasv/jVO7EJ/wyv8F/8AokXgT/wmbL/41Rdi5SRP2X/g2ilV+E3gZVPYeG7MD/0VSGlYZ/wyz8GM/wDJIvAh/wC5asv/AI1Rcdg/4ZZ+C/8A0SHwH/4TVl/8aouwsg/4ZY+C/wD0SLwJ/wCEzZf/ABqi7JsH/DLPwYzz8IvAn/hNWX/xqndjJYf2Y/g7bBhF8J/A8QYYYJ4csxn6/u6VxnplABQAUAFABQAUAFABQAUAFABQAUAFABQAUAf/2Q==",
            "timestamp": 1011786912134,
            "timing": 600
          },
          {
            "data": "data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRQBAwQEBQQFCQUFCRQNCw0UFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFP/AABEIANUAeAMBEQACEQEDEQH/xAGiAAABBQEBAQEBAQAAAAAAAAAAAQIDBAUGBwgJCgsQAAIBAwMCBAMFBQQEAAABfQECAwAEEQUSITFBBhNRYQcicRQygZGhCCNCscEVUtHwJDNicoIJChYXGBkaJSYnKCkqNDU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6g4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2drh4uPk5ebn6Onq8fLz9PX29/j5+gEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoLEQACAQIEBAMEBwUEBAABAncAAQIDEQQFITEGEkFRB2FxEyIygQgUQpGhscEJIzNS8BVictEKFiQ04SXxFxgZGiYnKCkqNTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqCg4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2dri4+Tl5ufo6ery8/T19vf4+fr/2gAMAwEAAhEDEQA/APiKJXVR0rIuxc3fKABk0FM7f4KfDO7+MfxP0XwdaXsOly6iJ2+2XCM6RLFBJMxKryfliIwO5pokg+J37M/2t/Dfijwh4y07xf4Q1vxDB4Sk1SO1ns5LDUnVXWKWCVQzKYmDh4yw+V1O0hd3RDY5pq54j8Q/AN74K+J3iTwUG/tTU9E1W70p2tI2PnvBK8bOi/ewdhPriupPQzaOVSAyOECs0jEBVUZJPpSbRNr6Hrv7OP7PA+Pfi3xTpOoeJIvBtj4a0C68Q6lf3VjJcmK3t3iWQeUhDFgJd2BzhSACSBQ5W2LSsX/jD+y1cfDv4e6b8R/C3jDRfiP8N7+9bTU1zR/MgmtLkIHEV3aygPCzDcQPm4ALbd6blzXdiZLS6PIX0TUFt7OZ7C5WO9BFrI0TBZ8NtOw4+bDccZ54p3Isz7d8Z/s2ad8GvCQsvGXxD0jTPiFb2MV03hG1tZ7tk3qGEUl1GDHHLjPynj7pDFXVjwy1Z3xdkeSfYJo4IJ3ikEM5IikK4WQjrtJ4OPapsDdz074qfA6L4T2Wl2l/4ns77xlOIHvfDFpbytLYpNGZIy0+PKc42BlVsguMbh8xYjnviz4K0XwF42vtA0LxFJ4pt7I+VNqJ09rNDKM7lRWZiyjgbuATnGRhigOPEZPtU2KHKrZ4osgOPjuP3eduKVyrFq0O993rTGfQn7DDKP2pPCDhVdki1HCOu5XJ0+5AUjvkkDFAmSfETxL/AMSn4e3njzw/pPwm8SaR4902SDQNOL6VBfWBXdcajdaa7bY3jaNY/tn/AC0BMZz5II6InNPcz/Gmi/EbRPiL+0m/w8h1vSfiJcePYtStY9GkkttXvtEkn1QvJaohE09s0r2bv5QZCBE54QEbXVkiOrMe4vvE0/xC+Ji+DNSu7n4zDwl4dhafQbtpdQnuY4LIasttJAxdrsSL++2MXIS8JyNwoA+ivAmi+KPGnxEj0jULmbWfHOs/s0XVi7X14HnuL2XUJEEck0jf6wO2xt7fKwIYjBpbJDszzX4c+HNM/ZF+E9l4A+L2o6C+u+OfHXh+e/8ACs19BeLoul2l5FNNd3m0vEolVdhXOGjZSWbDqib5ndCSsrM7z9qH42a98MNa1rWvEngHVfFngK/8ZaDq+geIdQ8V2l/pUUVpMLqL+yrNbVDAJrRJIpCrPjedzMSd6Sv6g9ir+0T+zR4l8V/EXxP8SdA1fSPEXw41a5/tE+Ko9XtzBao7YeNv3mT5bfIBGGyNuOSVXna1Ojoey/ELSte8DfBX4qJceJNe8U3VlDoer6Fr2p+IIL7zzHcIz31jbRgvZxozA5LtuG3nhqaA0J/G17rP7Xnj3Q7vWZrme38HMvheyk1CK2ZNQntLQkWkkqssU7gy4bB4LkgqCKYHyt+1NrGv6rrfhLSvEvhvU9H17S9GWFrjWdZi1S/vYDLI0TTPHGm1l+cYcbyCCc5DGAPFmsZYRGXT/WjKgcsR9OtAWuNmRYo9qlWmZcnGCAPSuWrUvKyO+nSVrs85Ecjj0xW1jlNO0jZIsnriqAsWExWbb6/rQB5b41V18QXCE4VcYXPAzzXZDY4ZtuTOdK46ADtkdT9fWttkSmzc8H+JtP8AC+sPeap4W0nxfE0RRbTWZbyOONiwPmKbW4gfcMEYLFcMflzghW0GnZmt8Ufi/rHxX1fR7vUbaw0y10TSoNE0nTdMhZILKyh3eXCpdnkfl3YtI7sS5yTxilFRVhu5ykV8JsJIuTn7w/z7ChOxi0W5kjXPA3etGm4r2R7/AKKgOk2gIyPKXp06Vwvc9FLQ0Mf/AKqBDreFp5NqY6ck9gKVwL0bqqFbdSkYxumY8ngdfy/meKzcuVXLjBydkRXOqw28Dqsu2QjJbjOcVyyqSex2Kmo/Ecc/ifT5rK8nDMXtPnmIHIQnG73GTj8KnkbV2UpRi7IzrNWMQJHU12HGXY1AHJ47CgCS2th5vmAY9zQB5V41GfE17g5HHI+ldsNkefNanNS/erUlaEaxvcTJFGNzuQqjOOT/ACoLWpqan4P1zRpr6K90m9tpdPVmvo5YGVrTbMYCJhj92RKNhDY+YgdSMu6KZPa+BfEkmqfYF8Pas999oW0+yrYymXzmUssWzbneQCQuM4GcUjFjp/Cut2tqt1caPqFvbGBLoTS2johhdzGkmSMbWcFQ3QkEdaLktdD6BttOu9Kt4rO+tpbO8gAjlt54yjxsOCGU8g+xrhe56S2LEMTSuqgH5jjOKVwsW5lCt9nt06EZbjLH3oe1xJXdjh/F3i1o1e2tpBHaRLh5uhPrXKr1Wd+lNHls/jCJrxsCSVAf9YT+oFehTwzS1OKpX6LUn8B6h9mm1ydpSm+EbflyGPmA7T9QD+VXXj7sbGdFq7uerRWaDgKMVxl8xZitUXA2gmgq5YS0+YjAAx0poLnjnjm28nxNdr0+6f0rtj8Jwz3OWuFGSRVoz3GW0ptJo5lALIwYZ6cVdgvY7/w58ede8K6a1rYWenJO1iLBr3ZKJm4uozKcSBfNMF7PBu28IQwAlHmVHKXzEGqfF+fV4Psj+GtCttO+0xS/YrWO4ii8lBEDbnbNu2uYI2ebPnswJM3zNlqAnIk0/wCMOrWEtxNHY2InaCyhimQzo1uLa3W3VkKyg72iXaWbJUktH5bYIrlsZuR7P9tXV1iuYrO206F4kEdnZIVhhUDAVdxLEAYGWJJ6kkkk8DWp6C2J1QWtu0pBDsdqN6DHJqWO9jmT8R9ANzLYrqCCdgUSbkRE9OH6e2envVzo1OS6RVGcXOzPI/HupXSymw8to0PzSMB154B/LNPCU18ReJqW0RxBGw16vmcN7o7Xw7OmleANXne286TULiK3hkI/1PlneTn/AGgxA/3TXLNXlYtaHsaDrXmmpYjXLD1oKLMLAu4x04zVbAjx74jrt8V3OehVT/47XXHscc9zjZuGIPStTJ6FaVuMDpTEei+AvCui6/4LvVuU0GO/nnmhOoajrq2l1aMI4zaCGCSSNCkszMkkj+aFQMxEATzHlM1SuUdN8F6KLS6+0XgvL+20m8u5o4NVs4IYpo5vLTbI7Hz8gbhDEC7grsOCWXS7QmtDs/GHwk8I6H4f1i90nxTaahJawQSxxNqlsXLtcmERoqBjcM8QS5O3YsCuYnd5Fw0uTehm0rXO40SHOm2cacs0aAc1xPQ71sT67pv9pafeWkchgklge2EhGGXKkZOPc5/L0rNSV1cq19D55uvhZ4kt7iaOWxAiiUs9wXHlbR3z/Tr7V6ftIWsc3I0zPfxHcvdltSBmZjlmwM04w5VZEyvN3K+oRW93GZbcjP8AdA5/EVd7bkLQ9G1/w+dD+FEUe+KeaK5RnaPP7sqzqVbsSskkvzDqrJnoMc696Vzd6HZLOwXJ6+wrzrnRYs2twDjOaQywJ1Eny53GgVro8b+ILM3iu5zk4C8+vyiuyn8Jy1l+8djk7jcW6V0RMmQEDDdcgZoYt2dHf/DbxHY3BjWwXUiqwM8mj3EWoRxGZisSSPbs6pIzDaI2IfPBUGiLG9Bknw88TwWEd9J4e1OOzae4tvPa0cKJYI1lnQnHBSNg7A9F5PQ1pdE9C/Z+BPFEmjjVIfD2py6e0tvAlwtpIUd5zIsIU4+YuYpQuM5KEdaV0Qe86HHLDbW6vADLDCC8MowBhTwR2NedLc9OPwo0oUyO+0dMmotco5L4k61H/wAInLFaTq5mmWGQL6DLEfmBVwj7xlUlaJ4bqVqrgjGeOSa9FO5w7aj/AAZ4fuL/AFWS7tXeJ7BftEbxuFYSLlkIJ6AbSxP+zgfMy5Jy5DeLurns91410i28L3SaxbLDF5Ato4NpZJFC7UQADjgAfhnNYXbd0MsiMemfauCx1jonjXhk2/UVGxVrlkQqSGQjmkykrHjPjif7L4pvldVcZUj/AL5FehTWiOCo/eMK0KX92qsoUHtnvW8rpGN7s05dGjs33gFXGCD6HrWak3uNpLY7/T/2gbrwg/h/+x/Cnh7T49B1eLXNNhjN6ywXYe3aV/nuSXEws7dXVyQBH+7EZZmOtkKTZP4d/ab16x1fQdRuvDvhrWG0L7IbCHUrSV1hlt7bT4ElDLKGDldKtSxDDP71eEkZCcqJuzN0v42avottcwW2l6ULe7W2W9hdZ2F35NtdWpLEy5Tfb3s8REZQKCpjEbKGD5UJu57Fp97N4gubzUbgILi8ia4k254YkE8kkn8ST9a8yT1PTh8KCZVhiZiQFCkk0kW3oeReOL+3g8P2yIyBHvZpgcgZyqqPr90100lfY4qrPMFnl1a5S0tVMsr5IGQBgDJJJ4AABJJ4ABJ4Fd1uVXOdQd9WepaTpsHh7SJdOtlJuQkf2+YIQS5ZmEeWAcYwNynABVQV3IWPHNubOuKSVjj/ABn4mhu7drSKJTFC2Fc4Id8ckf7vT64ranTe5lLex6U2vQRXTRMjja2M4rzeZI7bG3iORUGBhuh9aTaY0nYijvYUujCeGTn60nYpJnh3xDnVvFt7tXZkr1PX5RzXo0vhTOCabdznVmeKVXU4YHIIrZ6mZsS+KpbiNUdfujrip5UIz7i8FxnKj86aViXqT6YUkkUYICnJNDYFmdgsbe+aE3qJ2SPpbw1MEtbMs/lo8IRm9AVx/OvNluepFWikaWoWxmtZoMoHZSjLKDjBGKhtLqUk2ef/ABj8Jz33h/QodNs98on8gJDGTu3/AHeQMAAhsknuM100KkY3uzmrQlfRGd4Q+G8egKRBJDdap/y0uQuVt2DA7Vz/ABKUBDDBUk9SBtJ1nI0jS7mX4zuZ/B9vNpNtFGU1GICS4iPIIbOxP9rgknsD1ya0pe+7yMppx0R5LqDSvPtYBSowIwSQg9Oa74djBO+rPaZcSyPLNjJGTivAep6FzTtLyO+0Nkhl+aEEemMdKe25a1Q/RtJEkXnzyhQcnr/M0Cs+pyBlt4NZ1CM3Dyaarvc3TMAwIC7SMd/ulcHPb1rJuU5qKLUVGLkzy+9njnvJ5YohBE8jMkQOdgJ4X8Ole4r2VzynuV6YhFY7hQOxtafHi2GOSx5/Ope5m9xb5sJgMD7VSWhm3fQ+lNJ/5BFmP+mS8fhXmy0keutUmaMCvJaOMB1V1ZiX2lAehA78E557e+K8TFRcZcz2PRw7vokYo1nw/FqenCyhgurl5dsZmDMrsVYAcjj5snnkqrcZow1J1PeWxVaqoe7Lch8ffCvUdW0m5dfEhW3gj8yW1S1IE5GDhn3liOBgYwMDjNevSko7nn1eZ6nLaV8A9VSxgubC+S2tbtAZfJmFw8ikZG1Xjj2cH+8evtXX7eK0MHTk1cxNY+FTWljK1rHII4GKSS3G0Ozg4OeTzkHvWsaq3OecHc3LlF8qTPQLXnpHWWP2c/CsHjj4r+HPDV9LcJp2sa9aadcNbsBIsUs6RuUJBAYKxxkEZ7VU1ewot6n1b4v/AGVvC8OkeAbi70jxX4JPiT4gW/hB9D1i9imnuLORgDeQs1vGUPDfKyuDnPTrCjqi9z5q8HfsveMfiz4Qubnw9eeG7B9Q1KTTtPs9c1uC0vNVmiCP9ltY5MF5MSREklV5Xmnh43lzsqtP93yoxrL9iP4lv8Pr7xXq0OkeGPs+n3urRaDr2oLaaxeWlortcSw2bDzCEEbfeC54IyCCfSc1c8/l0OK+DXwI1v41Ta1JYanofh3SNGhjl1DXfE2oLYafbNIxWGN5mBAeQhgi99jelXJqIlG57h8S/wBgDWI/jn468L+BtTsbDwloWqWmiWGreNdWhtG1DUZ7SOdLKJ9irNcNvOEVRxtz1yYU9NS+U8g+G/wI8Y+OPiVrXgK3tLbTdZ0P7UdZm1O5SG10iK1YrczXU2SscUbDDOCRyAMkgFyaWrMnG7sdr4b/AGM/FHj/AMWa54b8PeNvh1qusWFx9mtLW38V27Pq7+Qs2LNesoCsQWIVdyuuco2K50kZqGp9TaH+y/bXvwO+HN9pN5b63408ZLI9tFHrtvDb2cUeXbdEYy0gSKOXzWDp5TgJhjwfOn3PTg9LHB/Fz4Yaj4H1zR/s1vZHw3fadutNU0vU11G11OSIFZ5VkHGfMDAxgfuy6rluGbxcXD284U+h6VCoqVOU+pF4q/Y98ex/EHwzafa/DUepxyvf6xpqaxF9o0WAQtI9zfKOIIghTLnOS6DJLAV7lCnGjR9mePVnKtU52evD9nTxDDf6lFd3nhy202ztbW+bVp9XiSyktriVoopllPylSyOOdpOBgHIzy8jOtzTPNPiB4Yuvhp4sbw7ez2n2i2ki8xraYPE6Oqujow6qyOrA+jDIB4pNWZHMjwX4r2MkPiG9FpcmC2ulWXETblc45YgHAOc/lmu6jJNbHFVXvaFK5tSIJdo3FlIGOc1znWy38Etck+HHxF0HxLJYPdDSNXttTNszGPzhFMshQMQcZ24zg9aqfQmKseyeKP2ufD9rq/gnwn4O8EXmn6Zofjq18dXsuq6z5895cRAs0SgRBYU2tt3AMTgcZU7spOzVjZR0ucvpv7Xnw08I69Yxv8LtY1eLwb4mm8ReDftXifYLWSSC3jMNztg+eMS24uFx8wKJGSVLl/QjStHQ43J3PZbf466B8YPgVf8AxQ+I+r+B7X4gReBPEXhm3aDxYY9TnFws0dtGdIEHDlm2hvNI2StIwPyCMaa0C90fFvwc+LnhTwh4K8Z+DfHHhW98TeHPEEtjfqdL1EWN1bXdoZvKKu0ci7HW4ljfcjEAgrhgDWrjfUlM+jrn/gpn/bN/8QUuPDHiHQNM8Ta3b+IrZ/Cvif7Ff2twllDaSQPO1u6yQSLboceWpQlvvHaVj2Y+Y8Q+DH7S9v8ADj4y+NvE+r6HdeJfD/jaz1LSdasLrUj9vazvZA8pW6CDdMCqkuUG75vubsro4pq1yG0tWeyfB/8Ab38KfACwOn+Bvhdd2kEOsx6jHNN4jK3F7ALdIZIbx1g/egkSSqq7I0kaM7GEbeZLjz9TKM0tkdb8Kf2k5/Cuk/CCG18OfbpPBdtqMDj7e8JvUvmfftZEzEUWUhSN3IB+WvMr1FTi2z06MeZi/Gr4vXvj/WtOaxOtva6PE6W8/iDVBfzSFv3kkgIRAgPyphc52Z615vNecEdTXLCVjt7z9q/wnd+N9e8Wv8OrmfVPFumPo/iVH1orHJaPCsUiWwWIGNmMcblm3YwVAGdw9dSuee9zlPHH7Sdl4g8E+IPCOleF59O0e+0TSdBtJLnUvOmijsbyS5E0p8sCR5DKwIG0L2yOKYjzTx74vX4geJYtWNmbErp9jY+SZvN/49rWK335wPveVuxjjdjJxkyLcwtQ0ddXskQAGSMkgE9Qeo+vA/L3qouwOPMczLdRwW7TtFGUXH3R834f/rrPmidSjYv+HvAXi74u6xeaD4ZtdPaK106bUdYvdQ1AWVvptiCqNPNLI6qAN+cDc3yk7cAmmtdTKTs7HQeAP2L/AB54gFld6bFpEy6w93b6M1n4psw+qm1lYXH2ECXdKsZjYllONpUgkMQHa429LHMfED9jv4htYah4ljtdGWGHw2niz7E+t2Y1G6005L3a2ofeERfvHavIIGW4rrhNKOpzSV2cdqX7KHxAsfFnhjwnb22lan4w15EePw7ZatbvfWm6D7QpuE3jyl8n94XJ2gdSDxWqnEnl7nQ6P+yd4hsIPEV3qujnxRo8XhHVPEela14X1+0+wutnIkc05ldX82OF2KSQIFkYsu0gHcRyQ7Ht9p+xV4h07RhJJ4N0qK7ZrRbnSDqFu2o2IumSO3M0bP5ke93UDOGUnLBeTXE5SudCjGx5/wDFb4Sz/BzVIrHVPEEsb7pop4NJ8QRTtZSRELJHMiBmRlY4+brtJUtgkVz9DN00kN8U/Cfxd8MNR8RxeJofEGmnw/eWmn3rTa7DMouLqBriCNCgIkJhVnO0kKB82CQKu7asjN6aHqfgz4IeLrzQdB1U3dpC2vNbnSNM1XV4Pt97HPIIopktywbymdiNxx93d90Zrz6zu0mehSuk2T3XwW8aysIbWxUSN4k/4RPbDdxxD+0VXPk/fPGP4/uds0qcLScgnLoSr8DPFL6JqeqXF5pZ0uwvF05rqTxDamGa6MCztBE4kKu6o4yAcZBUEsMV0owN+y/Zh1+08O2+rXOkWvmTWseoHT/tkMt9HaSsqxzmEEuEJdQeMqc7gAM0tRyUeh578ZPhnN8KvEEem3dxp7XLtJ5trZ30dxJayKE3RyKpyhG7HPBIIBO04pEPTc4y0n2t8p5olsETh7iMtYxxjlnZcfz/AKVz9Ds2Zu/Cz47xfBzxB8RtL1jQpvEvhnxjoX9jahYW90LSWNdgZJ45fKlw6bpCFKY+YE5Awdk9DnlGzcmetfBj9svwvoEfw9Fh8L75D4BbVW8PmfxOsuEvCxdbk/ZAZdrsxXYYwBgYPJOso2djFS5pHmnxD/a9Y+N4pT4TKvZfC5/hruGpcsXilX7b/quxmz5X+z9/njeENCJbsteFf2908D2vw3i0/wAIatrkng3U5LyG88VeI1vrtLSayezn0+znjtIntYSkgdRl9rRxnB2gVfIxHVfCj9oTR/EGhfGzxFrXivxBbabD8ONS8MafpXjnxn/bWo31/qMybGs0aGH5AIVEoRDtAjY5ycTJPRAek2v7XGjfFLTr3xLd+BZbPxZ4qs9Mg1zU7LXHSJmtJoXka3i8omFpPs8a53ts2KRk7i3HLQ6o6nFftQfGmD4t6J4dsjot1BdaHa3cL6tqmoJf39+khUoJZBBFuEWCBuBPznnOSc1K8kEoWV7nOftP/G6e6+Evwu+HR1nRPEes2EK6z4n1rQbuO6jvbsIbWxSSZQN80NlHGkjZOS2M5TJ9CMU7s4Jy6Hong/8AaG03UvCnw717UfCc8viTwVa2FhY6jDq3l21xbWtyJIxJAYidxXcm4SDJbd2Cjx600p3fQ9WjGUo8vc39a/a40x9VspdI8GT2scPjhfHFyJ9Z8/7TclXEkSsIFEaHKBTtYjYSd27jeMlJXRlOLTsZHwG+O9l8ObXUrG60bUfEFvfSTvPpVxqyjSLhZERV82ze3cF0ZNwkRkY/dPHW7uJMdz0u5/aStdWt57qXw7NB4kvPDsXhy81VdRUwyW6uplbyDBw8iqFzuIXggdcq5pynlnxs+Lkfxsh0qyOj6vbT+H7m5tm1a9vU1W5uIpfKlVZJFiify48nYDvPztz66p6GLXM7M8ju9JuNNZ3DC4t1ODInBTjOHXqp5HWkxWscJeXKWccEsr+XFGrM0n90cAn8iaxOxrW5maTo3hjxXpsc+p+II9Ekku3kv7lt/wBpjt3bYiCPaUZYRCGLhgxN0EAbYSu9KN2ctWXQ7D4b+DfA9laadLHrtxcQrpxubt2mjiKTHTkuhAqlCfnuWe3DfME8kk58xQtTepMErmb8cfBPwp0XQbltI8Yya54kttTvIPtlsmw39strbNBP5MjKsSLOs8PlhjI4l89dyKsbdFNvlIkvePJdY0bQIdASW0Mh1JbGGeVBfwyBJmlKshXClsoVfCZMZ+Vw3LDXUzOp+IHhTwHF4n8RDwzrMR0dbvVWsC9+fLFvE5Nq6jy3lYSKTCEPzEoJWdI2OC7Gew/BbTvCkvgdTNq7WEllbtJDb+fHKb2QszyDf/y7hFySJR0B54JPn1F7x00/hOqtNN8C+JPEul2+t3N7Dos8rQz3lldxSMEM8cbcKjspWNpWyVYOY/lA3fLktCmuZWZ5v4j+C3w7tYGOm6trC3zRZSKfYAG2xE4JXMhWRpYdqAFjEZvljdBW8a846IzeHjJanoun2Xw/8NpfWl/rs7aJpdpKLW7WZAdUljgdol8rYTbGVlBHmn5N3lsC3I8mcOebb6noQmoRsi5ZW3wx1LTlF1rRtriO/v1W6F2kck9rHDE9riNhtIkZZUDjAVn3NlQBXRCMoKxhJqTKGky+DrO1ll/tKc6l9rvrcWcEqyeVHGkXkSMdg3q7O/zLt4hPyjcCul2LlXQ7nRtP8PSPfyXepPYxxKpiR5Y5mAMbMzZT5ZBvCR/KQf3ocgBGWrQPQ87v7TRdRknu7a4ni3xXMsbyXsUQ3J/qx5YUuGwoQKM7ywO9VVmrQ5m9Sp4d1+41C6MF3M00gi2xTiLfKoAHy8DLjAyQ2STkg5xSZUdXqeF/EHUJBFbaZAN013tUDHzcNnj3yF/I1nCPc2bscZc+FdcnuZo1sjtA2IwIVSo4yNx78k/U13wskkck7uR6j4N0p9M02RJSN8h24HYDgVzVHubQjpc8q8czLL4ovmUYG4cH6CuuirQRhPcoaD4evvE+otZadD59wltcXbLvVMRQQvNK2WIHyxxu3XnGBk4FdF0tyDuT+zX8SxrP9kHwneLqf2iW2+zs8YO6MxiRsl8BAZoh5h+TLY3ZGKLoZo6T8JvEGp/B/VNXj0/z7Wx1Y27zxTRsFlNqJ+zZIESSsxAIUL82M4rjn8R0weljmtX8DeJoNLt7loUk04wNcJLHextGmILeVgTvwrbLq2Uofm3yLHjzBsFJJ7oJOy0NvQvg98SVhvbrSYD5ds7o0llrFsRMUnihJhKzfv186eJMx7hubHJFVaHQy53syy3hP4l6LoFhfTST6Pp121l9je8u47aGUXUEk0MgldhGqbEBJZhtMiAgE0WgCn3OG8U6LrnhfUol1m1m03ULmFb3ypGCybJMkMyg5Qn0ODjBwMiqSJv1IU8Q6ha2kQjvbhUJPyLMwHvxmjlRalZXPR/hJqbafqV5vjMn2+I2QkJ3bQyksfwKpz6E1yVl1RstEd0LYQqkYbIQBRke1Zowe5NFO1rPHKhKSIwKsDyD2NUNaHm1+ou/iJbAxj/Q7QyE4654H5F6TNrHQu5I4prUmxo6ZlvLXHbP61DNVtY8R8aQyDxNqOImC+Zwdpx0FdtKSUUjjnuZFjqV1pkzy2lzLazNFJCzwuUYxyIY5EJH8LIzKR0IYg8Gui6ehBdvfFeu6lHcR3mtahdrcTy3MwuLp5PMllKGWRsnlnMURZjyxjTJO0U9FoM6/wAKeKtZg8Ca1DBqt9B5F7aXKeXcuuyXe22QEHIZcNgjkbjjrXLUVpm0HochqHinUL6Gyi8020NrZLYxxQEqPKEhlIbnLbpWZzk8E4GAFA1SE3cD4s1uSwnsn1i+a0uPM86A3LlJd7xu+5c4bc8MTnOctGhOSow9DLqXbn4g6/f2F9bXmp3F615cWtzLdXUzyXG+3jkjhxITuwqSsMZ7LjG0U9BGTdareamIFu7qa6W3Ro4RM5fylLtIVUnoC7u2PV2PUmhIBJyPssCjGQWP8qdgPWPhzbl7vTkGOJ5pGOf4VjViM1xVux2LY76SUBuozmsVuYu1yewsjql0sW7y4sFpJeyIOrH/AD1Iq7Ajx2x1mefxvLNdRxqrxBFaN8rGmMjJOM5xyfWs29Lo1vrY6ZNcsp7sW0UwkcxtJuTlcLjPP401sBWuPiLp+jzW3lBrvep5B2BT0wcjP6U1FsaZnxeONS1aG5ubS0sHijcD5mbcfUYPt34q72Znypm34b13SfFSShtPjjnj4eOSNSM5xwf8QK05mHIjXfwTod4MvpdqfcJt/lRzyJ5DG8U+FNP0Hwbq/wDZ9uLbeI5ZMOzbtrfL1Jx940uZyd2Uo2R4nJ98n1rpWxkhnakOwhJNAWRInAFaIzHyNlVHYA4pvYaPVPBl/Pa3KpHazSwW4MgeIAkmQqmDkjvt+gJNcM7vc6paLQ9AtWEkoa9SfT4WyyGaMbnHsAxrFbmNurEl8SXOoBrPwxp7C0jYfatQvISRKQT8o65xnOOB64xk9HKktWZc8r6I8P0iM28F8LwKts2WRDHvjD4znaTWF0dXLZlBbryo1up01BWZcRSbx5ZA44BXoOOAatIkZa+ILu28yVRHEXjMfmCMjcM5IyKu1h3YyyNnqkpjujJbzyMcSLjy8+rA8/kaHzR1iFrl2S51LT28iae2ntpDsV5wrIR65xkVKUXq9x2a3Oi0LxfdaBbup1q0mThVidXlVFHQrjG3jjnI46U+UDfXxHfeL/C+vZs/KsooiFuSw+8NrYJ7np0A+lGiHY8pvUhRYUiBEiKRJns2Tx+VbQ2M5FTrzVkiDGeaa3EyTcMVoZi9RxQ9ho9v+EtuL3UCJCfKWJmdVYru424OD/tGvPqaM6uU9es9E09CGW0Rtv8AfJb+dYp6l2tuaykAALgAdAOKT3HZPY+J5L8XS7Jr26ZO6lQQf/Hq6OWRneBee/0iZLdJJNRkSJQAjqhUfhmnZon3SrmzDMIr67jiJ+75Q/8AisUnOptYajDqxjxaYqnYbuQ+p2r/AI1KlVe5fLTFht7Dbho5mY9MygAf+O0c07j5Idzb0C1s4nkP2WOY7cZuFEgH0B4/SsqkpdzSNOJ6Tpdm8XgS+kkfJuIpJQnPC4wMfgAaS33IPGNRiCMzBcEyMN3rg13w2OeoigK1ZCAgUkMKYnYmiGVzQ9ibanvHwOjJtbyYAOwCx/N6H/661xT7HVFnr0byIBtCj2xWFmbXRZSU7stsH0FPlYro+F89a7jjEUEGluNEhYrRZF2JFfPtRZAhQ5U9aXKVfU6bwlBLqN4lvEMtI2Dj06n9K5qi1NYy0ueq6jqMscDab9nWASR+QihTtwVx8pJGSPcY460GF2eT614O1aG7nH2SSQq5DKi5Ze/KjJH8q6ISSE/eRztzZy2kpjlQxyDqjAgj8DW6dzLYhwaZQoRicAE0C3NrRPCur642ywsJ7oE43Ih2j8egqW0NJrU9X+GF+nhTRbmO5m/etLkNGQF2gDHLFcjJPIyDXDLmbujdStudvbfETTpWC/2rDnJG0yJ26/xUrS7GnNE0bXxvp8+duq2zkDcQCpwPfGfWpfMugNx7nyERsYr1ruOQKkBQce9O4CE5ouA5WzxTHc7vwJJp2mxpNfxTtJdN5MRMJ8oDPJzjnn06YNZSVy1LQ6iDxnbyXstoEuY4vKaRZJnXDYYg4LNjr0JI6VPKRcmuvitp8NjZ71nuJQnNuzgA4P8AEwBz0x1Occ03BvYpOxzepeJo9WuTfw2mkeXI+37HcQIzphQMltgYgnJ+99KWsdAujZl0Oz1LSkvtM0mwUzxCRYZIT69AQ2cdecdvemprqJrQ6rSbHw7pml2sWp6TG9zs3SPFaCSMN6D5Sf0z9apyXczj5kn/AAkGnaXrNxJbvcHTPJAgsI7QxrG/G5gWwefoBz071ndF2ZjXOsi8vLqS5YtBMwJjRWfYMcEkLgnvnHp6Cs/aMfIi7B4a0W/UbDJERwEI2L9AMDjtx9PWrVaSL9ki7D4PtbOArFeLCgIJMyq6/iD/AJ6dgBTdaTJ9jE+buTW1ySRIZGUsEYgdTikAiqXYKvUnAoEK8bxMQ6lSOxoACo8lW53EnP6Y/rVIY/LtEFYJsBwMgAn8eppiL8Ks87RJd/ZouWZ4gwUe2KkNTpNNutLXR7n7QlvOFVE2ncrOQDzznB6n6saiTd7I0ik9WVLHVNJvbwxz6ckVko+RQ+CuSMknqe/ek01qP3W7G3H41MOpNEptW0yIjCxghmTOOM9CBzis3T6kqV2ddFr+gymF7fVI4GkTeF39AOxHY+1ZNSRuuUq6r420/RlDfa4dSkfjaoHHuc59hTjCUtROSudJp16NU0u3vI7K2lhmXcCPkbryfxPpWTlbdGiinsyLUb200hEe5i+xRluCs+0MfTHf8KcXzbCdo7jLXxBpd3cZivV+1HGOFkbH4c/4VbjJEppnzwgwC+RwQMd67DmJ43LgLvOT0Cg5pPTUpIe4gSPY8ckcw6g9DU3uDViNMysqK+4k9HwBTvYm1yR4pLF8homyM/3sfnVX0KtZ2NCe3jsoY5mPm3b4KJgHH1AqOaTdi2klcqXE11LGJpQqo56gAfpWqaMmmRW8UEr4nnMSkj5wueO9JtvcNjRv4dPtUCWfnyufuyzIAH+gobbEtNSotiIVhmk/exH78Y4YUr3C1tRDL513i2GzPAJxwPeqSfUeltCezs3IM8iRzW7tsaXAYr7+1K9hI09P1/VLaeGz0+6+yIuWQsBg8dx6cVDipblRk4vQTV9cu9TK2utzm4aNsQzJgeVn7xwOvQcH0pKChsXKbluZ8zNouswyRXJnWF1kSUArkZzWlrozcuV6FYNdwWQClDb5PBwevWstGV7xJaWUt7A8ix7I4hneTgUmxpX3LiX9tHDGZbgyXCHOMFh147VnZ3ujXmSVjZuvF9nqekS29xGpkcBQoHHbnPbFJRad2K8TASzs5I5NjFZeNjtKCB+FaX1JaXQU6XCLNpnlka4Y/KVxsY/lVXFZEUFlBGq/bHkJY4VImHHqSSKrmJsJqcFnZTMtpKtzERwXJDL9cYGatN9SGtS9/aVpKkBFzKLiMA+Yw4XHYCoauaxaGW2oXd9qUMsZjJiPyvKnGcUbE83Mxs+q31vI7reR7uc7QAT+lCs9wlfdFMa1cCZ5fkLtwfl607IzvIjjuEu7xGvHYR4wzIOcf/rq7iJPKgbzVjvRHFnI3ocn8qRRAglLGOMmZF53bTx7072DXof0kn9lv4MEYPwj8C49P+Easv8A41WBY9f2Yvg6sZQfCfwOEP8ACPDlnj/0XQBF/wAMsfBb/okPgP8A8Jqy/wDjVACj9lr4ML0+EXgQfTw1Zf8AxqgBP+GWPgv/ANEi8Cf+E1Zf/GqAJP8Ahl/4NmNY/wDhU3gby15C/wDCN2eB9P3VADT+y58GSMH4SeBcf9i1Zf8AxqgBp/ZY+C5/5pF4E/8ACasv/jVO7EJ/wyv8F/8AokXgT/wmbL/41Rdi5SRP2X/g2ilV+E3gZVPYeG7MD/0VSGlYZ/wyz8GM/wDJIvAh/wC5asv/AI1Rcdg/4ZZ+C/8A0SHwH/4TVl/8aouwsg/4ZY+C/wD0SLwJ/wCEzZf/ABqi7JsH/DLPwYzz8IvAn/hNWX/xqndjJYf2Y/g7bBhF8J/A8QYYYJ4csxn6/u6VxnplABQAUAFABQAUAFABQAUAFABQAUAFABQAUAf/2Q==",
            "timing": 900,
            "timestamp": 1011787212134
          },
          {
            "data": "data:image/jpeg;base64,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",
            "timestamp": 1011787512134,
            "timing": 1200
          },
          {
            "timing": 1500,
            "timestamp": 1011787812134,
            "data": "data:image/jpeg;base64,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"
          },
          {
            "timing": 1800,
            "timestamp": 1011788112134,
            "data": "data:image/jpeg;base64,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"
          },
          {
            "data": "data:image/jpeg;base64,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",
            "timing": 2100,
            "timestamp": 1011788412134
          },
          {
            "data": "data:image/jpeg;base64,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",
            "timing": 2400,
            "timestamp": 1011788712134
          },
          {
            "timing": 2700,
            "timestamp": 1011789012134,
            "data": "data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRQBAwQEBQQFCQUFCRQNCw0UFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFP/AABEIANUAeAMBEQACEQEDEQH/xAGiAAABBQEBAQEBAQAAAAAAAAAAAQIDBAUGBwgJCgsQAAIBAwMCBAMFBQQEAAABfQECAwAEEQUSITFBBhNRYQcicRQygZGhCCNCscEVUtHwJDNicoIJChYXGBkaJSYnKCkqNDU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6g4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2drh4uPk5ebn6Onq8fLz9PX29/j5+gEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoLEQACAQIEBAMEBwUEBAABAncAAQIDEQQFITEGEkFRB2FxEyIygQgUQpGhscEJIzNS8BVictEKFiQ04SXxFxgZGiYnKCkqNTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqCg4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2dri4+Tl5ufo6ery8/T19vf4+fr/2gAMAwEAAhEDEQA/APiKJXVR0rIuxc3fKABk0FM7f4KfDO7+MfxP0XwdaXsOly6iJ2+2XCM6RLFBJMxKryfliIwO5pokg+J37M/2t/Dfijwh4y07xf4Q1vxDB4Sk1SO1ns5LDUnVXWKWCVQzKYmDh4yw+V1O0hd3RDY5pq54j8Q/AN74K+J3iTwUG/tTU9E1W70p2tI2PnvBK8bOi/ewdhPriupPQzaOVSAyOECs0jEBVUZJPpSbRNr6Hrv7OP7PA+Pfi3xTpOoeJIvBtj4a0C68Q6lf3VjJcmK3t3iWQeUhDFgJd2BzhSACSBQ5W2LSsX/jD+y1cfDv4e6b8R/C3jDRfiP8N7+9bTU1zR/MgmtLkIHEV3aygPCzDcQPm4ALbd6blzXdiZLS6PIX0TUFt7OZ7C5WO9BFrI0TBZ8NtOw4+bDccZ54p3Isz7d8Z/s2ad8GvCQsvGXxD0jTPiFb2MV03hG1tZ7tk3qGEUl1GDHHLjPynj7pDFXVjwy1Z3xdkeSfYJo4IJ3ikEM5IikK4WQjrtJ4OPapsDdz074qfA6L4T2Wl2l/4ns77xlOIHvfDFpbytLYpNGZIy0+PKc42BlVsguMbh8xYjnviz4K0XwF42vtA0LxFJ4pt7I+VNqJ09rNDKM7lRWZiyjgbuATnGRhigOPEZPtU2KHKrZ4osgOPjuP3eduKVyrFq0O993rTGfQn7DDKP2pPCDhVdki1HCOu5XJ0+5AUjvkkDFAmSfETxL/AMSn4e3njzw/pPwm8SaR4902SDQNOL6VBfWBXdcajdaa7bY3jaNY/tn/AC0BMZz5II6InNPcz/Gmi/EbRPiL+0m/w8h1vSfiJcePYtStY9GkkttXvtEkn1QvJaohE09s0r2bv5QZCBE54QEbXVkiOrMe4vvE0/xC+Ji+DNSu7n4zDwl4dhafQbtpdQnuY4LIasttJAxdrsSL++2MXIS8JyNwoA+ivAmi+KPGnxEj0jULmbWfHOs/s0XVi7X14HnuL2XUJEEck0jf6wO2xt7fKwIYjBpbJDszzX4c+HNM/ZF+E9l4A+L2o6C+u+OfHXh+e/8ACs19BeLoul2l5FNNd3m0vEolVdhXOGjZSWbDqib5ndCSsrM7z9qH42a98MNa1rWvEngHVfFngK/8ZaDq+geIdQ8V2l/pUUVpMLqL+yrNbVDAJrRJIpCrPjedzMSd6Sv6g9ir+0T+zR4l8V/EXxP8SdA1fSPEXw41a5/tE+Ko9XtzBao7YeNv3mT5bfIBGGyNuOSVXna1Ojoey/ELSte8DfBX4qJceJNe8U3VlDoer6Fr2p+IIL7zzHcIz31jbRgvZxozA5LtuG3nhqaA0J/G17rP7Xnj3Q7vWZrme38HMvheyk1CK2ZNQntLQkWkkqssU7gy4bB4LkgqCKYHyt+1NrGv6rrfhLSvEvhvU9H17S9GWFrjWdZi1S/vYDLI0TTPHGm1l+cYcbyCCc5DGAPFmsZYRGXT/WjKgcsR9OtAWuNmRYo9qlWmZcnGCAPSuWrUvKyO+nSVrs85Ecjj0xW1jlNO0jZIsnriqAsWExWbb6/rQB5b41V18QXCE4VcYXPAzzXZDY4ZtuTOdK46ADtkdT9fWttkSmzc8H+JtP8AC+sPeap4W0nxfE0RRbTWZbyOONiwPmKbW4gfcMEYLFcMflzghW0GnZmt8Ufi/rHxX1fR7vUbaw0y10TSoNE0nTdMhZILKyh3eXCpdnkfl3YtI7sS5yTxilFRVhu5ykV8JsJIuTn7w/z7ChOxi0W5kjXPA3etGm4r2R7/AKKgOk2gIyPKXp06Vwvc9FLQ0Mf/AKqBDreFp5NqY6ck9gKVwL0bqqFbdSkYxumY8ngdfy/meKzcuVXLjBydkRXOqw28Dqsu2QjJbjOcVyyqSex2Kmo/Ecc/ifT5rK8nDMXtPnmIHIQnG73GTj8KnkbV2UpRi7IzrNWMQJHU12HGXY1AHJ47CgCS2th5vmAY9zQB5V41GfE17g5HHI+ldsNkefNanNS/erUlaEaxvcTJFGNzuQqjOOT/ACoLWpqan4P1zRpr6K90m9tpdPVmvo5YGVrTbMYCJhj92RKNhDY+YgdSMu6KZPa+BfEkmqfYF8Pas999oW0+yrYymXzmUssWzbneQCQuM4GcUjFjp/Cut2tqt1caPqFvbGBLoTS2johhdzGkmSMbWcFQ3QkEdaLktdD6BttOu9Kt4rO+tpbO8gAjlt54yjxsOCGU8g+xrhe56S2LEMTSuqgH5jjOKVwsW5lCt9nt06EZbjLH3oe1xJXdjh/F3i1o1e2tpBHaRLh5uhPrXKr1Wd+lNHls/jCJrxsCSVAf9YT+oFehTwzS1OKpX6LUn8B6h9mm1ydpSm+EbflyGPmA7T9QD+VXXj7sbGdFq7uerRWaDgKMVxl8xZitUXA2gmgq5YS0+YjAAx0poLnjnjm28nxNdr0+6f0rtj8Jwz3OWuFGSRVoz3GW0ptJo5lALIwYZ6cVdgvY7/w58ede8K6a1rYWenJO1iLBr3ZKJm4uozKcSBfNMF7PBu28IQwAlHmVHKXzEGqfF+fV4Psj+GtCttO+0xS/YrWO4ii8lBEDbnbNu2uYI2ebPnswJM3zNlqAnIk0/wCMOrWEtxNHY2InaCyhimQzo1uLa3W3VkKyg72iXaWbJUktH5bYIrlsZuR7P9tXV1iuYrO206F4kEdnZIVhhUDAVdxLEAYGWJJ6kkkk8DWp6C2J1QWtu0pBDsdqN6DHJqWO9jmT8R9ANzLYrqCCdgUSbkRE9OH6e2envVzo1OS6RVGcXOzPI/HupXSymw8to0PzSMB154B/LNPCU18ReJqW0RxBGw16vmcN7o7Xw7OmleANXne286TULiK3hkI/1PlneTn/AGgxA/3TXLNXlYtaHsaDrXmmpYjXLD1oKLMLAu4x04zVbAjx74jrt8V3OehVT/47XXHscc9zjZuGIPStTJ6FaVuMDpTEei+AvCui6/4LvVuU0GO/nnmhOoajrq2l1aMI4zaCGCSSNCkszMkkj+aFQMxEATzHlM1SuUdN8F6KLS6+0XgvL+20m8u5o4NVs4IYpo5vLTbI7Hz8gbhDEC7grsOCWXS7QmtDs/GHwk8I6H4f1i90nxTaahJawQSxxNqlsXLtcmERoqBjcM8QS5O3YsCuYnd5Fw0uTehm0rXO40SHOm2cacs0aAc1xPQ71sT67pv9pafeWkchgklge2EhGGXKkZOPc5/L0rNSV1cq19D55uvhZ4kt7iaOWxAiiUs9wXHlbR3z/Tr7V6ftIWsc3I0zPfxHcvdltSBmZjlmwM04w5VZEyvN3K+oRW93GZbcjP8AdA5/EVd7bkLQ9G1/w+dD+FEUe+KeaK5RnaPP7sqzqVbsSskkvzDqrJnoMc696Vzd6HZLOwXJ6+wrzrnRYs2twDjOaQywJ1Eny53GgVro8b+ILM3iu5zk4C8+vyiuyn8Jy1l+8djk7jcW6V0RMmQEDDdcgZoYt2dHf/DbxHY3BjWwXUiqwM8mj3EWoRxGZisSSPbs6pIzDaI2IfPBUGiLG9Bknw88TwWEd9J4e1OOzae4tvPa0cKJYI1lnQnHBSNg7A9F5PQ1pdE9C/Z+BPFEmjjVIfD2py6e0tvAlwtpIUd5zIsIU4+YuYpQuM5KEdaV0Qe86HHLDbW6vADLDCC8MowBhTwR2NedLc9OPwo0oUyO+0dMmotco5L4k61H/wAInLFaTq5mmWGQL6DLEfmBVwj7xlUlaJ4bqVqrgjGeOSa9FO5w7aj/AAZ4fuL/AFWS7tXeJ7BftEbxuFYSLlkIJ6AbSxP+zgfMy5Jy5DeLurns91410i28L3SaxbLDF5Ato4NpZJFC7UQADjgAfhnNYXbd0MsiMemfauCx1jonjXhk2/UVGxVrlkQqSGQjmkykrHjPjif7L4pvldVcZUj/AL5FehTWiOCo/eMK0KX92qsoUHtnvW8rpGN7s05dGjs33gFXGCD6HrWak3uNpLY7/T/2gbrwg/h/+x/Cnh7T49B1eLXNNhjN6ywXYe3aV/nuSXEws7dXVyQBH+7EZZmOtkKTZP4d/ab16x1fQdRuvDvhrWG0L7IbCHUrSV1hlt7bT4ElDLKGDldKtSxDDP71eEkZCcqJuzN0v42avottcwW2l6ULe7W2W9hdZ2F35NtdWpLEy5Tfb3s8REZQKCpjEbKGD5UJu57Fp97N4gubzUbgILi8ia4k254YkE8kkn8ST9a8yT1PTh8KCZVhiZiQFCkk0kW3oeReOL+3g8P2yIyBHvZpgcgZyqqPr90100lfY4qrPMFnl1a5S0tVMsr5IGQBgDJJJ4AABJJ4ABJ4Fd1uVXOdQd9WepaTpsHh7SJdOtlJuQkf2+YIQS5ZmEeWAcYwNynABVQV3IWPHNubOuKSVjj/ABn4mhu7drSKJTFC2Fc4Id8ckf7vT64ranTe5lLex6U2vQRXTRMjja2M4rzeZI7bG3iORUGBhuh9aTaY0nYijvYUujCeGTn60nYpJnh3xDnVvFt7tXZkr1PX5RzXo0vhTOCabdznVmeKVXU4YHIIrZ6mZsS+KpbiNUdfujrip5UIz7i8FxnKj86aViXqT6YUkkUYICnJNDYFmdgsbe+aE3qJ2SPpbw1MEtbMs/lo8IRm9AVx/OvNluepFWikaWoWxmtZoMoHZSjLKDjBGKhtLqUk2ef/ABj8Jz33h/QodNs98on8gJDGTu3/AHeQMAAhsknuM100KkY3uzmrQlfRGd4Q+G8egKRBJDdap/y0uQuVt2DA7Vz/ABKUBDDBUk9SBtJ1nI0jS7mX4zuZ/B9vNpNtFGU1GICS4iPIIbOxP9rgknsD1ya0pe+7yMppx0R5LqDSvPtYBSowIwSQg9Oa74djBO+rPaZcSyPLNjJGTivAep6FzTtLyO+0Nkhl+aEEemMdKe25a1Q/RtJEkXnzyhQcnr/M0Cs+pyBlt4NZ1CM3Dyaarvc3TMAwIC7SMd/ulcHPb1rJuU5qKLUVGLkzy+9njnvJ5YohBE8jMkQOdgJ4X8Ole4r2VzynuV6YhFY7hQOxtafHi2GOSx5/Ope5m9xb5sJgMD7VSWhm3fQ+lNJ/5BFmP+mS8fhXmy0keutUmaMCvJaOMB1V1ZiX2lAehA78E557e+K8TFRcZcz2PRw7vokYo1nw/FqenCyhgurl5dsZmDMrsVYAcjj5snnkqrcZow1J1PeWxVaqoe7Lch8ffCvUdW0m5dfEhW3gj8yW1S1IE5GDhn3liOBgYwMDjNevSko7nn1eZ6nLaV8A9VSxgubC+S2tbtAZfJmFw8ikZG1Xjj2cH+8evtXX7eK0MHTk1cxNY+FTWljK1rHII4GKSS3G0Ozg4OeTzkHvWsaq3OecHc3LlF8qTPQLXnpHWWP2c/CsHjj4r+HPDV9LcJp2sa9aadcNbsBIsUs6RuUJBAYKxxkEZ7VU1ewot6n1b4v/AGVvC8OkeAbi70jxX4JPiT4gW/hB9D1i9imnuLORgDeQs1vGUPDfKyuDnPTrCjqi9z5q8HfsveMfiz4Qubnw9eeG7B9Q1KTTtPs9c1uC0vNVmiCP9ltY5MF5MSREklV5Xmnh43lzsqtP93yoxrL9iP4lv8Pr7xXq0OkeGPs+n3urRaDr2oLaaxeWlortcSw2bDzCEEbfeC54IyCCfSc1c8/l0OK+DXwI1v41Ta1JYanofh3SNGhjl1DXfE2oLYafbNIxWGN5mBAeQhgi99jelXJqIlG57h8S/wBgDWI/jn468L+BtTsbDwloWqWmiWGreNdWhtG1DUZ7SOdLKJ9irNcNvOEVRxtz1yYU9NS+U8g+G/wI8Y+OPiVrXgK3tLbTdZ0P7UdZm1O5SG10iK1YrczXU2SscUbDDOCRyAMkgFyaWrMnG7sdr4b/AGM/FHj/AMWa54b8PeNvh1qusWFx9mtLW38V27Pq7+Qs2LNesoCsQWIVdyuuco2K50kZqGp9TaH+y/bXvwO+HN9pN5b63408ZLI9tFHrtvDb2cUeXbdEYy0gSKOXzWDp5TgJhjwfOn3PTg9LHB/Fz4Yaj4H1zR/s1vZHw3fadutNU0vU11G11OSIFZ5VkHGfMDAxgfuy6rluGbxcXD284U+h6VCoqVOU+pF4q/Y98ex/EHwzafa/DUepxyvf6xpqaxF9o0WAQtI9zfKOIIghTLnOS6DJLAV7lCnGjR9mePVnKtU52evD9nTxDDf6lFd3nhy202ztbW+bVp9XiSyktriVoopllPylSyOOdpOBgHIzy8jOtzTPNPiB4Yuvhp4sbw7ez2n2i2ki8xraYPE6Oqujow6qyOrA+jDIB4pNWZHMjwX4r2MkPiG9FpcmC2ulWXETblc45YgHAOc/lmu6jJNbHFVXvaFK5tSIJdo3FlIGOc1znWy38Etck+HHxF0HxLJYPdDSNXttTNszGPzhFMshQMQcZ24zg9aqfQmKseyeKP2ufD9rq/gnwn4O8EXmn6Zofjq18dXsuq6z5895cRAs0SgRBYU2tt3AMTgcZU7spOzVjZR0ucvpv7Xnw08I69Yxv8LtY1eLwb4mm8ReDftXifYLWSSC3jMNztg+eMS24uFx8wKJGSVLl/QjStHQ43J3PZbf466B8YPgVf8AxQ+I+r+B7X4gReBPEXhm3aDxYY9TnFws0dtGdIEHDlm2hvNI2StIwPyCMaa0C90fFvwc+LnhTwh4K8Z+DfHHhW98TeHPEEtjfqdL1EWN1bXdoZvKKu0ci7HW4ljfcjEAgrhgDWrjfUlM+jrn/gpn/bN/8QUuPDHiHQNM8Ta3b+IrZ/Cvif7Ff2twllDaSQPO1u6yQSLboceWpQlvvHaVj2Y+Y8Q+DH7S9v8ADj4y+NvE+r6HdeJfD/jaz1LSdasLrUj9vazvZA8pW6CDdMCqkuUG75vubsro4pq1yG0tWeyfB/8Ab38KfACwOn+Bvhdd2kEOsx6jHNN4jK3F7ALdIZIbx1g/egkSSqq7I0kaM7GEbeZLjz9TKM0tkdb8Kf2k5/Cuk/CCG18OfbpPBdtqMDj7e8JvUvmfftZEzEUWUhSN3IB+WvMr1FTi2z06MeZi/Gr4vXvj/WtOaxOtva6PE6W8/iDVBfzSFv3kkgIRAgPyphc52Z615vNecEdTXLCVjt7z9q/wnd+N9e8Wv8OrmfVPFumPo/iVH1orHJaPCsUiWwWIGNmMcblm3YwVAGdw9dSuee9zlPHH7Sdl4g8E+IPCOleF59O0e+0TSdBtJLnUvOmijsbyS5E0p8sCR5DKwIG0L2yOKYjzTx74vX4geJYtWNmbErp9jY+SZvN/49rWK335wPveVuxjjdjJxkyLcwtQ0ddXskQAGSMkgE9Qeo+vA/L3qouwOPMczLdRwW7TtFGUXH3R834f/rrPmidSjYv+HvAXi74u6xeaD4ZtdPaK106bUdYvdQ1AWVvptiCqNPNLI6qAN+cDc3yk7cAmmtdTKTs7HQeAP2L/AB54gFld6bFpEy6w93b6M1n4psw+qm1lYXH2ECXdKsZjYllONpUgkMQHa429LHMfED9jv4htYah4ljtdGWGHw2niz7E+t2Y1G6005L3a2ofeERfvHavIIGW4rrhNKOpzSV2cdqX7KHxAsfFnhjwnb22lan4w15EePw7ZatbvfWm6D7QpuE3jyl8n94XJ2gdSDxWqnEnl7nQ6P+yd4hsIPEV3qujnxRo8XhHVPEela14X1+0+wutnIkc05ldX82OF2KSQIFkYsu0gHcRyQ7Ht9p+xV4h07RhJJ4N0qK7ZrRbnSDqFu2o2IumSO3M0bP5ke93UDOGUnLBeTXE5SudCjGx5/wDFb4Sz/BzVIrHVPEEsb7pop4NJ8QRTtZSRELJHMiBmRlY4+brtJUtgkVz9DN00kN8U/Cfxd8MNR8RxeJofEGmnw/eWmn3rTa7DMouLqBriCNCgIkJhVnO0kKB82CQKu7asjN6aHqfgz4IeLrzQdB1U3dpC2vNbnSNM1XV4Pt97HPIIopktywbymdiNxx93d90Zrz6zu0mehSuk2T3XwW8aysIbWxUSN4k/4RPbDdxxD+0VXPk/fPGP4/uds0qcLScgnLoSr8DPFL6JqeqXF5pZ0uwvF05rqTxDamGa6MCztBE4kKu6o4yAcZBUEsMV0owN+y/Zh1+08O2+rXOkWvmTWseoHT/tkMt9HaSsqxzmEEuEJdQeMqc7gAM0tRyUeh578ZPhnN8KvEEem3dxp7XLtJ5trZ30dxJayKE3RyKpyhG7HPBIIBO04pEPTc4y0n2t8p5olsETh7iMtYxxjlnZcfz/AKVz9Ds2Zu/Cz47xfBzxB8RtL1jQpvEvhnxjoX9jahYW90LSWNdgZJ45fKlw6bpCFKY+YE5Awdk9DnlGzcmetfBj9svwvoEfw9Fh8L75D4BbVW8PmfxOsuEvCxdbk/ZAZdrsxXYYwBgYPJOso2djFS5pHmnxD/a9Y+N4pT4TKvZfC5/hruGpcsXilX7b/quxmz5X+z9/njeENCJbsteFf2908D2vw3i0/wAIatrkng3U5LyG88VeI1vrtLSayezn0+znjtIntYSkgdRl9rRxnB2gVfIxHVfCj9oTR/EGhfGzxFrXivxBbabD8ONS8MafpXjnxn/bWo31/qMybGs0aGH5AIVEoRDtAjY5ycTJPRAek2v7XGjfFLTr3xLd+BZbPxZ4qs9Mg1zU7LXHSJmtJoXka3i8omFpPs8a53ts2KRk7i3HLQ6o6nFftQfGmD4t6J4dsjot1BdaHa3cL6tqmoJf39+khUoJZBBFuEWCBuBPznnOSc1K8kEoWV7nOftP/G6e6+Evwu+HR1nRPEes2EK6z4n1rQbuO6jvbsIbWxSSZQN80NlHGkjZOS2M5TJ9CMU7s4Jy6Hong/8AaG03UvCnw717UfCc8viTwVa2FhY6jDq3l21xbWtyJIxJAYidxXcm4SDJbd2Cjx600p3fQ9WjGUo8vc39a/a40x9VspdI8GT2scPjhfHFyJ9Z8/7TclXEkSsIFEaHKBTtYjYSd27jeMlJXRlOLTsZHwG+O9l8ObXUrG60bUfEFvfSTvPpVxqyjSLhZERV82ze3cF0ZNwkRkY/dPHW7uJMdz0u5/aStdWt57qXw7NB4kvPDsXhy81VdRUwyW6uplbyDBw8iqFzuIXggdcq5pynlnxs+Lkfxsh0qyOj6vbT+H7m5tm1a9vU1W5uIpfKlVZJFiify48nYDvPztz66p6GLXM7M8ju9JuNNZ3DC4t1ODInBTjOHXqp5HWkxWscJeXKWccEsr+XFGrM0n90cAn8iaxOxrW5maTo3hjxXpsc+p+II9Ekku3kv7lt/wBpjt3bYiCPaUZYRCGLhgxN0EAbYSu9KN2ctWXQ7D4b+DfA9laadLHrtxcQrpxubt2mjiKTHTkuhAqlCfnuWe3DfME8kk58xQtTepMErmb8cfBPwp0XQbltI8Yya54kttTvIPtlsmw39strbNBP5MjKsSLOs8PlhjI4l89dyKsbdFNvlIkvePJdY0bQIdASW0Mh1JbGGeVBfwyBJmlKshXClsoVfCZMZ+Vw3LDXUzOp+IHhTwHF4n8RDwzrMR0dbvVWsC9+fLFvE5Nq6jy3lYSKTCEPzEoJWdI2OC7Gew/BbTvCkvgdTNq7WEllbtJDb+fHKb2QszyDf/y7hFySJR0B54JPn1F7x00/hOqtNN8C+JPEul2+t3N7Dos8rQz3lldxSMEM8cbcKjspWNpWyVYOY/lA3fLktCmuZWZ5v4j+C3w7tYGOm6trC3zRZSKfYAG2xE4JXMhWRpYdqAFjEZvljdBW8a846IzeHjJanoun2Xw/8NpfWl/rs7aJpdpKLW7WZAdUljgdol8rYTbGVlBHmn5N3lsC3I8mcOebb6noQmoRsi5ZW3wx1LTlF1rRtriO/v1W6F2kck9rHDE9riNhtIkZZUDjAVn3NlQBXRCMoKxhJqTKGky+DrO1ll/tKc6l9rvrcWcEqyeVHGkXkSMdg3q7O/zLt4hPyjcCul2LlXQ7nRtP8PSPfyXepPYxxKpiR5Y5mAMbMzZT5ZBvCR/KQf3ocgBGWrQPQ87v7TRdRknu7a4ni3xXMsbyXsUQ3J/qx5YUuGwoQKM7ywO9VVmrQ5m9Sp4d1+41C6MF3M00gi2xTiLfKoAHy8DLjAyQ2STkg5xSZUdXqeF/EHUJBFbaZAN013tUDHzcNnj3yF/I1nCPc2bscZc+FdcnuZo1sjtA2IwIVSo4yNx78k/U13wskkck7uR6j4N0p9M02RJSN8h24HYDgVzVHubQjpc8q8czLL4ovmUYG4cH6CuuirQRhPcoaD4evvE+otZadD59wltcXbLvVMRQQvNK2WIHyxxu3XnGBk4FdF0tyDuT+zX8SxrP9kHwneLqf2iW2+zs8YO6MxiRsl8BAZoh5h+TLY3ZGKLoZo6T8JvEGp/B/VNXj0/z7Wx1Y27zxTRsFlNqJ+zZIESSsxAIUL82M4rjn8R0weljmtX8DeJoNLt7loUk04wNcJLHextGmILeVgTvwrbLq2Uofm3yLHjzBsFJJ7oJOy0NvQvg98SVhvbrSYD5ds7o0llrFsRMUnihJhKzfv186eJMx7hubHJFVaHQy53syy3hP4l6LoFhfTST6Pp121l9je8u47aGUXUEk0MgldhGqbEBJZhtMiAgE0WgCn3OG8U6LrnhfUol1m1m03ULmFb3ypGCybJMkMyg5Qn0ODjBwMiqSJv1IU8Q6ha2kQjvbhUJPyLMwHvxmjlRalZXPR/hJqbafqV5vjMn2+I2QkJ3bQyksfwKpz6E1yVl1RstEd0LYQqkYbIQBRke1Zowe5NFO1rPHKhKSIwKsDyD2NUNaHm1+ou/iJbAxj/Q7QyE4654H5F6TNrHQu5I4prUmxo6ZlvLXHbP61DNVtY8R8aQyDxNqOImC+Zwdpx0FdtKSUUjjnuZFjqV1pkzy2lzLazNFJCzwuUYxyIY5EJH8LIzKR0IYg8Gui6ehBdvfFeu6lHcR3mtahdrcTy3MwuLp5PMllKGWRsnlnMURZjyxjTJO0U9FoM6/wAKeKtZg8Ca1DBqt9B5F7aXKeXcuuyXe22QEHIZcNgjkbjjrXLUVpm0HochqHinUL6Gyi8020NrZLYxxQEqPKEhlIbnLbpWZzk8E4GAFA1SE3cD4s1uSwnsn1i+a0uPM86A3LlJd7xu+5c4bc8MTnOctGhOSow9DLqXbn4g6/f2F9bXmp3F615cWtzLdXUzyXG+3jkjhxITuwqSsMZ7LjG0U9BGTdareamIFu7qa6W3Ro4RM5fylLtIVUnoC7u2PV2PUmhIBJyPssCjGQWP8qdgPWPhzbl7vTkGOJ5pGOf4VjViM1xVux2LY76SUBuozmsVuYu1yewsjql0sW7y4sFpJeyIOrH/AD1Iq7Ajx2x1mefxvLNdRxqrxBFaN8rGmMjJOM5xyfWs29Lo1vrY6ZNcsp7sW0UwkcxtJuTlcLjPP401sBWuPiLp+jzW3lBrvep5B2BT0wcjP6U1FsaZnxeONS1aG5ubS0sHijcD5mbcfUYPt34q72Znypm34b13SfFSShtPjjnj4eOSNSM5xwf8QK05mHIjXfwTod4MvpdqfcJt/lRzyJ5DG8U+FNP0Hwbq/wDZ9uLbeI5ZMOzbtrfL1Jx940uZyd2Uo2R4nJ98n1rpWxkhnakOwhJNAWRInAFaIzHyNlVHYA4pvYaPVPBl/Pa3KpHazSwW4MgeIAkmQqmDkjvt+gJNcM7vc6paLQ9AtWEkoa9SfT4WyyGaMbnHsAxrFbmNurEl8SXOoBrPwxp7C0jYfatQvISRKQT8o65xnOOB64xk9HKktWZc8r6I8P0iM28F8LwKts2WRDHvjD4znaTWF0dXLZlBbryo1up01BWZcRSbx5ZA44BXoOOAatIkZa+ILu28yVRHEXjMfmCMjcM5IyKu1h3YyyNnqkpjujJbzyMcSLjy8+rA8/kaHzR1iFrl2S51LT28iae2ntpDsV5wrIR65xkVKUXq9x2a3Oi0LxfdaBbup1q0mThVidXlVFHQrjG3jjnI46U+UDfXxHfeL/C+vZs/KsooiFuSw+8NrYJ7np0A+lGiHY8pvUhRYUiBEiKRJns2Tx+VbQ2M5FTrzVkiDGeaa3EyTcMVoZi9RxQ9ho9v+EtuL3UCJCfKWJmdVYru424OD/tGvPqaM6uU9es9E09CGW0Rtv8AfJb+dYp6l2tuaykAALgAdAOKT3HZPY+J5L8XS7Jr26ZO6lQQf/Hq6OWRneBee/0iZLdJJNRkSJQAjqhUfhmnZon3SrmzDMIr67jiJ+75Q/8AisUnOptYajDqxjxaYqnYbuQ+p2r/AI1KlVe5fLTFht7Dbho5mY9MygAf+O0c07j5Idzb0C1s4nkP2WOY7cZuFEgH0B4/SsqkpdzSNOJ6Tpdm8XgS+kkfJuIpJQnPC4wMfgAaS33IPGNRiCMzBcEyMN3rg13w2OeoigK1ZCAgUkMKYnYmiGVzQ9ibanvHwOjJtbyYAOwCx/N6H/661xT7HVFnr0byIBtCj2xWFmbXRZSU7stsH0FPlYro+F89a7jjEUEGluNEhYrRZF2JFfPtRZAhQ5U9aXKVfU6bwlBLqN4lvEMtI2Dj06n9K5qi1NYy0ueq6jqMscDab9nWASR+QihTtwVx8pJGSPcY460GF2eT614O1aG7nH2SSQq5DKi5Ze/KjJH8q6ISSE/eRztzZy2kpjlQxyDqjAgj8DW6dzLYhwaZQoRicAE0C3NrRPCur642ywsJ7oE43Ih2j8egqW0NJrU9X+GF+nhTRbmO5m/etLkNGQF2gDHLFcjJPIyDXDLmbujdStudvbfETTpWC/2rDnJG0yJ26/xUrS7GnNE0bXxvp8+duq2zkDcQCpwPfGfWpfMugNx7nyERsYr1ruOQKkBQce9O4CE5ouA5WzxTHc7vwJJp2mxpNfxTtJdN5MRMJ8oDPJzjnn06YNZSVy1LQ6iDxnbyXstoEuY4vKaRZJnXDYYg4LNjr0JI6VPKRcmuvitp8NjZ71nuJQnNuzgA4P8AEwBz0x1Occ03BvYpOxzepeJo9WuTfw2mkeXI+37HcQIzphQMltgYgnJ+99KWsdAujZl0Oz1LSkvtM0mwUzxCRYZIT69AQ2cdecdvemprqJrQ6rSbHw7pml2sWp6TG9zs3SPFaCSMN6D5Sf0z9apyXczj5kn/AAkGnaXrNxJbvcHTPJAgsI7QxrG/G5gWwefoBz071ndF2ZjXOsi8vLqS5YtBMwJjRWfYMcEkLgnvnHp6Cs/aMfIi7B4a0W/UbDJERwEI2L9AMDjtx9PWrVaSL9ki7D4PtbOArFeLCgIJMyq6/iD/AJ6dgBTdaTJ9jE+buTW1ySRIZGUsEYgdTikAiqXYKvUnAoEK8bxMQ6lSOxoACo8lW53EnP6Y/rVIY/LtEFYJsBwMgAn8eppiL8Ks87RJd/ZouWZ4gwUe2KkNTpNNutLXR7n7QlvOFVE2ncrOQDzznB6n6saiTd7I0ik9WVLHVNJvbwxz6ckVko+RQ+CuSMknqe/ek01qP3W7G3H41MOpNEptW0yIjCxghmTOOM9CBzis3T6kqV2ddFr+gymF7fVI4GkTeF39AOxHY+1ZNSRuuUq6r420/RlDfa4dSkfjaoHHuc59hTjCUtROSudJp16NU0u3vI7K2lhmXcCPkbryfxPpWTlbdGiinsyLUb200hEe5i+xRluCs+0MfTHf8KcXzbCdo7jLXxBpd3cZivV+1HGOFkbH4c/4VbjJEppnzwgwC+RwQMd67DmJ43LgLvOT0Cg5pPTUpIe4gSPY8ckcw6g9DU3uDViNMysqK+4k9HwBTvYm1yR4pLF8homyM/3sfnVX0KtZ2NCe3jsoY5mPm3b4KJgHH1AqOaTdi2klcqXE11LGJpQqo56gAfpWqaMmmRW8UEr4nnMSkj5wueO9JtvcNjRv4dPtUCWfnyufuyzIAH+gobbEtNSotiIVhmk/exH78Y4YUr3C1tRDL513i2GzPAJxwPeqSfUeltCezs3IM8iRzW7tsaXAYr7+1K9hI09P1/VLaeGz0+6+yIuWQsBg8dx6cVDipblRk4vQTV9cu9TK2utzm4aNsQzJgeVn7xwOvQcH0pKChsXKbluZ8zNouswyRXJnWF1kSUArkZzWlrozcuV6FYNdwWQClDb5PBwevWstGV7xJaWUt7A8ix7I4hneTgUmxpX3LiX9tHDGZbgyXCHOMFh147VnZ3ujXmSVjZuvF9nqekS29xGpkcBQoHHbnPbFJRad2K8TASzs5I5NjFZeNjtKCB+FaX1JaXQU6XCLNpnlka4Y/KVxsY/lVXFZEUFlBGq/bHkJY4VImHHqSSKrmJsJqcFnZTMtpKtzERwXJDL9cYGatN9SGtS9/aVpKkBFzKLiMA+Yw4XHYCoauaxaGW2oXd9qUMsZjJiPyvKnGcUbE83Mxs+q31vI7reR7uc7QAT+lCs9wlfdFMa1cCZ5fkLtwfl607IzvIjjuEu7xGvHYR4wzIOcf/rq7iJPKgbzVjvRHFnI3ocn8qRRAglLGOMmZF53bTx7072DXof0kn9lv4MEYPwj8C49P+Easv8A41WBY9f2Yvg6sZQfCfwOEP8ACPDlnj/0XQBF/wAMsfBb/okPgP8A8Jqy/wDjVACj9lr4ML0+EXgQfTw1Zf8AxqgBP+GWPgv/ANEi8Cf+E1Zf/GqAJP8Ahl/4NmNY/wDhU3gby15C/wDCN2eB9P3VADT+y58GSMH4SeBcf9i1Zf8AxqgBp/ZY+C5/5pF4E/8ACasv/jVO7EJ/wyv8F/8AokXgT/wmbL/41Rdi5SRP2X/g2ilV+E3gZVPYeG7MD/0VSGlYZ/wyz8GM/wDJIvAh/wC5asv/AI1Rcdg/4ZZ+C/8A0SHwH/4TVl/8aouwsg/4ZY+C/wD0SLwJ/wCEzZf/ABqi7JsH/DLPwYzz8IvAn/hNWX/xqndjJYf2Y/g7bBhF8J/A8QYYYJ4csxn6/u6VxnplABQAUAFABQAUAFABQAUAFABQAUAFABQAUAf/2Q=="
          },
          {
            "timing": 3000,
            "data": "data:image/jpeg;base64,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",
            "timestamp": 1011789312134
          }
        ]
      }
    },
    "aria-roles": {
      "id": "aria-roles",
      "title": "`[role]` values are valid",
      "description": "ARIA roles must have valid values in order to perform their intended accessibility functions. [Learn more](https://web.dev/aria-roles/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "canonical": {
      "id": "canonical",
      "title": "Document has a valid `rel=canonical`",
      "description": "Canonical links suggest which URL to show in search results. [Learn more](https://web.dev/canonical/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "render-blocking-resources": {
      "id": "render-blocking-resources",
      "title": "Eliminate render-blocking resources",
      "description": "Resources are blocking the first paint of your page. Consider delivering critical JS/CSS inline and deferring all non-critical JS/styles. [Learn more](https://web.dev/render-blocking-resources/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "Potential savings of 0 ms",
      "details": {
        "items": [
          {
            "totalBytes": 1555,
            "url": "https://fonts.googleapis.com/css2?family=Open+Sans&family=PT+Sans:wght@400;700&display=swap",
            "wastedMs": 780
          }
        ],
        "type": "opportunity",
        "headings": [
          {
            "valueType": "url",
            "key": "url",
            "label": "URL"
          },
          {
            "key": "totalBytes",
            "valueType": "bytes",
            "label": "Transfer Size"
          },
          {
            "key": "wastedMs",
            "valueType": "timespanMs",
            "label": "Potential Savings"
          }
        ],
        "overallSavingsMs": 0
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "structured-data": {
      "id": "structured-data",
      "title": "Structured data is valid",
      "description": "Run the [Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool/) and the [Structured Data Linter](http://linter.structured-data.org/) to validate structured data. [Learn more](https://web.dev/structured-data/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "user-timings": {
      "id": "user-timings",
      "title": "User Timing marks and measures",
      "description": "Consider instrumenting your app with the User Timing API to measure your app's real-world performance during key user experiences. [Learn more](https://web.dev/user-timings/).",
      "score": null,
      "scoreDisplayMode": "notApplicable",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "interactive": {
      "id": "interactive",
      "title": "Time to Interactive",
      "description": "Time to interactive is the amount of time it takes for the page to become fully interactive. [Learn more](https://web.dev/interactive/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "1.9 s",
      "numericValue": 1860,
      "numericUnit": "millisecond"
    },
    "full-page-screenshot": {
      "id": "full-page-screenshot",
      "title": "Full-page screenshot",
      "description": "A full-height screenshot of the final rendered page",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "nodes": {
          "page-5-SPAN": {
            "bottom": 59,
            "top": -3,
            "width": 144,
            "right": 299,
            "height": 62,
            "left": 155
          },
          "6-24-META": {
            "width": 0,
            "left": 0,
            "top": 0,
            "right": 0,
            "bottom": 0,
            "height": 0
          },
          "6-23-META": {
            "left": 0,
            "height": 0,
            "bottom": 0,
            "width": 0,
            "top": 0,
            "right": 0
          },
          "6-27-SPAN": {
            "width": 144,
            "bottom": 59,
            "top": -3,
            "left": 155,
            "height": 62,
            "right": 299
          },
          "6-7-A": {
            "left": 18,
            "width": 324,
            "top": 3381,
            "bottom": 3473,
            "height": 92,
            "right": 342
          },
          "page-4-H2": {
            "height": 96,
            "top": 236,
            "bottom": 332,
            "left": 0,
            "right": 360,
            "width": 360
          },
          "6-30-HEADER": {
            "bottom": 600,
            "left": 0,
            "top": 0,
            "right": 360,
            "width": 360,
            "height": 600
          },
          "page-1-IMG": {
            "left": 18,
            "right": 342,
            "bottom": 1704,
            "height": 223,
            "top": 1482,
            "width": 324
          },
          "6-19-LINK": {
            "top": 0,
            "right": 0,
            "bottom": 0,
            "left": 0,
            "width": 0,
            "height": 0
          },
          "6-28-BODY": {
            "width": 360,
            "top": 0,
            "bottom": 4069,
            "height": 4069,
            "left": 0,
            "right": 360
          },
          "6-10-A": {
            "width": 324,
            "left": 18,
            "right": 342,
            "top": 3931,
            "height": 36,
            "bottom": 3967
          },
          "page-6-P": {
            "top": 332,
            "bottom": 396,
            "left": 0,
            "right": 360,
            "width": 360,
            "height": 64
          },
          "6-1-A": {
            "height": 36,
            "width": 324,
            "left": 18,
            "bottom": 114,
            "top": 78,
            "right": 342
          },
          "6-15-LINK": {
            "left": 0,
            "right": 0,
            "width": 0,
            "height": 0,
            "top": 0,
            "bottom": 0
          },
          "6-12-A": {
            "left": 18,
            "bottom": 4039,
            "top": 4003,
            "height": 36,
            "right": 342,
            "width": 324
          },
          "6-20-LINK": {
            "right": 0,
            "top": 0,
            "height": 0,
            "left": 0,
            "width": 0,
            "bottom": 0
          },
          "6-6-A": {
            "width": 324,
            "top": 2977,
            "left": 18,
            "right": 342,
            "height": 56,
            "bottom": 3033
          },
          "6-21-LINK": {
            "bottom": 0,
            "top": 0,
            "right": 0,
            "height": 0,
            "left": 0,
            "width": 0
          },
          "6-29-H1": {
            "width": 324,
            "right": 342,
            "left": 18,
            "height": 58,
            "top": 0,
            "bottom": 58
          },
          "6-13-LINK": {
            "bottom": 0,
            "right": 0,
            "left": 0,
            "top": 0,
            "height": 0,
            "width": 0
          },
          "6-2-A": {
            "left": 18,
            "width": 324,
            "height": 36,
            "bottom": 150,
            "top": 114,
            "right": 342
          },
          "page-7-A": {
            "height": 36,
            "left": 18,
            "bottom": 114,
            "width": 324,
            "right": 342,
            "top": 78
          },
          "6-14-LINK": {
            "top": 0,
            "width": 0,
            "bottom": 0,
            "left": 0,
            "height": 0,
            "right": 0
          },
          "6-18-LINK": {
            "bottom": 0,
            "left": 0,
            "right": 0,
            "top": 0,
            "width": 0,
            "height": 0
          },
          "6-0-A": {
            "bottom": 58,
            "top": 0,
            "height": 58,
            "right": 342,
            "width": 324,
            "left": 18
          },
          "6-22-META": {
            "right": 0,
            "left": 0,
            "width": 0,
            "height": 0,
            "bottom": 0,
            "top": 0
          },
          "6-17-LINK": {
            "top": 0,
            "bottom": 0,
            "height": 0,
            "width": 0,
            "left": 0,
            "right": 0
          },
          "page-0-IMG": {
            "left": 18,
            "bottom": 925,
            "width": 324,
            "height": 223,
            "top": 702,
            "right": 342
          },
          "6-26-SCRIPT": {
            "right": 0,
            "bottom": 0,
            "left": 0,
            "width": 0,
            "top": 0,
            "height": 0
          },
          "page-8-A": {
            "bottom": 186,
            "top": 150,
            "height": 36,
            "width": 324,
            "left": 18,
            "right": 342
          },
          "page-2-IMG": {
            "width": 324,
            "height": 223,
            "bottom": 2517,
            "left": 18,
            "right": 342,
            "top": 2295
          },
          "6-11-A": {
            "bottom": 4003,
            "top": 3967,
            "width": 324,
            "left": 18,
            "height": 36,
            "right": 342
          },
          "6-16-LINK": {
            "top": 0,
            "bottom": 0,
            "height": 0,
            "right": 0,
            "left": 0,
            "width": 0
          },
          "6-9-A": {
            "width": 324,
            "right": 342,
            "bottom": 3911,
            "height": 58,
            "left": 18,
            "top": 3853
          },
          "6-4-A": {
            "top": 1385,
            "right": 342,
            "height": 56,
            "left": 18,
            "width": 324,
            "bottom": 1441
          },
          "6-8-A": {
            "top": 3721,
            "width": 324,
            "height": 92,
            "bottom": 3813,
            "left": 18,
            "right": 342
          },
          "6-5-A": {
            "left": 18,
            "height": 56,
            "right": 342,
            "bottom": 2254,
            "width": 324,
            "top": 2198
          },
          "6-3-A": {
            "bottom": 186,
            "right": 342,
            "width": 324,
            "height": 36,
            "left": 18,
            "top": 150
          },
          "page-3-HEADER": {
            "top": 0,
            "right": 360,
            "bottom": 600,
            "width": 360,
            "height": 600,
            "left": 0
          },
          "6-25-META": {
            "top": 0,
            "bottom": 0,
            "width": 0,
            "left": 0,
            "right": 0,
            "height": 0
          }
        },
        "type": "full-page-screenshot",
        "screenshot": {
          "width": 360,
          "height": 4069,
          "data": "data:image/jpeg;base64,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iAip4piMWG0/FkBc4mzGDdxXJZjGMytEsWGtMR1HZdcj3/kg9Ei1YSWAuFnW1HetkBFxsTxieCvbRUdOJpiLnN77e5dCkmnfRtlqouFLYlzG62sgsoqGEzV1TE6asjZE1x+zYGkOt33V9AREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQeY8pPtcaoYX/wCGct/a6x+S9MBYWC4/lFhcldFHNT6zRcr2zD6qpFjmJsjEUmGSPmAtmyuF/ZZB0sZgdK2N3pE0UYvmN7ZunMLj4fUyUuORU0Ve6rgkGpJuNj8dFJjkNU+upat1I+ohDG5ogCbHmCtYYKh+OUlUcONNCdA1jPV31dYaboKr6GoPlH5qK2QSkXE2tx2b239m6tYlVzGvhwx1cYIomNEs17Fxy3uVZNPP+lwn4MnCy/4mU5fU6qLGKSWnxhuINpPO4XgZ2Zc2trbe7VBphlU+mxplJFWmrp5W7k3sbE/kvTrjYXOyoqwWYOKZjWkiUsAIPTbxXZQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERBSk/XMP8A/Tv/ALmreqnlbPFT04ZxJAXFz7kNaLchvuFippZpKqOognbG5jHMs6PMCCQeo6I+lmfwpDUNFRHcB4j7JB5Ft+4c+SCGSunhp6wSNjM1MwPBbfK4EG2nLYrNRWT0sLHTGBj5nhrMxIazQk5jfXbuWzsPMlPVMkmzS1LcrpMtgBawAF/zU1VTCoYwB+R8bszHWvY7beBKCmMUd5rWOa+CaSnYHh8Zux1wbc+481uaiu86ZT2pwZGGRrrHsAWuCL67jopZKSWajngmnYTK3KHMjyhvsvr71Kae9ZHUZ/UjczLbe5Bv8EGKCd1TStke0NfdzXAbXBINvcqUVXM2GnbDHEHTVErCDewsXG+/df6K9SU/m0PDzZu2517W3cT+aoT0roXUMLJbO84keH5drhztvbZBI+tqYmVLHxsfNDkN2A5S1x3t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RviDM0MYeQQToRYnmuoiDlspsgw9rGyvYyV7iXtsRdrjr01K0ngkNHiwETi6RxyAN1d2G7ddbrrog5Zc+nlrWvglk49nMc1tweyBYnltzUdIXQx4bUGOR8fmuQljS4gnKRoNeS67hmaWnYiy0p4W09PHCwktjaGgnewQcd0NRLxJxHNFlq+JYNBdlyAXAOh/981YjjvBWSiSse+RgaS6INdoD6osNdV1EQRwxMgibFE0NY0WACkREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREHjfKCtq4cYnjiqpmMGWzWyEAdkclz/SVd+Nqf6rvqrPlJ+vKn+H+0LmILXpKu/G1P9V31T0lXfjan+q76qqiC16SrvxtT/Vd9U9JV342p/qu+qqogtekq78bU/wBV31T0lXfjan+q76qqiC16SrvxtT/Vd9U9JV342p/qu+qqogtekq78bU/1XfVPSVd+Nqf6rvqqqILXpKu/G1P9V31T0lXfjan+q76qqiC16SrvxtT/AFXfVPSVd+Nqf6rvqqqILXpKu/G1P9V31T0lXfjan+q76qqiC16SrvxtT/Vd9U9JV342p/qu+qqogtekq78bU/1XfVPSVd+Nqf6rvqqqILXpKu/G1P8AVd9U9JV342p/qu+qqogtekq78bU/1XfVPSVd+Nqf6rvqqqILXpKu/G1P9V31T0lXfjan+q76qqiC16SrvxtT/Vd9U9JV342p/qu+qqogtekq78bU/wBV31T0lXfjan+q76qqiC16SrvxtT/Vd9U9JV342p/qu+qqogtekq78bU/1XfVPSVd+Nqf6rvqqqILXpKu/G1P9V31T0lXfjan+q76qqiC16SrvxtT/AFXfVPSVd+Nqf6rvqqqIO15P1tXNjEEctVM9hzXa6QkHsnkvZLw3k3+vKb+L+0r3KAiIgIiIPDeUn68qf4f7QuYun5Sfryp/h/tC5iAiIgIiICIiAiIgIiIClNPMKYVBYeCXZQ/lfool15P/AKpF/wD1X5FBQpaCqrGudTwukDTY25KT0TX8Yw+bP4gbmy6bbXXSwTh+ha7jTPhZnZd7BqNVLhJgM9dkq5ZIhTG8rgczetvBByHY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NBsuhSYdVwxPinrzNGYzG1vDAy9/eojgdqKlijqSyemJLJQ3qb7XQZw2pqmYnPh1VKJyxgeyTLlJGm49qvUDaxsJFc+N8mY2LBYWUGH4a6mqJaqoqDPUSixflygDoB7lPQU81NCWT1LqhxcSHOFrDogqYcftsRqCwySicssLXygCwF0qsRkfTE07XwStqGQuEjQbXt0J6qaWhlbVPqaOoEL5AOI1zMzXW2PKxWgwx5iIkqM0jp2zucGWFxbQC/cg2qM1NTsbNiRjcXeuWNzO7gLfkqEs81ThOIM85c8Q3tJkAL25b2It8V06yjfPPDPDMIpYswBczMCDvpcdFGzDTwKuOScyGp9Z2W1jayCKZ9RR4S14qHSPLo7OLWiwJAtstayolZiDmTVUlJDZvCeGAtcedyQfyU7qGeah83nqGuIc0hzY7WDSDtfuWa2kqaoSRCpY2CQWLeFdwHOxv+SC6NllasaGMa0bNFgtkBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERARcnFa2pFZBh9CWtnlGYvcL5R/wFSwcfDoZZsRruNEALHh2y625a9EHRRV31tPG6BrpLGo/whlPa29243VefG8Pgc5klRZzXFjmhpJBG/JB0EVWbEaSClbUyTNET/VI1zeAWaLEKWuY51NKH5fWFrEewoLKKGlqoKuMyU8gkaDlJHVVcQZVRxT1MdaYxG0uazI3LoOd9Sg6CLnT1U8raKGI8GWpbmc618gAubA89QFtSSzxV8lFPKZhwxLG8gA2vYg2QX0REBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQcLFy+hximxIxufAGcOTKL5d/r8ExLEafE8Iq46Que5jWuPZI0zD6LurAAaLAADuQeZdWxVlVg/BzFsLgx7i0gBxA0v10K0jraWlnxhk/wDiSvcGNyk5t9F6kAAWAA8FTosPFJUVUxkEnHkzgZbZd/qg4JhkoqbCJ6pjuDE5xeLXyXNxcK9hb21ePVdZTg+b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66MTKOskkp4aYxODXOjkzkkkAntDbW3JbNlhZgTC6ljeeO5ty5w1yjXQ96DlouiGUsGG09RJBxZZHPbYuIFhbU28VgspqOmp3S0/HkmbxDd5aGi5AAtz0Qc9F1W0dLHWSNdZwdE2SBkj8odmsbE+09FTr2GOfKaU0xA1Zcm/eLoKyIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgKekqfNnSnJmzxOj3ta4tdQIgu4diLqHiAxiRjweyTbK6xFx7CVpBVsbT+b1EPGiDs7bPylp562OiqogtyVkc0zDJTgwRsyMia8iw8eq3fiOVsDKWIwtheZG5nZiXac9OmyoogvmvhZxH09IIppGlpdnJDQd8o5fFRQ1cbaN1LNAZG587SH5S02t01GgVVEE8tTxKOCnyW4TnnNffNb6KWOsidBHFVU/G4VwxwflIF72OhuFTRBbfWRz1L5aqnzhwAa1j8uQDQAb8lrWVQqRExkfDjiblY3NmO99SqyICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIBc2G66E1PRUb+DUGeSZvr8MgNaemoN/gg56KWWFzI2zBpEUjnBhJFzb/2FsKOczRwiP7SVocwXGoIuEECKz6Pqs8bOF25Llrbi+nUcvatZ6SanLeI0dv1crg6/uKCBFalw6rhjdJJDYN9azgS3xANx7Uiw+qmjbIyMZXermeG5vAE6oKqIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiDaN2SRr7XykFdKvoJ6qrkqaRhnhmcXhzdbX1selly0QdQ001VhVOyBnEfDJIJGg6tvax8NDqrTW5PKDDm3DssUYuDcGzVwUQW6B9SawugaJZXB2Zrtc4O471eEMFFV0VTLEaZxl7cLnXygW7XUDx6LjIg69NSz0dRPUVWkPDeC8nSW4IAHW5IWaOnlq4YI6ulLoALNqGusY235nYgdCuOiDLgA4gG4B0PVYREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBFM6kqWx8V1PKI98xYbe9QoCIiAiyQQbEEHvWEBEWbG17G210GEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQFdwhrTWF7mhxijfI1p5kNJCpKWmnkpZ2TREBzTpfY9yA+pnkc5z5pHF/rXcdVdlZR0ckdPLTGVxa10kmcgi4v2QNNL81BNPSSNdkozHI7mJSWjwFvzUgr4X8N9RSCWaNoaHZyA4DbMLa/BBKyigp34i2oaZBTWy2Nr9qyjmbTGjhrI6cM+1Mb485LXWAPiN+qh8+e5lZxG5n1VruvaxDr7LQ1N6BtLk9WUyZr9QBa3sQXcbLJMVkhipmh4ktdpJL+617e5b1NCwUFRI6lZTyQ5SMs2cm5sQRc237lBJiTXVsdayDJO1wc857tcfC2i1fXQinqIYKXhicDMTJmIIcD02QbVLaaiy07qYTS8Nrnvc8ixIvoB0upGywswJhdSxvPHc25c4a5Rroe9QPrYZ42+cUxfK1gYHtky3A0FxbVaQ1cbaN1LNAZG587SH5S02t01GgQTFlNR01OZafjyTM4hu8tDRcgAW56KDEKdlPUWiJMb2NkZfcAi9it46yJ0EcVVT8bhXDHB+UgXvY6G4UNXUOqp3SvAbewDW7NAFgAghREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERB//9k="
        }
      }
    },
    "dlitem": {
      "id": "dlitem",
      "title": "Definition list items are wrapped in `<dl>` elements",
      "description": "Definition list items (`<dt>` and `<dd>`) must be wrapped in a parent `<dl>` element to ensure that screen readers can properly announce them. [Learn more](https://web.dev/dlitem/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "managed-focus": {
      "id": "managed-focus",
      "title": "The user's focus is directed to new content added to the page",
      "description": "If new content, such as a dialog, is added to the page, the user's focus is directed to it. [Learn more](https://web.dev/managed-focus/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "accesskeys": {
      "id": "accesskeys",
      "title": "`[accesskey]` values are unique",
      "description": "Access keys let users quickly focus a part of the page. For proper navigation, each access key must be unique. [Learn more](https://web.dev/accesskeys/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "uses-rel-preload": {
      "id": "uses-rel-preload",
      "title": "Preload key requests",
      "description": "Consider using `<link rel=preload>` to prioritize fetching resources that are currently requested later in page load. [Learn more](https://web.dev/uses-rel-preload/).",
      "score": null,
      "scoreDisplayMode": "notApplicable",
      "details": {
        "headings": [],
        "type": "opportunity",
        "overallSavingsMs": 0,
        "items": []
      }
    },
    "modern-image-formats": {
      "id": "modern-image-formats",
      "title": "Serve images in next-gen formats",
      "description": "Image formats like WebP and AVIF often provide better compression than PNG or JPEG, which means faster downloads and less data consumption. [Learn more](https://web.dev/uses-webp-images/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsBytes": 0,
        "overallSavingsMs": 0,
        "type": "opportunity",
        "headings": [],
        "items": []
      },
      "warnings": [],
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "document-title": {
      "id": "document-title",
      "title": "Document has a `<title>` element",
      "description": "The title gives screen reader users an overview of the page, and search engine users rely on it heavily to determine if a page is relevant to their search. [Learn more](https://web.dev/document-title/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "password-inputs-can-be-pasted-into": {
      "id": "password-inputs-can-be-pasted-into",
      "title": "Allows users to paste into password fields",
      "description": "Preventing password pasting undermines good security policy. [Learn more](https://web.dev/password-inputs-can-be-pasted-into/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "lcp-lazy-loaded": {
      "id": "lcp-lazy-loaded",
      "title": "Largest Contentful Paint image was not lazily loaded",
      "description": "Above-the-fold images that are lazily loaded render later in the page lifecycle, which can delay the largest contentful paint. [Learn more](https://web.dev/lcp-lazy-loading/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [
          {
            "node": {
              "snippet": "<header class=\"header\">",
              "nodeLabel": "BlogDeCafé\nNosotros\nCursos\nContacto\nBlog de café con consejos y cursos\n\nAprende…",
              "path": "1,HTML,1,BODY,0,HEADER",
              "selector": "body > header.header",
              "boundingRect": {
                "bottom": 600,
                "right": 360,
                "width": 360,
                "height": 600,
                "top": 0,
                "left": 0
              },
              "lhId": "page-3-HEADER",
              "type": "node"
            }
          }
        ],
        "type": "table",
        "headings": [
          {
            "itemType": "node",
            "text": "Element",
            "key": "node"
          }
        ]
      }
    },
    "is-crawlable": {
      "id": "is-crawlable",
      "title": "Page isn’t blocked from indexing",
      "description": "Search engines are unable to include your pages in search results if they don't have permission to crawl them. [Learn more](https://web.dev/is-crawable/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "main-thread-tasks": {
      "id": "main-thread-tasks",
      "title": "Tasks",
      "description": "Lists the toplevel main thread tasks that executed during page load.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "headings": [
          {
            "itemType": "ms",
            "granularity": 1,
            "text": "Start Time",
            "key": "startTime"
          },
          {
            "itemType": "ms",
            "text": "End Time",
            "key": "duration",
            "granularity": 1
          }
        ],
        "items": [
          {
            "startTime": 171.506,
            "duration": 10.432
          },
          {
            "startTime": 315.661,
            "duration": 9.558
          },
          {
            "duration": 16.34,
            "startTime": 325.234
          },
          {
            "duration": 7.205,
            "startTime": 350.099
          },
          {
            "startTime": 519.823,
            "duration": 64.343
          }
        ],
        "type": "table"
      }
    },
    "aria-required-attr": {
      "id": "aria-required-attr",
      "title": "`[role]`s have all required `[aria-*]` attributes",
      "description": "Some ARIA roles have required attributes that describe the state of the element to screen readers. [Learn more](https://web.dev/aria-required-attr/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-required-parent": {
      "id": "aria-required-parent",
      "title": "`[role]`s are contained by their required parent element",
      "description": "Some ARIA child roles must be contained by specific parent roles to properly perform their intended accessibility functions. [Learn more](https://web.dev/aria-required-parent/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "largest-contentful-paint": {
      "id": "largest-contentful-paint",
      "title": "Largest Contentful Paint",
      "description": "Largest Contentful Paint marks the time at which the largest text or image is painted. [Learn more](https://web.dev/lighthouse-largest-contentful-paint/)",
      "score": 0.86,
      "scoreDisplayMode": "numeric",
      "displayValue": "2.7 s",
      "numericValue": 2670,
      "numericUnit": "millisecond"
    },
    "aria-hidden-body": {
      "id": "aria-hidden-body",
      "title": "`[aria-hidden=\"true\"]` is not present on the document `<body>`",
      "description": "Assistive technologies, like screen readers, work inconsistently when `aria-hidden=\"true\"` is set on the document `<body>`. [Learn more](https://web.dev/aria-hidden-body/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "td-headers-attr": {
      "id": "td-headers-attr",
      "title": "Cells in a `<table>` element that use the `[headers]` attribute refer to table cells within the same table.",
      "description": "Screen readers have features to make navigating tables easier. Ensuring `<td>` cells using the `[headers]` attribute only refer to other cells in the same table may improve the experience for screen reader users. [Learn more](https://web.dev/td-headers-attr/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "listitem": {
      "id": "listitem",
      "title": "List items (`<li>`) are contained within `<ul>` or `<ol>` parent elements",
      "description": "Screen readers require list items (`<li>`) to be contained within a parent `<ul>` or `<ol>` to be announced properly. [Learn more](https://web.dev/listitem/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "unused-javascript": {
      "id": "unused-javascript",
      "title": "Reduce unused JavaScript",
      "description": "Reduce unused JavaScript and defer loading scripts until they are required to decrease bytes consumed by network activity. [Learn more](https://web.dev/unused-javascript/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "headings": [],
        "overallSavingsMs": 0,
        "overallSavingsBytes": 0,
        "type": "opportunity",
        "items": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "input-image-alt": {
      "id": "input-image-alt",
      "title": "`<input type=\"image\">` elements have `[alt]` text",
      "description": "When an image is being used as an `<input>` button, providing alternative text can help screen reader users understand the purpose of the button. [Learn more](https://web.dev/input-image-alt/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "charset": {
      "id": "charset",
      "title": "Properly defines charset",
      "description": "A character encoding declaration is required. It can be done with a `<meta>` tag in the first 1024 bytes of the HTML or in the Content-Type HTTP response header. [Learn more](https://web.dev/charset/).",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "custom-controls-roles": {
      "id": "custom-controls-roles",
      "title": "Custom controls have ARIA roles",
      "description": "Custom interactive controls have appropriate ARIA roles. [Learn more](https://web.dev/custom-control-roles/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "first-contentful-paint-3g": {
      "id": "first-contentful-paint-3g",
      "title": "First Contentful Paint (3G)",
      "description": "First Contentful Paint 3G marks the time at which the first text or image is painted while on a 3G network. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/first-contentful-paint).",
      "score": 0.62,
      "scoreDisplayMode": "numeric",
      "displayValue": "3960 ms",
      "numericValue": 3960,
      "numericUnit": "millisecond"
    },
    "content-width": {
      "id": "content-width",
      "title": "Content is sized correctly for the viewport",
      "description": "If the width of your app's content doesn't match the width of the viewport, your app might not be optimized for mobile screens. [Learn more](https://web.dev/content-width/).",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "interactive-element-affordance": {
      "id": "interactive-element-affordance",
      "title": "Interactive elements indicate their purpose and state",
      "description": "Interactive elements, such as links and buttons, should indicate their state and be distinguishable from non-interactive elements. [Learn more](https://web.dev/interactive-element-affordance/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "font-display": {
      "id": "font-display",
      "title": "All text remains visible during webfont loads",
      "description": "Leverage the font-display CSS feature to ensure text is user-visible while webfonts are loading. [Learn more](https://web.dev/font-display/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      },
      "warnings": [
        "Lighthouse was unable to automatically check the `font-display` value for the origin https://fonts.googleapis.com."
      ]
    },
    "unused-css-rules": {
      "id": "unused-css-rules",
      "title": "Reduce unused CSS",
      "description": "Reduce unused rules from stylesheets and defer CSS not used for above-the-fold content to decrease bytes consumed by network activity. [Learn more](https://web.dev/unused-css-rules/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "headings": [],
        "overallSavingsMs": 0,
        "items": [],
        "type": "opportunity",
        "overallSavingsBytes": 0
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "metrics": {
      "id": "metrics",
      "title": "Metrics",
      "description": "Collects all available metrics.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "items": [
          {
            "observedFirstContentfulPaintAllFramesTs": 1011786620233,
            "observedFirstContentfulPaint": 308,
            "observedLargestContentfulPaintTs": 1011786886413,
            "observedTimeOriginTs": 1011786312134,
            "totalBlockingTime": 0,
            "observedFirstMeaningfulPaintTs": 1011786620233,
            "observedTotalCumulativeLayoutShift": 0.018392486572265623,
            "observedDomContentLoaded": 275,
            "observedFirstContentfulPaintAllFrames": 308,
            "totalCumulativeLayoutShift": 0.018392486572265623,
            "observedLoad": 472,
            "observedCumulativeLayoutShiftMainFrame": 0.018392486572265623,
            "observedSpeedIndex": 581,
            "observedLargestContentfulPaintAllFrames": 574,
            "observedFirstPaint": 308,
            "firstMeaningfulPaint": 1860,
            "observedCumulativeLayoutShift": 0.018392486572265623,
            "speedIndex": 1860,
            "cumulativeLayoutShiftMainFrame": 0.018392486572265623,
            "observedFirstMeaningfulPaint": 308,
            "observedLargestContentfulPaintAllFramesTs": 1011786886413,
            "observedLastVisualChangeTs": 1011786893134,
            "observedFirstContentfulPaintTs": 1011786620233,
            "observedLargestContentfulPaint": 574,
            "observedNavigationStartTs": 1011786312134,
            "largestContentfulPaint": 2670,
            "observedTimeOrigin": 0,
            "interactive": 1860,
            "observedLoadTs": 1011786783936,
            "observedTraceEndTs": 1011789102573,
            "observedNavigationStart": 0,
            "observedTraceEnd": 2790,
            "observedFirstVisualChangeTs": 1011786893134,
            "observedSpeedIndexTs": 1011786893572,
            "cumulativeLayoutShift": 0.018392486572265623,
            "observedDomContentLoadedTs": 1011786587199,
            "observedFirstVisualChange": 581,
            "observedLastVisualChange": 581,
            "firstContentfulPaint": 1860,
            "observedFirstPaintTs": 1011786620233,
            "maxPotentialFID": 16
          },
          {
            "lcpInvalidated": false
          }
        ],
        "type": "debugdata"
      },
      "numericValue": 1860,
      "numericUnit": "millisecond"
    },
    "themed-omnibox": {
      "id": "themed-omnibox",
      "title": "Does not set a theme color for the address bar.",
      "description": "The browser address bar can be themed to match your site. [Learn more](https://web.dev/themed-omnibox/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "Failures: No manifest was fetched,\nNo `<meta name=\"theme-color\">` tag found.",
      "details": {
        "items": [
          {
            "failures": [
              "No manifest was fetched",
              "No `<meta name=\"theme-color\">` tag found"
            ],
            "parseFailureReason": "No manifest was fetched",
            "isParseFailure": true,
            "themeColor": null
          }
        ],
        "type": "debugdata"
      }
    },
    "script-treemap-data": {
      "id": "script-treemap-data",
      "title": "Script Treemap Data",
      "description": "Used for treemap app",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "nodes": [
          {
            "unusedBytes": 614,
            "name": "https://maitaneabad.github.io/fictitious-blog-cafe/js/modernizr.js",
            "resourceBytes": 4793
          }
        ],
        "type": "treemap-data"
      }
    },
    "pwa-each-page-has-url": {
      "id": "pwa-each-page-has-url",
      "title": "Each page has a URL",
      "description": "Ensure individual pages are deep linkable via URL and that URLs are unique for the purpose of shareability on social media. [Learn more](https://web.dev/pwa-each-page-has-url/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "duplicate-id-aria": {
      "id": "duplicate-id-aria",
      "title": "ARIA IDs are unique",
      "description": "The value of an ARIA ID must be unique to prevent other instances from being overlooked by assistive technologies. [Learn more](https://web.dev/duplicate-id-aria/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-valid-attr-value": {
      "id": "aria-valid-attr-value",
      "title": "`[aria-*]` attributes have valid values",
      "description": "Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid values. [Learn more](https://web.dev/aria-valid-attr-value/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-valid-attr": {
      "id": "aria-valid-attr",
      "title": "`[aria-*]` attributes are valid and not misspelled",
      "description": "Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid names. [Learn more](https://web.dev/aria-valid-attr/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "mainthread-work-breakdown": {
      "id": "mainthread-work-breakdown",
      "title": "Minimizes main-thread work",
      "description": "Consider reducing the time spent parsing, compiling and executing JS. You may find delivering smaller JS payloads helps with this. [Learn more](https://web.dev/mainthread-work-breakdown/)",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "0.6 s",
      "details": {
        "headings": [
          {
            "key": "groupLabel",
            "text": "Category",
            "itemType": "text"
          },
          {
            "itemType": "ms",
            "text": "Time Spent",
            "granularity": 1,
            "key": "duration"
          }
        ],
        "type": "table",
        "items": [
          {
            "groupLabel": "Rendering",
            "duration": 289.892,
            "group": "paintCompositeRender"
          },
          {
            "groupLabel": "Other",
            "duration": 144.23999999999995,
            "group": "other"
          },
          {
            "groupLabel": "Style & Layout",
            "duration": 88.55999999999999,
            "group": "styleLayout"
          },
          {
            "group": "scriptEvaluation",
            "groupLabel": "Script Evaluation",
            "duration": 47.443999999999996
          },
          {
            "groupLabel": "Parse HTML & CSS",
            "duration": 21.644,
            "group": "parseHTML"
          },
          {
            "group": "scriptParseCompile",
            "groupLabel": "Script Parsing & Compilation",
            "duration": 7.164000000000001
          }
        ]
      },
      "numericValue": 598.944,
      "numericUnit": "millisecond"
    },
    "third-party-summary": {
      "id": "third-party-summary",
      "title": "Minimize third-party usage",
      "description": "Third-party code can significantly impact load performance. Limit the number of redundant third-party providers and try to load third-party code after your page has primarily finished loading. [Learn more](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/loading-third-party-javascript/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "displayValue": "Third-party code blocked the main thread for 0 ms",
      "details": {
        "items": [
          {
            "mainThreadTime": 4.588000000000001,
            "transferSize": 40280,
            "entity": {
              "url": "https://fonts.google.com/",
              "text": "Google Fonts",
              "type": "link"
            },
            "blockingTime": 0,
            "subItems": {
              "items": [
                {
                  "blockingTime": 0,
                  "url": "https://fonts.gstatic.com/s/ptsans/v16/jizfRExUiTo99u79B_mh0O6tLR8a8zI.woff2",
                  "transferSize": 12468,
                  "mainThreadTime": 0
                },
                {
                  "url": "https://fonts.gstatic.com/s/opensans/v28/memSYaGs126MiZpBA-UvWbX2vVnXBbObj2OVZyOOSr4dVJWUgsjZ0B4gaVIUx6EQ.woff2",
                  "mainThreadTime": 0,
                  "blockingTime": 0,
                  "transferSize": 12434
                },
                {
                  "blockingTime": 0,
                  "transferSize": 12268,
                  "url": "https://fonts.gstatic.com/s/ptsans/v16/jizaRExUiTo99u79D0KExcOPIDU.woff2",
                  "mainThreadTime": 0
                }
              ],
              "type": "subitems"
            }
          }
        ],
        "summary": {
          "wastedBytes": 40280,
          "wastedMs": 0
        },
        "headings": [
          {
            "text": "Third-Party",
            "key": "entity",
            "itemType": "link",
            "subItemsHeading": {
              "itemType": "url",
              "key": "url"
            }
          },
          {
            "key": "transferSize",
            "itemType": "bytes",
            "granularity": 1,
            "subItemsHeading": {
              "key": "transferSize"
            },
            "text": "Transfer Size"
          },
          {
            "key": "blockingTime",
            "granularity": 1,
            "subItemsHeading": {
              "key": "blockingTime"
            },
            "text": "Main-Thread Blocking Time",
            "itemType": "ms"
          }
        ],
        "type": "table"
      }
    },
    "aria-hidden-focus": {
      "id": "aria-hidden-focus",
      "title": "`[aria-hidden=\"true\"]` elements do not contain focusable descendents",
      "description": "Focusable descendents within an `[aria-hidden=\"true\"]` element prevent those interactive elements from being available to users of assistive technologies like screen readers. [Learn more](https://web.dev/aria-hidden-focus/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "uses-optimized-images": {
      "id": "uses-optimized-images",
      "title": "Efficiently encode images",
      "description": "Optimized images load faster and consume less cellular data. [Learn more](https://web.dev/uses-optimized-images/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsBytes": 0,
        "headings": [],
        "items": [],
        "overallSavingsMs": 0,
        "type": "opportunity"
      },
      "warnings": [],
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "resource-summary": {
      "id": "resource-summary",
      "title": "Keep request counts low and transfer sizes small",
      "description": "To set budgets for the quantity and size of page resources, add a budget.json file. [Learn more](https://web.dev/use-lighthouse-for-performance-budgets/).",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "14 requests • 383 KiB",
      "details": {
        "type": "table",
        "items": [
          {
            "transferSize": 391719,
            "label": "Total",
            "resourceType": "total",
            "requestCount": 14
          },
          {
            "label": "Image",
            "transferSize": 340232,
            "resourceType": "image",
            "requestCount": 4
          },
          {
            "transferSize": 38725,
            "requestCount": 4,
            "label": "Font",
            "resourceType": "font"
          },
          {
            "requestCount": 3,
            "transferSize": 6093,
            "label": "Stylesheet",
            "resourceType": "stylesheet"
          },
          {
            "requestCount": 1,
            "label": "Script",
            "transferSize": 2519,
            "resourceType": "script"
          },
          {
            "label": "Document",
            "requestCount": 1,
            "resourceType": "document",
            "transferSize": 2318
          },
          {
            "requestCount": 1,
            "label": "Other",
            "transferSize": 1832,
            "resourceType": "other"
          },
          {
            "requestCount": 0,
            "transferSize": 0,
            "resourceType": "media",
            "label": "Media"
          },
          {
            "requestCount": 5,
            "resourceType": "third-party",
            "transferSize": 40280,
            "label": "Third-party"
          }
        ],
        "headings": [
          {
            "itemType": "text",
            "text": "Resource Type",
            "key": "label"
          },
          {
            "text": "Requests",
            "itemType": "numeric",
            "key": "requestCount"
          },
          {
            "text": "Transfer Size",
            "itemType": "bytes",
            "key": "transferSize"
          }
        ]
      }
    },
    "logical-tab-order": {
      "id": "logical-tab-order",
      "title": "The page has a logical tab order",
      "description": "Tabbing through the page follows the visual layout. Users cannot focus elements that are offscreen. [Learn more](https://web.dev/logical-tab-order/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "cumulative-layout-shift": {
      "id": "cumulative-layout-shift",
      "title": "Cumulative Layout Shift",
      "description": "Cumulative Layout Shift measures the movement of visible elements within the viewport. [Learn more](https://web.dev/cls/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "0.018",
      "details": {
        "type": "debugdata",
        "items": [
          {
            "totalCumulativeLayoutShift": 0.018392486572265623,
            "cumulativeLayoutShiftMainFrame": 0.018392486572265623
          }
        ]
      },
      "numericValue": 0.018392486572265623,
      "numericUnit": "unitless"
    },
    "maskable-icon": {
      "id": "maskable-icon",
      "title": "Manifest doesn't have a maskable icon",
      "description": "A maskable icon ensures that the image fills the entire shape without being letterboxed when installing the app on a device. [Learn more](https://web.dev/maskable-icon-audit/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "No manifest was fetched"
    },
    "image-alt": {
      "id": "image-alt",
      "title": "Image elements have `[alt]` attributes",
      "description": "Informative elements should aim for short, descriptive alternate text. Decorative elements can be ignored with an empty alt attribute. [Learn more](https://web.dev/image-alt/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "meta-refresh": {
      "id": "meta-refresh",
      "title": "The document does not use `<meta http-equiv=\"refresh\">`",
      "description": "Users do not expect a page to refresh automatically, and doing so will move focus back to the top of the page. This may create a frustrating or confusing experience. [Learn more](https://web.dev/meta-refresh/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "crawlable-anchors": {
      "id": "crawlable-anchors",
      "title": "Links are crawlable",
      "description": "Search engines may use `href` attributes on links to crawl websites. Ensure that the `href` attribute of anchor elements links to an appropriate destination, so more pages of the site can be discovered. [Learn More](https://support.google.com/webmasters/answer/9112205)",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "max-potential-fid": {
      "id": "max-potential-fid",
      "title": "Max Potential First Input Delay",
      "description": "The maximum potential First Input Delay that your users could experience is the duration of the longest task. [Learn more](https://web.dev/lighthouse-max-potential-fid/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "20 ms",
      "numericValue": 16,
      "numericUnit": "millisecond"
    },
    "object-alt": {
      "id": "object-alt",
      "title": "`<object>` elements have alternate text",
      "description": "Screen readers cannot translate non-text content. Adding alternate text to `<object>` elements helps screen readers convey meaning to users. [Learn more](https://web.dev/object-alt/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "network-server-latency": {
      "id": "network-server-latency",
      "title": "Server Backend Latencies",
      "description": "Server latencies can impact web performance. If the server latency of an origin is high, it's an indication the server is overloaded or has poor backend performance. [Learn more](https://hpbn.co/primer-on-web-performance/#analyzing-the-resource-waterfall).",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "0 ms",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "timing-budget": {
      "id": "timing-budget",
      "title": "Timing budget",
      "description": "Set a timing budget to help you keep an eye on the performance of your site. Performant sites load fast and respond to user input events quickly. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/budgets).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-input-field-name": {
      "id": "aria-input-field-name",
      "title": "ARIA input fields have accessible names",
      "description": "When an input field doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more](https://web.dev/aria-name/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "is-on-https": {
      "id": "is-on-https",
      "title": "Uses HTTPS",
      "description": "All sites should be protected with HTTPS, even ones that don't handle sensitive data. This includes avoiding [mixed content](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content), where some resources are loaded over HTTP despite the initial request being served over HTTPS. HTTPS prevents intruders from tampering with or passively listening in on the communications between your app and your users, and is a prerequisite for HTTP/2 and many new web platform APIs. [Learn more](https://web.dev/is-on-https/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "largest-contentful-paint-element": {
      "id": "largest-contentful-paint-element",
      "title": "Largest Contentful Paint element",
      "description": "This is the largest contentful element painted within the viewport. [Learn More](https://web.dev/lighthouse-largest-contentful-paint/)",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "1 element found",
      "details": {
        "type": "table",
        "headings": [
          {
            "key": "node",
            "text": "Element",
            "itemType": "node"
          }
        ],
        "items": [
          {
            "node": {
              "snippet": "<header class=\"header\">",
              "lhId": "page-3-HEADER",
              "type": "node",
              "path": "1,HTML,1,BODY,0,HEADER",
              "nodeLabel": "BlogDeCafé\nNosotros\nCursos\nContacto\nBlog de café con consejos y cursos\n\nAprende…",
              "boundingRect": {
                "width": 360,
                "top": 0,
                "right": 360,
                "left": 0,
                "bottom": 600,
                "height": 600
              },
              "selector": "body > header.header"
            }
          }
        ]
      }
    },
    "total-byte-weight": {
      "id": "total-byte-weight",
      "title": "Avoids enormous network payloads",
      "description": "Large network payloads cost users real money and are highly correlated with long load times. [Learn more](https://web.dev/total-byte-weight/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "Total size was 383 KiB",
      "details": {
        "type": "table",
        "headings": [
          {
            "key": "url",
            "itemType": "url",
            "text": "URL"
          },
          {
            "key": "totalBytes",
            "itemType": "bytes",
            "text": "Transfer Size"
          }
        ],
        "items": [
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog3.webp",
            "totalBytes": 123553
          },
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog1.webp",
            "totalBytes": 97271
          },
          {
            "totalBytes": 74972,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog2.webp"
          },
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/banner.webp",
            "totalBytes": 44436
          },
          {
            "totalBytes": 12468,
            "url": "https://fonts.gstatic.com/s/ptsans/v16/jizfRExUiTo99u79B_mh0O6tLR8a8zI.woff2"
          },
          {
            "url": "https://fonts.gstatic.com/s/opensans/v28/memSYaGs126MiZpBA-UvWbX2vVnXBbObj2OVZyOOSr4dVJWUgsjZ0B4gaVIUx6EQ.woff2",
            "totalBytes": 12434
          },
          {
            "totalBytes": 12268,
            "url": "https://fonts.gstatic.com/s/ptsans/v16/jizaRExUiTo99u79D0KExcOPIDU.woff2"
          },
          {
            "totalBytes": 2519,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/js/modernizr.js"
          },
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/css/normalize.css",
            "totalBytes": 2509
          },
          {
            "totalBytes": 2318,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/"
          }
        ]
      },
      "numericValue": 391719,
      "numericUnit": "byte"
    },
    "heading-order": {
      "id": "heading-order",
      "title": "Heading elements appear in a sequentially-descending order",
      "description": "Properly ordered headings that do not skip levels convey the semantic structure of the page, making it easier to navigate and understand when using assistive technologies. [Learn more](https://web.dev/heading-order/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "html-lang-valid": {
      "id": "html-lang-valid",
      "title": "`<html>` element has a valid value for its `[lang]` attribute",
      "description": "Specifying a valid [BCP 47 language](https://www.w3.org/International/questions/qa-choosing-language-tags#question) helps screen readers announce text properly. [Learn more](https://web.dev/html-lang-valid/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "redirects": {
      "id": "redirects",
      "title": "Avoid multiple page redirects",
      "description": "Redirects introduce additional delays before the page can be loaded. [Learn more](https://web.dev/redirects/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsMs": 0,
        "type": "opportunity",
        "items": [],
        "headings": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "link-name": {
      "id": "link-name",
      "title": "Links have a discernible name",
      "description": "Link text (and alternate text for images, when used as links) that is discernible, unique, and focusable improves the navigation experience for screen reader users. [Learn more](https://web.dev/link-name/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "duplicated-javascript": {
      "id": "duplicated-javascript",
      "title": "Remove duplicate modules in JavaScript bundles",
      "description": "Remove large, duplicate JavaScript modules from bundles to reduce unnecessary bytes consumed by network activity. ",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "type": "opportunity",
        "overallSavingsBytes": 0,
        "headings": [],
        "items": [],
        "overallSavingsMs": 0
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "speed-index": {
      "id": "speed-index",
      "title": "Speed Index",
      "description": "Speed Index shows how quickly the contents of a page are visibly populated. [Learn more](https://web.dev/speed-index/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "1.9 s",
      "numericValue": 1860,
      "numericUnit": "millisecond"
    },
    "uses-rel-preconnect": {
      "id": "uses-rel-preconnect",
      "title": "Preconnect to required origins",
      "description": "Consider adding `preconnect` or `dns-prefetch` resource hints to establish early connections to important third-party origins. [Learn more](https://web.dev/uses-rel-preconnect/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "warnings": []
    },
    "installable-manifest": {
      "id": "installable-manifest",
      "title": "Web app manifest or service worker do not meet the installability requirements",
      "description": "Service worker is the technology that enables your app to use many Progressive Web App features, such as offline, add to homescreen, and push notifications. With proper service worker and manifest implementations, browsers can proactively prompt users to add your app to their homescreen, which can lead to higher engagement. [Learn more](https://web.dev/installable-manifest/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "displayValue": "1 reason",
      "details": {
        "items": [
          {
            "reason": "No manifest was fetched"
          }
        ],
        "debugData": {
          "type": "debugdata",
          "manifestUrl": null
        },
        "type": "table",
        "headings": [
          {
            "itemType": "text",
            "key": "reason",
            "text": "Failure reason"
          }
        ]
      },
      "warnings": [],
      "numericValue": 1,
      "numericUnit": "element"
    },
    "duplicate-id-active": {
      "id": "duplicate-id-active",
      "title": "`[id]` attributes on active, focusable elements are unique",
      "description": "All focusable elements must have a unique `id` to ensure that they're visible to assistive technologies. [Learn more](https://web.dev/duplicate-id-active/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "uses-text-compression": {
      "id": "uses-text-compression",
      "title": "Enable text compression",
      "description": "Text-based resources should be served with compression (gzip, deflate or brotli) to minimize total network bytes. [Learn more](https://web.dev/uses-text-compression/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "items": [],
        "type": "opportunity",
        "headings": [],
        "overallSavingsMs": 0,
        "overallSavingsBytes": 0
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "bypass": {
      "id": "bypass",
      "title": "The page contains a heading, skip link, or landmark region",
      "description": "Adding ways to bypass repetitive content lets keyboard users navigate the page more efficiently. [Learn more](https://web.dev/bypass/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "focus-traps": {
      "id": "focus-traps",
      "title": "User focus is not accidentally trapped in a region",
      "description": "A user can tab into and out of any control or region without accidentally trapping their focus. [Learn more](https://web.dev/focus-traps/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "network-rtt": {
      "id": "network-rtt",
      "title": "Network Round Trip Times",
      "description": "Network round trip times (RTT) have a large impact on performance. If the RTT to an origin is high, it's an indication that servers closer to the user could improve performance. [Learn more](https://hpbn.co/primer-on-latency-and-bandwidth/).",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "0 ms",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "button-name": {
      "id": "button-name",
      "title": "Buttons have an accessible name",
      "description": "When a button doesn't have an accessible name, screen readers announce it as \"button\", making it unusable for users who rely on screen readers. [Learn more](https://web.dev/button-name/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "network-requests": {
      "id": "network-requests",
      "title": "Network Requests",
      "description": "Lists the network requests that were made during page load.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "headings": [
          {
            "text": "URL",
            "key": "url",
            "itemType": "url"
          },
          {
            "key": "protocol",
            "text": "Protocol",
            "itemType": "text"
          },
          {
            "text": "Start Time",
            "key": "startTime",
            "granularity": 1,
            "itemType": "ms"
          },
          {
            "itemType": "ms",
            "text": "End Time",
            "granularity": 1,
            "key": "endTime"
          },
          {
            "key": "transferSize",
            "displayUnit": "kb",
            "itemType": "bytes",
            "text": "Transfer Size",
            "granularity": 1
          },
          {
            "displayUnit": "kb",
            "granularity": 1,
            "itemType": "bytes",
            "text": "Resource Size",
            "key": "resourceSize"
          },
          {
            "text": "Status Code",
            "key": "statusCode",
            "itemType": "text"
          },
          {
            "itemType": "text",
            "key": "mimeType",
            "text": "MIME Type"
          },
          {
            "itemType": "text",
            "text": "Resource Type",
            "key": "resourceType"
          }
        ],
        "items": [
          {
            "endTime": 122.15999991167337,
            "transferSize": 2318,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/",
            "protocol": "h2",
            "resourceSize": 6794,
            "statusCode": 200,
            "finished": true,
            "resourceType": "Document",
            "mimeType": "text/html",
            "startTime": 0
          },
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/css/normalize.css",
            "finished": true,
            "endTime": 268.3419999666512,
            "startTime": 138.73199990484864,
            "protocol": "h2",
            "resourceSize": 6434,
            "resourceType": "Stylesheet",
            "statusCode": 200,
            "mimeType": "text/css",
            "transferSize": 2509
          },
          {
            "mimeType": "text/css",
            "transferSize": 1555,
            "resourceType": "Font",
            "statusCode": 200,
            "resourceSize": 5701,
            "endTime": 150.7899999851361,
            "protocol": "h2",
            "url": "https://fonts.googleapis.com/css2?family=Open+Sans&family=PT+Sans:wght@400;700&display=swap",
            "startTime": 138.99099989794195,
            "finished": true
          },
          {
            "url": "https://fonts.googleapis.com/css2?family=Open+Sans&family=PT+Sans:wght@400;700&display=swap",
            "mimeType": "text/css",
            "resourceType": "Stylesheet",
            "finished": true,
            "startTime": 139.32699989527464,
            "protocol": "h2",
            "endTime": 147.40699995309114,
            "resourceSize": 5701,
            "statusCode": 200,
            "transferSize": 1555
          },
          {
            "resourceType": "Stylesheet",
            "resourceSize": 4486,
            "startTime": 139.5569999003783,
            "protocol": "h2",
            "finished": true,
            "statusCode": 200,
            "transferSize": 2029,
            "mimeType": "text/css",
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/css/main.css",
            "endTime": 265.1509999996051
          },
          {
            "statusCode": 200,
            "resourceSize": 4793,
            "transferSize": 2519,
            "resourceType": "Script",
            "endTime": 267.9599999682978,
            "finished": true,
            "startTime": 140.26999997440726,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/js/modernizr.js",
            "mimeType": "application/javascript",
            "protocol": "h2"
          },
          {
            "finished": true,
            "mimeType": "text/html",
            "resourceSize": 0,
            "startTime": 143.97799992002547,
            "statusCode": 200,
            "protocol": "h2",
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/us.html",
            "transferSize": 1832,
            "endTime": 274.6579999802634,
            "resourceType": "Other"
          },
          {
            "startTime": 272.9689999250695,
            "resourceSize": 44,
            "mimeType": "image/webp",
            "protocol": "data",
            "endTime": 273.1309999944642,
            "url": "data:image/webp;base64,UklGRiQAAABXRUJQVlA4IBgAAAAwAQCdASoBAAEAAwA0JaQAA3AA/vuUAAA=",
            "resourceType": "Image",
            "finished": true,
            "statusCode": 200,
            "transferSize": 0
          },
          {
            "resourceSize": 11340,
            "startTime": 277.758999960497,
            "mimeType": "font/woff2",
            "resourceType": "Font",
            "endTime": 282.723999931477,
            "transferSize": 12268,
            "protocol": "h2",
            "statusCode": 200,
            "finished": true,
            "url": "https://fonts.gstatic.com/s/ptsans/v16/jizaRExUiTo99u79D0KExcOPIDU.woff2"
          },
          {
            "mimeType": "font/woff2",
            "protocol": "h2",
            "finished": true,
            "transferSize": 12468,
            "startTime": 277.96599990688264,
            "url": "https://fonts.gstatic.com/s/ptsans/v16/jizfRExUiTo99u79B_mh0O6tLR8a8zI.woff2",
            "statusCode": 200,
            "resourceType": "Font",
            "resourceSize": 11540,
            "endTime": 281.1849999707192
          },
          {
            "resourceType": "Font",
            "finished": true,
            "protocol": "h2",
            "statusCode": 200,
            "url": "https://fonts.gstatic.com/s/opensans/v28/memSYaGs126MiZpBA-UvWbX2vVnXBbObj2OVZyOOSr4dVJWUgsjZ0B4gaVIUx6EQ.woff2",
            "transferSize": 12434,
            "resourceSize": 11508,
            "endTime": 281.55399998649955,
            "mimeType": "font/woff2",
            "startTime": 278.27499993145466
          },
          {
            "finished": true,
            "mimeType": "image/webp",
            "resourceSize": 96582,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog1.webp",
            "statusCode": 200,
            "protocol": "h2",
            "transferSize": 97271,
            "endTime": 444.9669999303296,
            "resourceType": "Image",
            "startTime": 295.84899998735636
          },
          {
            "endTime": 402.81999995931983,
            "statusCode": 200,
            "transferSize": 74972,
            "resourceSize": 74266,
            "mimeType": "image/webp",
            "protocol": "h2",
            "startTime": 296.4919999940321,
            "resourceType": "Image",
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog2.webp",
            "finished": true
          },
          {
            "endTime": 435.7479999307543,
            "finished": true,
            "resourceType": "Image",
            "mimeType": "image/webp",
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog3.webp",
            "statusCode": 200,
            "protocol": "h2",
            "resourceSize": 122812,
            "transferSize": 123553,
            "startTime": 296.6920000035316
          },
          {
            "url": "data:image/webp;base64,UklGRkoAAABXRUJQVlA4WAoAAAAQAAAAAAAAAAAAQUxQSAwAAAABBxAR/Q9ERP8DAABWUDggGAAAA",
            "statusCode": 200,
            "finished": true,
            "transferSize": 0,
            "resourceType": "Image",
            "startTime": 297.1200000029057,
            "endTime": 297.25199996028095,
            "protocol": "data",
            "mimeType": "image/webp",
            "resourceSize": 82
          },
          {
            "resourceSize": 90,
            "url": "data:image/webp;base64,UklGRlIAAABXRUJQVlA4WAoAAAASAAAAAAAAAAAAQU5JTQYAAAD/////AABBTk1GJgAAAAAAAAAAA",
            "mimeType": "image/webp",
            "finished": true,
            "statusCode": 200,
            "startTime": 297.38699994049966,
            "protocol": "data",
            "transferSize": 0,
            "resourceType": "Image",
            "endTime": 297.48899990227073
          },
          {
            "resourceType": "Image",
            "endTime": 297.6839999901131,
            "startTime": 297.5959999021143,
            "statusCode": 200,
            "resourceSize": 38,
            "mimeType": "image/webp",
            "protocol": "data",
            "transferSize": 0,
            "finished": true,
            "url": "data:image/webp;base64,UklGRh4AAABXRUJQVlA4TBEAAAAvAAAAAAfQ//73v/+BiOh/AAA="
          },
          {
            "statusCode": 200,
            "finished": true,
            "transferSize": 44436,
            "resourceType": "Image",
            "resourceSize": 43748,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/banner.webp",
            "startTime": 305.3389999549836,
            "mimeType": "image/webp",
            "protocol": "h2",
            "endTime": 468.5759999556467
          }
        ],
        "type": "table"
      }
    },
    "tap-targets": {
      "id": "tap-targets",
      "title": "Tap targets are sized appropriately",
      "description": "Interactive elements like buttons and links should be large enough (48x48px), and have enough space around them, to be easy enough to tap without overlapping onto other elements. [Learn more](https://web.dev/tap-targets/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "displayValue": "100% appropriately sized tap targets",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "deprecations": {
      "id": "deprecations",
      "title": "Avoids deprecated APIs",
      "description": "Deprecated APIs will eventually be removed from the browser. [Learn more](https://web.dev/deprecations/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "font-size": {
      "id": "font-size",
      "title": "Document uses legible font sizes",
      "description": "Font sizes less than 12px are too small to be legible and require mobile visitors to “pinch to zoom” in order to read. Strive to have >60% of page text ≥12px. [Learn more](https://web.dev/font-size/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "displayValue": "100% legible text",
      "details": {
        "headings": [
          {
            "itemType": "source-location",
            "text": "Source",
            "key": "source"
          },
          {
            "key": "selector",
            "itemType": "code",
            "text": "Selector"
          },
          {
            "text": "% of Page Text",
            "key": "coverage",
            "itemType": "text"
          },
          {
            "itemType": "text",
            "key": "fontSize",
            "text": "Font Size"
          }
        ],
        "type": "table",
        "items": [
          {
            "fontSize": "≥ 12px",
            "coverage": "100.00%",
            "source": {
              "value": "Legible text",
              "type": "code"
            }
          }
        ]
      }
    },
    "critical-request-chains": {
      "id": "critical-request-chains",
      "title": "Avoid chaining critical requests",
      "description": "The Critical Request Chains below show you what resources are loaded with a high priority. Consider reducing the length of chains, reducing the download size of resources, or deferring the download of unnecessary resources to improve page load. [Learn more](https://web.dev/critical-request-chains/).",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "2 chains found",
      "details": {
        "type": "criticalrequestchain",
        "longestChain": {
          "transferSize": 2519,
          "duration": 267.9599999682978,
          "length": 2
        },
        "chains": {
          "269B5BE5AAAA62CD76D363C0D74FFC8C": {
            "request": {
              "endTime": 1011786.435997,
              "responseReceivedTime": 1011786.43599,
              "transferSize": 2318,
              "url": "https://maitaneabad.github.io/fictitious-blog-cafe/",
              "startTime": 1011786.313837
            },
            "children": {
              "41.8": {
                "request": {
                  "transferSize": 2519,
                  "endTime": 1011786.581797,
                  "startTime": 1011786.454107,
                  "responseReceivedTime": 1011786.581791,
                  "url": "https://maitaneabad.github.io/fictitious-blog-cafe/js/modernizr.js"
                }
              },
              "41.5": {
                "request": {
                  "url": "https://fonts.googleapis.com/css2?family=Open+Sans&family=PT+Sans:wght@400;700&display=swap",
                  "endTime": 1011786.461244,
                  "transferSize": 1555,
                  "startTime": 1011786.453164,
                  "responseReceivedTime": 1011786.461236
                }
              }
            }
          }
        }
      }
    },
    "unminified-javascript": {
      "id": "unminified-javascript",
      "title": "Minify JavaScript",
      "description": "Minifying JavaScript files can reduce payload sizes and script parse time. [Learn more](https://web.dev/unminified-javascript/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsBytes": 0,
        "type": "opportunity",
        "headings": [],
        "items": [],
        "overallSavingsMs": 0
      },
      "warnings": [],
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "first-meaningful-paint": {
      "id": "first-meaningful-paint",
      "title": "First Meaningful Paint",
      "description": "First Meaningful Paint measures when the primary content of a page is visible. [Learn more](https://web.dev/first-meaningful-paint/).",
      "score": 0.96,
      "scoreDisplayMode": "numeric",
      "displayValue": "1.9 s",
      "numericValue": 1860,
      "numericUnit": "millisecond"
    },
    "no-vulnerable-libraries": {
      "id": "no-vulnerable-libraries",
      "title": "Avoids front-end JavaScript libraries with known security vulnerabilities",
      "description": "Some third-party scripts may contain known security vulnerabilities that are easily identified and exploited by attackers. [Learn more](https://web.dev/no-vulnerable-libraries/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "summary": {},
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "custom-controls-labels": {
      "id": "custom-controls-labels",
      "title": "Custom controls have associated labels",
      "description": "Custom interactive controls have associated labels, provided by aria-label or aria-labelledby. [Learn more](https://web.dev/custom-controls-labels/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "viewport": {
      "id": "viewport",
      "title": "Has a `<meta name=\"viewport\">` tag with `width` or `initial-scale`",
      "description": "A `<meta name=\"viewport\">` not only optimizes your app for mobile screen sizes, but also prevents [a 300 millisecond delay to user input](https://developers.google.com/web/updates/2013/12/300ms-tap-delay-gone-away). [Learn more](https://web.dev/viewport/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "warnings": []
    },
    "no-unload-listeners": {
      "id": "no-unload-listeners",
      "title": "Avoids `unload` event listeners",
      "description": "The `unload` event does not fire reliably and listening for it can prevent browser optimizations like the Back-Forward Cache. Use `pagehide` or `visibilitychange` events instead. [Learn more](https://web.dev/bfcache/#never-use-the-unload-event)",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "notification-on-start": {
      "id": "notification-on-start",
      "title": "Avoids requesting the notification permission on page load",
      "description": "Users are mistrustful of or confused by sites that request to send notifications without context. Consider tying the request to user gestures instead. [Learn more](https://web.dev/notification-on-start/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "visual-order-follows-dom": {
      "id": "visual-order-follows-dom",
      "title": "Visual order on the page follows DOM order",
      "description": "DOM order matches the visual order, improving navigation for assistive technology. [Learn more](https://web.dev/visual-order-follows-dom/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "focusable-controls": {
      "id": "focusable-controls",
      "title": "Interactive controls are keyboard focusable",
      "description": "Custom interactive controls are keyboard focusable and display a focus indicator. [Learn more](https://web.dev/focusable-controls/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "apple-touch-icon": {
      "id": "apple-touch-icon",
      "title": "Does not provide a valid `apple-touch-icon`",
      "description": "For ideal appearance on iOS when users add a progressive web app to the home screen, define an `apple-touch-icon`. It must point to a non-transparent 192px (or 180px) square PNG. [Learn More](https://web.dev/apple-touch-icon/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "warnings": []
    },
    "uses-passive-event-listeners": {
      "id": "uses-passive-event-listeners",
      "title": "Uses passive listeners to improve scrolling performance",
      "description": "Consider marking your touch and wheel event listeners as `passive` to improve your page's scroll performance. [Learn more](https://web.dev/uses-passive-event-listeners/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "dom-size": {
      "id": "dom-size",
      "title": "Avoids an excessive DOM size",
      "description": "A large DOM will increase memory usage, cause longer [style calculations](https://developers.google.com/web/fundamentals/performance/rendering/reduce-the-scope-and-complexity-of-style-calculations), and produce costly [layout reflows](https://developers.google.com/speed/articles/reflow). [Learn more](https://web.dev/dom-size/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "71 elements",
      "details": {
        "type": "table",
        "headings": [
          {
            "itemType": "text",
            "key": "statistic",
            "text": "Statistic"
          },
          {
            "key": "node",
            "text": "Element",
            "itemType": "node"
          },
          {
            "key": "value",
            "itemType": "numeric",
            "text": "Value"
          }
        ],
        "items": [
          {
            "statistic": "Total DOM Elements",
            "value": 71
          },
          {
            "node": {
              "type": "node",
              "boundingRect": {
                "bottom": 59,
                "top": -3,
                "left": 155,
                "right": 299,
                "height": 62,
                "width": 144
              },
              "lhId": "6-27-SPAN",
              "snippet": "<span class=\"logo__bold\">",
              "path": "1,HTML,1,BODY,0,HEADER,0,DIV,0,DIV,0,A,0,H1,1,SPAN",
              "nodeLabel": "DeCafé",
              "selector": "div.bar > a.logo > h1.logo__name > span.logo__bold"
            },
            "statistic": "Maximum DOM Depth",
            "value": 7
          },
          {
            "value": 4,
            "statistic": "Maximum Child Elements",
            "node": {
              "path": "1,HTML,1,BODY",
              "selector": "body",
              "nodeLabel": "body",
              "type": "node",
              "boundingRect": {
                "height": 4069,
                "left": 0,
                "right": 360,
                "top": 0,
                "width": 360,
                "bottom": 4069
              },
              "snippet": "<body>",
              "lhId": "6-28-BODY"
            }
          }
        ]
      },
      "numericValue": 71,
      "numericUnit": "element"
    },
    "th-has-data-cells": {
      "id": "th-has-data-cells",
      "title": "`<th>` elements and elements with `[role=\"columnheader\"/\"rowheader\"]` have data cells they describe.",
      "description": "Screen readers have features to make navigating tables easier. Ensuring table headers always refer to some set of cells may improve the experience for screen reader users. [Learn more](https://web.dev/th-has-data-cells/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "uses-long-cache-ttl": {
      "id": "uses-long-cache-ttl",
      "title": "Serve static assets with an efficient cache policy",
      "description": "A long cache lifetime can speed up repeat visits to your page. [Learn more](https://web.dev/uses-long-cache-ttl/).",
      "score": 0.22,
      "scoreDisplayMode": "numeric",
      "displayValue": "7 resources found",
      "details": {
        "items": [
          {
            "cacheHitProbability": 0.08333333333333333,
            "totalBytes": 123553,
            "debugData": {
              "type": "debugdata",
              "max-age": 600
            },
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog3.webp",
            "cacheLifetimeMs": 600000,
            "wastedBytes": 113256.91666666666
          },
          {
            "totalBytes": 97271,
            "debugData": {
              "type": "debugdata",
              "max-age": 600
            },
            "wastedBytes": 89165.08333333333,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog1.webp",
            "cacheLifetimeMs": 600000,
            "cacheHitProbability": 0.08333333333333333
          },
          {
            "cacheLifetimeMs": 600000,
            "totalBytes": 74972,
            "debugData": {
              "max-age": 600,
              "type": "debugdata"
            },
            "cacheHitProbability": 0.08333333333333333,
            "wastedBytes": 68724.33333333333,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog2.webp"
          },
          {
            "debugData": {
              "max-age": 600,
              "type": "debugdata"
            },
            "cacheLifetimeMs": 600000,
            "cacheHitProbability": 0.08333333333333333,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/banner.webp",
            "totalBytes": 44436,
            "wastedBytes": 40733
          },
          {
            "cacheLifetimeMs": 600000,
            "wastedBytes": 2309.083333333333,
            "debugData": {
              "type": "debugdata",
              "max-age": 600
            },
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/js/modernizr.js",
            "cacheHitProbability": 0.08333333333333333,
            "totalBytes": 2519
          },
          {
            "cacheHitProbability": 0.08333333333333333,
            "debugData": {
              "type": "debugdata",
              "max-age": 600
            },
            "cacheLifetimeMs": 600000,
            "wastedBytes": 2299.9166666666665,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/css/normalize.css",
            "totalBytes": 2509
          },
          {
            "totalBytes": 2029,
            "cacheLifetimeMs": 600000,
            "cacheHitProbability": 0.08333333333333333,
            "wastedBytes": 1859.9166666666665,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/css/main.css",
            "debugData": {
              "max-age": 600,
              "type": "debugdata"
            }
          }
        ],
        "summary": {
          "wastedBytes": 318348.25
        },
        "type": "table",
        "headings": [
          {
            "key": "url",
            "text": "URL",
            "itemType": "url"
          },
          {
            "displayUnit": "duration",
            "key": "cacheLifetimeMs",
            "text": "Cache TTL",
            "itemType": "ms"
          },
          {
            "displayUnit": "kb",
            "key": "totalBytes",
            "granularity": 1,
            "itemType": "bytes",
            "text": "Transfer Size"
          }
        ]
      },
      "numericValue": 318348.25,
      "numericUnit": "byte"
    },
    "preload-lcp-image": {
      "id": "preload-lcp-image",
      "title": "Preload Largest Contentful Paint image",
      "description": "Preload the image used by the LCP element in order to improve your LCP time. [Learn more](https://web.dev/optimize-lcp/#preload-important-resources).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsMs": 0,
        "headings": [
          {
            "valueType": "node",
            "key": "node"
          },
          {
            "key": "url",
            "label": "URL",
            "valueType": "url"
          },
          {
            "valueType": "timespanMs",
            "label": "Potential Savings",
            "key": "wastedMs"
          }
        ],
        "items": [
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/banner.webp",
            "node": {
              "lhId": "page-3-HEADER",
              "path": "1,HTML,1,BODY,0,HEADER",
              "selector": "body > header.header",
              "boundingRect": {
                "height": 600,
                "width": 360,
                "left": 0,
                "top": 0,
                "bottom": 600,
                "right": 360
              },
              "type": "node",
              "snippet": "<header class=\"header\">",
              "nodeLabel": "BlogDeCafé\nNosotros\nCursos\nContacto\nBlog de café con consejos y cursos\n\nAprende…"
            },
            "wastedMs": 0
          }
        ],
        "type": "opportunity"
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "aria-toggle-field-name": {
      "id": "aria-toggle-field-name",
      "title": "ARIA toggle fields have accessible names",
      "description": "When a toggle field doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more](https://web.dev/aria-name/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "http-status-code": {
      "id": "http-status-code",
      "title": "Page has successful HTTP status code",
      "description": "Pages with unsuccessful HTTP status codes may not be indexed properly. [Learn more](https://web.dev/http-status-code/).",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "html-has-lang": {
      "id": "html-has-lang",
      "title": "`<html>` element has a `[lang]` attribute",
      "description": "If a page doesn't specify a lang attribute, a screen reader assumes that the page is in the default language that the user chose when setting up the screen reader. If the page isn't actually in the default language, then the screen reader might not announce the page's text correctly. [Learn more](https://web.dev/html-has-lang/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "layout-shift-elements": {
      "id": "layout-shift-elements",
      "title": "Avoid large layout shifts",
      "description": "These DOM elements contribute most to the CLS of the page.",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "5 elements found",
      "details": {
        "headings": [
          {
            "key": "node",
            "itemType": "node",
            "text": "Element"
          },
          {
            "text": "CLS Contribution",
            "granularity": 0.001,
            "itemType": "numeric",
            "key": "score"
          }
        ],
        "items": [
          {
            "score": 0.0072345635533873865,
            "node": {
              "boundingRect": {
                "width": 360,
                "left": 0,
                "height": 96,
                "bottom": 332,
                "top": 236,
                "right": 360
              },
              "snippet": "<h2 class=\"no-margin\">",
              "path": "1,HTML,1,BODY,0,HEADER,1,DIV,0,H2",
              "lhId": "page-4-H2",
              "nodeLabel": "Blog de café con consejos y cursos",
              "type": "node",
              "selector": "body > header.header > div.header__text > h2.no-margin"
            }
          },
          {
            "score": 0.0040068351987991675,
            "node": {
              "path": "1,HTML,1,BODY,0,HEADER,0,DIV,0,DIV,0,A,0,H1,1,SPAN",
              "nodeLabel": "DeCafé",
              "snippet": "<span class=\"logo__bold\">",
              "selector": "div.bar > a.logo > h1.logo__name > span.logo__bold",
              "type": "node",
              "boundingRect": {
                "width": 144,
                "right": 299,
                "left": 155,
                "height": 62,
                "bottom": 59,
                "top": -3
              },
              "lhId": "page-5-SPAN"
            }
          },
          {
            "score": 0.003895534221054746,
            "node": {
              "path": "1,HTML,1,BODY,0,HEADER,1,DIV,1,P",
              "nodeLabel": "Aprende de los expertos con las mejores recetas y consejos",
              "boundingRect": {
                "left": 0,
                "bottom": 396,
                "right": 360,
                "width": 360,
                "height": 64,
                "top": 332
              },
              "selector": "body > header.header > div.header__text > p.no-margin",
              "snippet": "<p class=\"no-margin\">",
              "lhId": "page-6-P",
              "type": "node"
            }
          },
          {
            "node": {
              "selector": "div.container > div.bar > nav.navbar > a.navbar__link",
              "boundingRect": {
                "bottom": 114,
                "width": 324,
                "right": 342,
                "height": 36,
                "top": 78,
                "left": 18
              },
              "lhId": "page-7-A",
              "type": "node",
              "path": "1,HTML,1,BODY,0,HEADER,0,DIV,0,DIV,1,NAV,0,A",
              "snippet": "<a class=\"navbar__link\" href=\"./us.html\">",
              "nodeLabel": "Nosotros"
            },
            "score": 0.0016277767995121618
          },
          {
            "node": {
              "selector": "div.container > div.bar > nav.navbar > a.navbar__link",
              "boundingRect": {
                "bottom": 186,
                "top": 150,
                "left": 18,
                "height": 36,
                "width": 324,
                "right": 342
              },
              "path": "1,HTML,1,BODY,0,HEADER,0,DIV,0,DIV,1,NAV,2,A",
              "nodeLabel": "Contacto",
              "lhId": "page-8-A",
              "type": "node",
              "snippet": "<a class=\"navbar__link\" href=\"./contact.html\">"
            },
            "score": 0.0016277767995121618
          }
        ],
        "type": "table"
      }
    },
    "valid-source-maps": {
      "id": "valid-source-maps",
      "title": "Page has valid source maps",
      "description": "Source maps translate minified code to the original source code. This helps developers debug in production. In addition, Lighthouse is able to provide further insights. Consider deploying source maps to take advantage of these benefits. [Learn more](https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "preload-fonts": {
      "id": "preload-fonts",
      "title": "Fonts with `font-display: optional` are preloaded",
      "description": "Preload `optional` fonts so first-time visitors may use them. [Learn more](https://web.dev/preload-optional-fonts/)",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "offscreen-images": {
      "id": "offscreen-images",
      "title": "Defer offscreen images",
      "description": "Consider lazy-loading offscreen and hidden images after all critical resources have finished loading to lower time to interactive. [Learn more](https://web.dev/offscreen-images/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "type": "opportunity",
        "overallSavingsMs": 0,
        "items": [],
        "headings": [],
        "overallSavingsBytes": 0
      },
      "warnings": [],
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "plugins": {
      "id": "plugins",
      "title": "Document avoids plugins",
      "description": "Search engines can't index plugin content, and many devices restrict plugins or don't support them. [Learn more](https://web.dev/plugins/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "uses-responsive-images": {
      "id": "uses-responsive-images",
      "title": "Properly size images",
      "description": "Serve images that are appropriately-sized to save cellular data and improve load time. [Learn more](https://web.dev/uses-responsive-images/).",
      "score": 0.5,
      "scoreDisplayMode": "numeric",
      "displayValue": "Potential savings of 143 KiB",
      "details": {
        "overallSavingsMs": 750,
        "type": "opportunity",
        "items": [
          {
            "node": {
              "snippet": "<img loading=\"lazy\" src=\"https://maitaneabad.github.io/fictitious-blog-cafe/img/blog3.webp\" alt=\"Imagen Blog\">",
              "nodeLabel": "Imagen Blog",
              "type": "node",
              "selector": "article.post > div.post__img > picture > img",
              "lhId": "page-2-IMG",
              "path": "1,HTML,1,BODY,1,DIV,0,MAIN,3,ARTICLE,0,DIV,0,PICTURE,1,IMG",
              "boundingRect": {
                "bottom": 2517,
                "height": 223,
                "top": 2295,
                "left": 18,
                "width": 324,
                "right": 342
              }
            },
            "totalBytes": 122812,
            "wastedPercent": 49.71096590909091,
            "wastedBytes": 61051,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog3.webp"
          },
          {
            "wastedBytes": 48012,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog1.webp",
            "node": {
              "path": "1,HTML,1,BODY,1,DIV,0,MAIN,1,ARTICLE,0,DIV,0,PICTURE,1,IMG",
              "nodeLabel": "Imagen Blog",
              "selector": "article.post > div.post__img > picture > img",
              "boundingRect": {
                "left": 18,
                "right": 342,
                "width": 324,
                "bottom": 925,
                "height": 223,
                "top": 702
              },
              "type": "node",
              "lhId": "page-0-IMG",
              "snippet": "<img loading=\"lazy\" src=\"https://maitaneabad.github.io/fictitious-blog-cafe/img/blog1.webp\" alt=\"Imagen Blog\">"
            },
            "totalBytes": 96582,
            "wastedPercent": 49.71096590909091
          },
          {
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/img/blog2.webp",
            "wastedPercent": 49.71096590909091,
            "node": {
              "selector": "article.post > div.post__img > picture > img",
              "path": "1,HTML,1,BODY,1,DIV,0,MAIN,2,ARTICLE,0,DIV,0,PICTURE,1,IMG",
              "boundingRect": {
                "left": 18,
                "right": 342,
                "bottom": 1704,
                "width": 324,
                "height": 223,
                "top": 1482
              },
              "type": "node",
              "lhId": "page-1-IMG",
              "snippet": "<img loading=\"lazy\" src=\"https://maitaneabad.github.io/fictitious-blog-cafe/img/blog2.webp\" alt=\"Imagen Blog\">",
              "nodeLabel": "Imagen Blog"
            },
            "totalBytes": 74266,
            "wastedBytes": 36918
          }
        ],
        "headings": [
          {
            "valueType": "node",
            "key": "node"
          },
          {
            "valueType": "url",
            "label": "URL",
            "key": "url"
          },
          {
            "key": "totalBytes",
            "valueType": "bytes",
            "label": "Resource Size"
          },
          {
            "key": "wastedBytes",
            "valueType": "bytes",
            "label": "Potential Savings"
          }
        ],
        "overallSavingsBytes": 145981
      },
      "numericValue": 750,
      "numericUnit": "millisecond"
    },
    "video-caption": {
      "id": "video-caption",
      "title": "`<video>` elements contain a `<track>` element with `[kind=\"captions\"]`",
      "description": "When a video provides a caption it is easier for deaf and hearing impaired users to access its information. [Learn more](https://web.dev/video-caption/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "color-contrast": {
      "id": "color-contrast",
      "title": "Background and foreground colors have a sufficient contrast ratio",
      "description": "Low-contrast text is difficult or impossible for many users to read. [Learn more](https://web.dev/color-contrast/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "legacy-javascript": {
      "id": "legacy-javascript",
      "title": "Avoid serving legacy JavaScript to modern browsers",
      "description": "Polyfills and transforms enable legacy browsers to use new JavaScript features. However, many aren't necessary for modern browsers. For your bundled JavaScript, adopt a modern script deployment strategy using module/nomodule feature detection to reduce the amount of code shipped to modern browsers, while retaining support for legacy browsers. [Learn More](https://philipwalton.com/articles/deploying-es2015-code-in-production-today/)",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "headings": [],
        "overallSavingsMs": 0,
        "items": [],
        "overallSavingsBytes": 0,
        "type": "opportunity"
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "long-tasks": {
      "id": "long-tasks",
      "title": "Avoid long main-thread tasks",
      "description": "Lists the longest tasks on the main thread, useful for identifying worst contributors to input delay. [Learn more](https://web.dev/long-tasks-devtools/)",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "1 long task found",
      "details": {
        "type": "table",
        "items": [
          {
            "duration": 257,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/",
            "startTime": 871
          }
        ],
        "headings": [
          {
            "key": "url",
            "text": "URL",
            "itemType": "url"
          },
          {
            "text": "Start Time",
            "key": "startTime",
            "itemType": "ms",
            "granularity": 1
          },
          {
            "key": "duration",
            "granularity": 1,
            "text": "Duration",
            "itemType": "ms"
          }
        ]
      }
    },
    "doctype": {
      "id": "doctype",
      "title": "Page has the HTML doctype",
      "description": "Specifying a doctype prevents the browser from switching to quirks-mode. [Learn more](https://web.dev/doctype/).",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "no-document-write": {
      "id": "no-document-write",
      "title": "Avoids `document.write()`",
      "description": "For users on slow connections, external scripts dynamically injected via `document.write()` can delay page load by tens of seconds. [Learn more](https://web.dev/no-document-write/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "use-landmarks": {
      "id": "use-landmarks",
      "title": "HTML5 landmark elements are used to improve navigation",
      "description": "Landmark elements (<main>, <nav>, etc.) are used to improve the keyboard navigation of the page for assistive technology. [Learn more](https://web.dev/use-landmarks/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "hreflang": {
      "id": "hreflang",
      "title": "Document has a valid `hreflang`",
      "description": "hreflang links tell search engines what version of a page they should list in search results for a given language or region. [Learn more](https://web.dev/hreflang/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "final-screenshot": {
      "id": "final-screenshot",
      "title": "Final Screenshot",
      "description": "The last screenshot captured of the pageload.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "data": "data:image/jpeg;base64,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",
        "timestamp": 1011786893572,
        "type": "screenshot",
        "timing": 581
      }
    },
    "offscreen-content-hidden": {
      "id": "offscreen-content-hidden",
      "title": "Offscreen content is hidden from assistive technology",
      "description": "Offscreen content is hidden with display: none or aria-hidden=true. [Learn more](https://web.dev/offscreen-content-hidden/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "third-party-facades": {
      "id": "third-party-facades",
      "title": "Lazy load third-party resources with facades",
      "description": "Some third-party embeds can be lazy loaded. Consider replacing them with a facade until they are required. [Learn more](https://web.dev/third-party-facades/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "image-aspect-ratio": {
      "id": "image-aspect-ratio",
      "title": "Displays images with correct aspect ratio",
      "description": "Image display dimensions should match natural aspect ratio. [Learn more](https://web.dev/image-aspect-ratio/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "aria-treeitem-name": {
      "id": "aria-treeitem-name",
      "title": "ARIA `treeitem` elements have accessible names",
      "description": "When an element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more](https://web.dev/aria-name/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "bootup-time": {
      "id": "bootup-time",
      "title": "JavaScript execution time",
      "description": "Consider reducing the time spent parsing, compiling, and executing JS. You may find delivering smaller JS payloads helps with this. [Learn more](https://web.dev/bootup-time/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "0.0 s",
      "details": {
        "headings": [
          {
            "text": "URL",
            "key": "url",
            "itemType": "url"
          },
          {
            "key": "total",
            "itemType": "ms",
            "granularity": 1,
            "text": "Total CPU Time"
          },
          {
            "key": "scripting",
            "text": "Script Evaluation",
            "granularity": 1,
            "itemType": "ms"
          },
          {
            "text": "Script Parse",
            "granularity": 1,
            "key": "scriptParseCompile",
            "itemType": "ms"
          }
        ],
        "type": "table",
        "summary": {
          "wastedMs": 30.727999999999998
        },
        "items": [
          {
            "scriptParseCompile": 5.516000000000001,
            "scripting": 11.879999999999997,
            "url": "https://maitaneabad.github.io/fictitious-blog-cafe/",
            "total": 453.592
          },
          {
            "scripting": 12.652000000000001,
            "scriptParseCompile": 0.6799999999999999,
            "url": "Unattributable",
            "total": 107.06400000000004
          }
        ]
      },
      "numericValue": 30.727999999999998,
      "numericUnit": "millisecond"
    }
  },
  "categories": {
    "performance": {
      "id": "performance",
      "title": "Performance",
      "score": 0.95,
      "auditRefs": [
        {
          "id": "first-contentful-paint",
          "weight": 10,
          "group": "metrics",
          "acronym": "FCP",
          "relevantAudits": [
            "server-response-time",
            "render-blocking-resources",
            "redirects",
            "critical-request-chains",
            "uses-text-compression",
            "uses-rel-preconnect",
            "uses-rel-preload",
            "font-display",
            "unminified-javascript",
            "unminified-css",
            "unused-css-rules"
          ]
        },
        {
          "id": "interactive",
          "weight": 10,
          "group": "metrics",
          "acronym": "TTI"
        },
        {
          "id": "speed-index",
          "weight": 10,
          "group": "metrics",
          "acronym": "SI"
        },
        {
          "id": "total-blocking-time",
          "weight": 30,
          "group": "metrics",
          "acronym": "TBT",
          "relevantAudits": [
            "long-tasks",
            "third-party-summary",
            "third-party-facades",
            "bootup-time",
            "mainthread-work-breakdown",
            "dom-size",
            "duplicated-javascript",
            "legacy-javascript",
            "viewport"
          ]
        },
        {
          "id": "largest-contentful-paint",
          "weight": 25,
          "group": "metrics",
          "acronym": "LCP",
          "relevantAudits": [
            "server-response-time",
            "render-blocking-resources",
            "redirects",
            "critical-request-chains",
            "uses-text-compression",
            "uses-rel-preconnect",
            "uses-rel-preload",
            "font-display",
            "unminified-javascript",
            "unminified-css",
            "unused-css-rules",
            "largest-contentful-paint-element",
            "preload-lcp-image",
            "unused-javascript",
            "efficient-animated-content",
            "total-byte-weight"
          ]
        },
        {
          "id": "cumulative-layout-shift",
          "weight": 15,
          "group": "metrics",
          "acronym": "CLS",
          "relevantAudits": [
            "layout-shift-elements",
            "non-composited-animations",
            "unsized-images"
          ]
        },
        {
          "id": "max-potential-fid",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "first-meaningful-paint",
          "weight": 0,
          "group": "hidden",
          "acronym": "FMP"
        },
        {
          "id": "render-blocking-resources",
          "weight": 0
        },
        {
          "id": "uses-responsive-images",
          "weight": 0
        },
        {
          "id": "offscreen-images",
          "weight": 0
        },
        {
          "id": "unminified-css",
          "weight": 0
        },
        {
          "id": "unminified-javascript",
          "weight": 0
        },
        {
          "id": "unused-css-rules",
          "weight": 0
        },
        {
          "id": "unused-javascript",
          "weight": 0
        },
        {
          "id": "uses-optimized-images",
          "weight": 0
        },
        {
          "id": "modern-image-formats",
          "weight": 0
        },
        {
          "id": "uses-text-compression",
          "weight": 0
        },
        {
          "id": "uses-rel-preconnect",
          "weight": 0
        },
        {
          "id": "server-response-time",
          "weight": 0
        },
        {
          "id": "redirects",
          "weight": 0
        },
        {
          "id": "uses-rel-preload",
          "weight": 0
        },
        {
          "id": "efficient-animated-content",
          "weight": 0
        },
        {
          "id": "duplicated-javascript",
          "weight": 0
        },
        {
          "id": "legacy-javascript",
          "weight": 0
        },
        {
          "id": "preload-lcp-image",
          "weight": 0
        },
        {
          "id": "total-byte-weight",
          "weight": 0
        },
        {
          "id": "uses-long-cache-ttl",
          "weight": 0
        },
        {
          "id": "dom-size",
          "weight": 0
        },
        {
          "id": "critical-request-chains",
          "weight": 0
        },
        {
          "id": "user-timings",
          "weight": 0
        },
        {
          "id": "bootup-time",
          "weight": 0
        },
        {
          "id": "mainthread-work-breakdown",
          "weight": 0
        },
        {
          "id": "font-display",
          "weight": 0
        },
        {
          "id": "resource-summary",
          "weight": 0
        },
        {
          "id": "third-party-summary",
          "weight": 0
        },
        {
          "id": "third-party-facades",
          "weight": 0
        },
        {
          "id": "largest-contentful-paint-element",
          "weight": 0
        },
        {
          "id": "lcp-lazy-loaded",
          "weight": 0
        },
        {
          "id": "layout-shift-elements",
          "weight": 0
        },
        {
          "id": "uses-passive-event-listeners",
          "weight": 0
        },
        {
          "id": "no-document-write",
          "weight": 0
        },
        {
          "id": "long-tasks",
          "weight": 0
        },
        {
          "id": "non-composited-animations",
          "weight": 0
        },
        {
          "id": "unsized-images",
          "weight": 0
        },
        {
          "id": "viewport",
          "weight": 0
        },
        {
          "id": "no-unload-listeners",
          "weight": 0
        },
        {
          "id": "performance-budget",
          "weight": 0,
          "group": "budgets"
        },
        {
          "id": "timing-budget",
          "weight": 0,
          "group": "budgets"
        },
        {
          "id": "network-requests",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "network-rtt",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "network-server-latency",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "main-thread-tasks",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "diagnostics",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "metrics",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "screenshot-thumbnails",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "final-screenshot",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "script-treemap-data",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "first-contentful-paint-3g",
          "weight": 0
        }
      ]
    },
    "accessibility": {
      "id": "accessibility",
      "title": "Accessibility",
      "description": "These checks highlight opportunities to [improve the accessibility of your web app](https://developers.google.com/web/fundamentals/accessibility). Only a subset of accessibility issues can be automatically detected so manual testing is also encouraged.",
      "score": 1,
      "manualDescription": "These items address areas which an automated testing tool cannot cover. Learn more in our guide on [conducting an accessibility review](https://developers.google.com/web/fundamentals/accessibility/how-to-review).",
      "auditRefs": [
        {
          "id": "accesskeys",
          "weight": 0,
          "group": "a11y-navigation"
        },
        {
          "id": "aria-allowed-attr",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-command-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-hidden-body",
          "weight": 10,
          "group": "a11y-aria"
        },
        {
          "id": "aria-hidden-focus",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-input-field-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-meter-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-progressbar-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-required-attr",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-required-children",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-required-parent",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-roles",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-toggle-field-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-tooltip-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-treeitem-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-valid-attr-value",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-valid-attr",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "button-name",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "bypass",
          "weight": 3,
          "group": "a11y-navigation"
        },
        {
          "id": "color-contrast",
          "weight": 3,
          "group": "a11y-color-contrast"
        },
        {
          "id": "definition-list",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "dlitem",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "document-title",
          "weight": 3,
          "group": "a11y-names-labels"
        },
        {
          "id": "duplicate-id-active",
          "weight": 0,
          "group": "a11y-navigation"
        },
        {
          "id": "duplicate-id-aria",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "form-field-multiple-labels",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "frame-title",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "heading-order",
          "weight": 2,
          "group": "a11y-navigation"
        },
        {
          "id": "html-has-lang",
          "weight": 3,
          "group": "a11y-language"
        },
        {
          "id": "html-lang-valid",
          "weight": 3,
          "group": "a11y-language"
        },
        {
          "id": "image-alt",
          "weight": 10,
          "group": "a11y-names-labels"
        },
        {
          "id": "input-image-alt",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "label",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "link-name",
          "weight": 3,
          "group": "a11y-names-labels"
        },
        {
          "id": "list",
          "weight": 3,
          "group": "a11y-tables-lists"
        },
        {
          "id": "listitem",
          "weight": 3,
          "group": "a11y-tables-lists"
        },
        {
          "id": "meta-refresh",
          "weight": 0,
          "group": "a11y-best-practices"
        },
        {
          "id": "meta-viewport",
          "weight": 10,
          "group": "a11y-best-practices"
        },
        {
          "id": "object-alt",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "tabindex",
          "weight": 0,
          "group": "a11y-navigation"
        },
        {
          "id": "td-headers-attr",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "th-has-data-cells",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "valid-lang",
          "weight": 0,
          "group": "a11y-language"
        },
        {
          "id": "video-caption",
          "weight": 0,
          "group": "a11y-audio-video"
        },
        {
          "id": "logical-tab-order",
          "weight": 0
        },
        {
          "id": "focusable-controls",
          "weight": 0
        },
        {
          "id": "interactive-element-affordance",
          "weight": 0
        },
        {
          "id": "managed-focus",
          "weight": 0
        },
        {
          "id": "focus-traps",
          "weight": 0
        },
        {
          "id": "custom-controls-labels",
          "weight": 0
        },
        {
          "id": "custom-controls-roles",
          "weight": 0
        },
        {
          "id": "visual-order-follows-dom",
          "weight": 0
        },
        {
          "id": "offscreen-content-hidden",
          "weight": 0
        },
        {
          "id": "use-landmarks",
          "weight": 0
        }
      ]
    },
    "best-practices": {
      "id": "best-practices",
      "title": "Best Practices",
      "score": 1,
      "auditRefs": [
        {
          "id": "is-on-https",
          "weight": 1,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "geolocation-on-start",
          "weight": 1,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "notification-on-start",
          "weight": 1,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "no-vulnerable-libraries",
          "weight": 1,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "csp-xss",
          "weight": 0,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "password-inputs-can-be-pasted-into",
          "weight": 1,
          "group": "best-practices-ux"
        },
        {
          "id": "image-aspect-ratio",
          "weight": 1,
          "group": "best-practices-ux"
        },
        {
          "id": "image-size-responsive",
          "weight": 1,
          "group": "best-practices-ux"
        },
        {
          "id": "preload-fonts",
          "weight": 0,
          "group": "best-practices-ux"
        },
        {
          "id": "doctype",
          "weight": 1,
          "group": "best-practices-browser-compat"
        },
        {
          "id": "charset",
          "weight": 1,
          "group": "best-practices-browser-compat"
        },
        {
          "id": "js-libraries",
          "weight": 0,
          "group": "best-practices-general"
        },
        {
          "id": "deprecations",
          "weight": 1,
          "group": "best-practices-general"
        },
        {
          "id": "errors-in-console",
          "weight": 1,
          "group": "best-practices-general"
        },
        {
          "id": "valid-source-maps",
          "weight": 0,
          "group": "best-practices-general"
        },
        {
          "id": "inspector-issues",
          "weight": 1,
          "group": "best-practices-general"
        }
      ]
    },
    "seo": {
      "id": "seo",
      "title": "SEO",
      "description": "These checks ensure that your page is following basic search engine optimization advice. There are many additional factors Lighthouse does not score here that may affect your search ranking, including performance on [Core Web Vitals](https://web.dev/learn-web-vitals/). [Learn more](https://support.google.com/webmasters/answer/35769).",
      "score": 1,
      "manualDescription": "Run these additional validators on your site to check additional SEO best practices.",
      "auditRefs": [
        {
          "id": "viewport",
          "weight": 1,
          "group": "seo-mobile"
        },
        {
          "id": "document-title",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "meta-description",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "http-status-code",
          "weight": 1,
          "group": "seo-crawl"
        },
        {
          "id": "link-text",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "crawlable-anchors",
          "weight": 1,
          "group": "seo-crawl"
        },
        {
          "id": "is-crawlable",
          "weight": 1,
          "group": "seo-crawl"
        },
        {
          "id": "robots-txt",
          "weight": 0,
          "group": "seo-crawl"
        },
        {
          "id": "image-alt",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "hreflang",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "canonical",
          "weight": 0,
          "group": "seo-content"
        },
        {
          "id": "font-size",
          "weight": 1,
          "group": "seo-mobile"
        },
        {
          "id": "plugins",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "tap-targets",
          "weight": 1,
          "group": "seo-mobile"
        },
        {
          "id": "structured-data",
          "weight": 0
        }
      ]
    },
    "pwa": {
      "id": "pwa",
      "title": "PWA",
      "description": "These checks validate the aspects of a Progressive Web App. [Learn more](https://developers.google.com/web/progressive-web-apps/checklist).",
      "score": 0.3,
      "manualDescription": "These checks are required by the baseline [PWA Checklist](https://developers.google.com/web/progressive-web-apps/checklist) but are not automatically checked by Lighthouse. They do not affect your score but it's important that you verify them manually.",
      "auditRefs": [
        {
          "id": "installable-manifest",
          "weight": 2,
          "group": "pwa-installable"
        },
        {
          "id": "service-worker",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "splash-screen",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "themed-omnibox",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "content-width",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "viewport",
          "weight": 2,
          "group": "pwa-optimized"
        },
        {
          "id": "apple-touch-icon",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "maskable-icon",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "pwa-cross-browser",
          "weight": 0
        },
        {
          "id": "pwa-page-transitions",
          "weight": 0
        },
        {
          "id": "pwa-each-page-has-url",
          "weight": 0
        }
      ]
    }
  },
  "categoryGroups": {
    "metrics": {
      "title": "Metrics"
    },
    "budgets": {
      "title": "Budgets",
      "description": "Performance budgets set standards for the performance of your site."
    },
    "a11y-color-contrast": {
      "title": "Contrast",
      "description": "These are opportunities to improve the legibility of your content."
    },
    "seo-mobile": {
      "title": "Mobile Friendly",
      "description": "Make sure your pages are mobile friendly so users don’t have to pinch or zoom in order to read the content pages. [Learn more](https://developers.google.com/search/mobile-sites/)."
    },
    "a11y-aria": {
      "title": "ARIA",
      "description": "These are opportunities to improve the usage of ARIA in your application which may enhance the experience for users of assistive technology, like a screen reader."
    },
    "a11y-language": {
      "title": "Internationalization and localization",
      "description": "These are opportunities to improve the interpretation of your content by users in different locales."
    },
    "a11y-navigation": {
      "title": "Navigation",
      "description": "These are opportunities to improve keyboard navigation in your application."
    },
    "pwa-installable": {
      "title": "Installable"
    },
    "a11y-best-practices": {
      "title": "Best practices",
      "description": "These items highlight common accessibility best practices."
    },
    "seo-crawl": {
      "title": "Crawling and Indexing",
      "description": "To appear in search results, crawlers need access to your app."
    },
    "best-practices-browser-compat": {
      "title": "Browser Compatibility"
    },
    "pwa-optimized": {
      "title": "PWA Optimized"
    },
    "a11y-audio-video": {
      "title": "Audio and video",
      "description": "These are opportunities to provide alternative content for audio and video. This may improve the experience for users with hearing or vision impairments."
    },
    "load-opportunities": {
      "title": "Opportunities",
      "description": "These suggestions can help your page load faster. They don't [directly affect](https://web.dev/performance-scoring/) the Performance score."
    },
    "diagnostics": {
      "title": "Diagnostics",
      "description": "More information about the performance of your application. These numbers don't [directly affect](https://web.dev/performance-scoring/) the Performance score."
    },
    "best-practices-ux": {
      "title": "User Experience"
    },
    "best-practices-trust-safety": {
      "title": "Trust and Safety"
    },
    "seo-content": {
      "title": "Content Best Practices",
      "description": "Format your HTML in a way that enables crawlers to better understand your app’s content."
    },
    "a11y-tables-lists": {
      "title": "Tables and lists",
      "description": "These are opportunities to improve the experience of reading tabular or list data using assistive technology, like a screen reader."
    },
    "a11y-names-labels": {
      "title": "Names and labels",
      "description": "These are opportunities to improve the semantics of the controls in your application. This may enhance the experience for users of assistive technology, like a screen reader."
    },
    "best-practices-general": {
      "title": "General"
    }
  },
  "timing": {
    "total": 7921.8
  },
  "i18n": {
    "rendererFormattedStrings": {
      "varianceDisclaimer": "Values are estimated and may vary. The [performance score is calculated](https://web.dev/performance-scoring/) directly from these metrics.",
      "opportunityResourceColumnLabel": "Opportunity",
      "opportunitySavingsColumnLabel": "Estimated Savings",
      "errorMissingAuditInfo": "Report error: no audit information",
      "errorLabel": "Error!",
      "warningHeader": "Warnings: ",
      "passedAuditsGroupTitle": "Passed audits",
      "notApplicableAuditsGroupTitle": "Not applicable",
      "manualAuditsGroupTitle": "Additional items to manually check",
      "toplevelWarningsMessage": "There were issues affecting this run of Lighthouse:",
      "crcLongestDurationLabel": "Maximum critical path latency:",
      "crcInitialNavigation": "Initial Navigation",
      "lsPerformanceCategoryDescription": "[Lighthouse](https://developers.google.com/web/tools/lighthouse/) analysis of the current page on an emulated mobile network. Values are estimated and may vary.",
      "labDataTitle": "Lab Data",
      "warningAuditsGroupTitle": "Passed audits but with warnings",
      "snippetExpandButtonLabel": "Expand snippet",
      "snippetCollapseButtonLabel": "Collapse snippet",
      "thirdPartyResourcesLabel": "Show 3rd-party resources",
      "runtimeDesktopEmulation": "Emulated Desktop",
      "runtimeMobileEmulation": "Emulated Moto G4",
      "runtimeNoEmulation": "No emulation",
      "runtimeSettingsBenchmark": "CPU/Memory Power",
      "runtimeSettingsCPUThrottling": "CPU throttling",
      "runtimeSettingsDevice": "Device",
      "runtimeSettingsNetworkThrottling": "Network throttling",
      "runtimeSettingsUANetwork": "User agent (network)",
      "runtimeUnknown": "Unknown",
      "dropdownCopyJSON": "Copy JSON",
      "dropdownDarkTheme": "Toggle Dark Theme",
      "dropdownPrintExpanded": "Print Expanded",
      "dropdownPrintSummary": "Print Summary",
      "dropdownSaveGist": "Save as Gist",
      "dropdownSaveHTML": "Save as HTML",
      "dropdownSaveJSON": "Save as JSON",
      "dropdownViewer": "Open in Viewer",
      "footerIssue": "File an issue",
      "throttlingProvided": "Provided by environment",
      "calculatorLink": "See calculator.",
      "runtimeSettingsAxeVersion": "Axe version",
      "viewTreemapLabel": "View Treemap",
      "showRelevantAudits": "Show audits relevant to:"
    }
  }
}
