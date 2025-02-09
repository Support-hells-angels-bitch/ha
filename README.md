# ha
developer tools, out of trailer 16 kenyon mn 55946
/*!
 * Bootstrap v4.0.0 (https://getbootstrap.com)
 * Copyright 2011-2018 The Bootstrap Authors
 * Copyright 2011-2018 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
*,
*::before,
*::after {
	box-sizing: border-box;
}

html {
	font-family: "Averia Libre";
	line-height: 1.15;
	-webkit-text-size-adjust: 100%;
	-ms-text-size-adjust: 100%;
	-ms-overflow-style: scrollbar;
	-webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

@-ms-viewport {
	width: device-width;
}

article, aside, dialog, figcaption, figure, footer, header, hgroup, main, nav, section {
	display: block;
}

body {
	margin: 0;
	font-family: "Averia Libre";
	font-size: 16px;
	font-weight: 300;
	line-height: 1.4875;
	color: #74757f;
	text-align: left;
	background-color: #fff;
}

[tabindex="-1"]:focus {
	outline: 0 !important;
}

hr {
	box-sizing: content-box;
	height: 0;
	overflow: visible;
}

h1, h2, h3, h4, h5, h6 {
	margin-top: 0;
	margin-bottom: 0.5rem;
}

p {
	margin-top: 0;
	margin-bottom: 1rem;
}

abbr[title],
abbr[data-original-title] {
	text-decoration: underline;
	text-decoration: underline dotted;
	cursor: help;
	border-bottom: 0;
}

address {
	margin-bottom: 1rem;
	font-style: normal;
	line-height: inherit;
}

ol,
ul,
dl {
	margin-top: 0;
	margin-bottom: 1rem;
}

ol ol,
ul ul,
ol ul,
ul ol {
	margin-bottom: 0;
}

dt {
	font-weight: inherit;
}

dd {
	margin-bottom: .5rem;
	margin-left: 0;
}

blockquote {
	margin: 0 0 1rem;
}

dfn {
	font-style: italic;
}

b,
strong {
	font-weight: bolder;
}

small {
	font-size: 80%;
}

sub,
sup {
	position: relative;
	font-size: 75%;
	line-height: 0;
	vertical-align: baseline;
}

sub {
	bottom: -.25em;
}

sup {
	top: -.5em;
}

a {
	color: #248cce;
	text-decoration: none;
	background-color: transparent;
	-webkit-text-decoration-skip: objects;
}

a:hover {
	color: #790420;
	text-decoration: underline;
}

a:not([href]):not([tabindex]) {
	color: inherit;
	text-decoration: none;
}
a:not([href]):not([tabindex]):hover, a:not([href]):not([tabindex]):focus {
	color: inherit;
	text-decoration: none;
}

a:not([href]):not([tabindex]):focus {
	outline: 0;
}

pre,
code,
kbd,
samp {
	font-family: monospace, monospace;
	font-size: 1em;
}

pre {
	margin-top: 0;
	margin-bottom: 1rem;
	overflow: auto;
	-ms-overflow-style: scrollbar;
}

figure {
	margin: 0 0 1rem;
}

img {
	vertical-align: middle;
	border-style: none;
}

svg:not(:root) {
	overflow: hidden;
}

table {
	border-collapse: collapse;
}

caption {
	padding-top: 0.75rem;
	padding-bottom: 0.75rem;
	color: #6c757d;
	text-align: left;
	caption-side: bottom;
}

th {
	text-align: inherit;
}

label {
	display: inline-block;
	margin-bottom: .5rem;
}

button {
	border-radius: 0;
}

button:focus {
	outline: 1px dotted;
	outline: 5px auto -webkit-focus-ring-color;
}

input,
button,
select,
optgroup,
textarea {
	margin: 0;
	font-family: inherit;
	font-size: inherit;
	line-height: inherit;
}

button,
input {
	overflow: visible;
}

button,
select {
	text-transform: none;
}

button,
html [type="button"],
[type="reset"],
[type="submit"] {
	-webkit-appearance: button;
}

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
	padding: 0;
	border-style: none;
}

input[type="radio"],
input[type="checkbox"] {
	box-sizing: border-box;
	padding: 0;
}

input[type="date"],
input[type="time"],
input[type="datetime-local"],
input[type="month"] {
	-webkit-appearance: listbox;
}

textarea {
	overflow: auto;
	resize: vertical;
}

fieldset {
	min-width: 0;
	padding: 0;
	margin: 0;
	border: 0;
}

legend {
	display: block;
	width: 100%;
	max-width: 100%;
	padding: 0;
	margin-bottom: .5rem;
	font-size: 1.5rem;
	line-height: inherit;
	color: inherit;
	white-space: normal;
}

progress {
	vertical-align: baseline;
}

[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
	height: auto;
}

[type="search"] {
	outline-offset: -2px;
	-webkit-appearance: none;
}

[type="search"]::-webkit-search-cancel-button,
[type="search"]::-webkit-search-decoration {
	-webkit-appearance: none;
}

::-webkit-file-upload-button {
	font: inherit;
	-webkit-appearance: button;
}

output {
	display: inline-block;
}

summary {
	display: list-item;
	cursor: pointer;
}

template {
	display: none;
}

[hidden] {
	display: none !important;
}

h1, h2, h3, h4, h5, h6,
.h1, .h2, .h3, .h4, .h5, .h6 {
	margin-bottom: 0.5rem;
	font-family: "Averia Libre";
	font-weight: 400;
	line-height: 1.1;
	color: #29293a;
}

h1, .h1 {
	font-size: 68px;
}

h2, .h2 {
	font-size: 48px;
}

h3, .h3 {
	font-size: 36px;
}

h4, .h4 {
	font-size: 24px;
}

h5, .h5 {
	font-size: 20px;
}

h6, .h6 {
	font-size: 16px;
}

.lead {
	font-size: 24px;
	font-weight: 300;
}

.display-1 {
	font-size: 6rem;
	font-weight: 300;
	line-height: 1.2;
}

.display-2 {
	font-size: 5.5rem;
	font-weight: 300;
	line-height: 1.2;
}

.display-3 {
	font-size: 4.5rem;
	font-weight: 300;
	line-height: 1.2;
}

.display-4 {
	font-size: 3.5rem;
	font-weight: 300;
	line-height: 1.2;
}

hr {
	margin-top: 1rem;
	margin-bottom: 1rem;
	border: 0;
	border-top: 1px solid #e8e9ee;
}

small,
.small {
	font-size: 80%;
	font-weight: 400;
}

mark,
.mark {
	padding: 5px 10px;
	background-color: #248cce;
}

.list-unstyled {
	padding-left: 0;
	list-style: none;
}

.list-inline {
	padding-left: 0;
	list-style: none;
}

.list-inline-item {
	display: inline-block;
}

.list-inline-item:not(:last-child) {
	margin-right: 5px;
}

.initialism {
	font-size: 90%;
	text-transform: uppercase;
}

.blockquote {
	margin-bottom: 1rem;
	font-size: 1.25rem;
}

.blockquote-footer {
	display: block;
	font-size: 80%;
	color: #6c757d;
}

.blockquote-footer::before {
	content: "\2014 \00A0";
}

.img-fluid {
	max-width: 100%;
	height: auto;
}

.img-thumbnail {
	padding: 0.25rem;
	background-color: #fff;
	border: 1px solid #dee2e6;
	border-radius: 0.25rem;
	max-width: 100%;
	height: auto;
}

.figure {
	display: inline-block;
}

.figure-img {
	margin-bottom: 0.5rem;
	line-height: 1;
}

.figure-caption {
	font-size: 90%;
	color: #6c757d;
}

code,
kbd,
pre,
samp {
	font-family: Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
}

code {
	font-size: 90%;
	color: #111111;
	word-break: break-word;
}

a > code {
	color: inherit;
}

kbd {
	padding: 0.2rem 0.4rem;
	font-size: 87.5%;
	color: #fff;
	background-color: #212529;
	border-radius: 0.2rem;
}

kbd kbd {
	padding: 0;
	font-size: 100%;
	font-weight: 700;
}

pre {
	display: block;
	font-size: 90%;
	color: #212529;
}

pre code {
	font-size: inherit;
	color: inherit;
	word-break: normal;
}

.pre-scrollable {
	max-height: 340px;
	overflow-y: scroll;
}

.container {
	width: 100%;
	padding-right: 15px;
	padding-left: 15px;
	margin-right: auto;
	margin-left: auto;
}

@media (min-width: 576px) {
	.container {
		max-width: 540px;
	}
}

@media (min-width: 768px) {
	.container {
		max-width: 720px;
	}
}

@media (min-width: 992px) {
	.container {
		max-width: 960px;
	}
}

@media (min-width: 1200px) {
	.container {
		max-width: 1200px;
	}
}

.container-fluid {
	width: 100%;
	padding-right: 15px;
	padding-left: 15px;
	margin-right: auto;
	margin-left: auto;
}

.row {
	display: flex;
	flex-wrap: wrap;
	margin-right: -15px;
	margin-left: -15px;
}

.no-gutters {
	margin-right: 0;
	margin-left: 0;
}

.no-gutters > .col,
.no-gutters > [class*="col-"] {
	padding-right: 0;
	padding-left: 0;
}

.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12, .col,
.col-auto, .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm,
.col-sm-auto, .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12, .col-md,
.col-md-auto, .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg,
.col-lg-auto, .col-xl-1, .col-xl-2, .col-xl-3, .col-xl-4, .col-xl-5, .col-xl-6, .col-xl-7, .col-xl-8, .col-xl-9, .col-xl-10, .col-xl-11, .col-xl-12, .col-xl,
.col-xl-auto, .col-xxl-1, .col-xxl-2, .col-xxl-3, .col-xxl-4, .col-xxl-5, .col-xxl-6, .col-xxl-7, .col-xxl-8, .col-xxl-9, .col-xxl-10, .col-xxl-11, .col-xxl-12, .col-xxl,
.col-xxl-auto {
	position: relative;
	width: 100%;
	min-height: 1px;
	padding-right: 15px;
	padding-left: 15px;
}

.col {
	flex-basis: 0;
	flex-grow: 1;
	max-width: 100%;
}

.col-auto {
	flex: 0 0 auto;
	width: auto;
	max-width: none;
}

.col-1 {
	flex: 0 0 8.33333%;
	max-width: 8.33333%;
}

.col-2 {
	flex: 0 0 16.66667%;
	max-width: 16.66667%;
}

.col-3 {
	flex: 0 0 25%;
	max-width: 25%;
}

.col-4 {
	flex: 0 0 33.33333%;
	max-width: 33.33333%;
}

.col-5 {
	flex: 0 0 41.66667%;
	max-width: 41.66667%;
}

.col-6 {
	flex: 0 0 50%;
	max-width: 50%;
}

.col-7 {
	flex: 0 0 58.33333%;
	max-width: 58.33333%;
}

.col-8 {
	flex: 0 0 66.66667%;
	max-width: 66.66667%;
}

.col-9 {
	flex: 0 0 75%;
	max-width: 75%;
}

.col-10 {
	flex: 0 0 83.33333%;
	max-width: 83.33333%;
}

.col-11 {
	flex: 0 0 91.66667%;
	max-width: 91.66667%;
}

.col-12 {
	flex: 0 0 100%;
	max-width: 100%;
}

.order-first {
	order: -1;
}

.order-last {
	order: 13;
}

.order-0 {
	order: 0;
}

.order-1 {
	order: 1;
}

.order-2 {
	order: 2;
}

.order-3 {
	order: 3;
}

.order-4 {
	order: 4;
}

.order-5 {
	order: 5;
}

.order-6 {
	order: 6;
}

.order-7 {
	order: 7;
}

.order-8 {
	order: 8;
}

.order-9 {
	order: 9;
}

.order-10 {
	order: 10;
}

.order-11 {
	order: 11;
}

.order-12 {
	order: 12;
}

.offset-1 {
	margin-left: 8.33333%;
}

.offset-2 {
	margin-left: 16.66667%;
}

.offset-3 {
	margin-left: 25%;
}

.offset-4 {
	margin-left: 33.33333%;
}

.offset-5 {
	margin-left: 41.66667%;
}

.offset-6 {
	margin-left: 50%;
}

.offset-7 {
	margin-left: 58.33333%;
}

.offset-8 {
	margin-left: 66.66667%;
}

.offset-9 {
	margin-left: 75%;
}

.offset-10 {
	margin-left: 83.33333%;
}

.offset-11 {
	margin-left: 91.66667%;
}

@media (min-width: 576px) {
	.col-sm {
		flex-basis: 0;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-sm-auto {
		flex: 0 0 auto;
		width: auto;
		max-width: none;
	}
	.col-sm-1 {
		flex: 0 0 8.33333%;
		max-width: 8.33333%;
	}
	.col-sm-2 {
		flex: 0 0 16.66667%;
		max-width: 16.66667%;
	}
	.col-sm-3 {
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-sm-4 {
		flex: 0 0 33.33333%;
		max-width: 33.33333%;
	}
	.col-sm-5 {
		flex: 0 0 41.66667%;
		max-width: 41.66667%;
	}
	.col-sm-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-sm-7 {
		flex: 0 0 58.33333%;
		max-width: 58.33333%;
	}
	.col-sm-8 {
		flex: 0 0 66.66667%;
		max-width: 66.66667%;
	}
	.col-sm-9 {
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-sm-10 {
		flex: 0 0 83.33333%;
		max-width: 83.33333%;
	}
	.col-sm-11 {
		flex: 0 0 91.66667%;
		max-width: 91.66667%;
	}
	.col-sm-12 {
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-sm-first {
		order: -1;
	}
	.order-sm-last {
		order: 13;
	}
	.order-sm-0 {
		order: 0;
	}
	.order-sm-1 {
		order: 1;
	}
	.order-sm-2 {
		order: 2;
	}
	.order-sm-3 {
		order: 3;
	}
	.order-sm-4 {
		order: 4;
	}
	.order-sm-5 {
		order: 5;
	}
	.order-sm-6 {
		order: 6;
	}
	.order-sm-7 {
		order: 7;
	}
	.order-sm-8 {
		order: 8;
	}
	.order-sm-9 {
		order: 9;
	}
	.order-sm-10 {
		order: 10;
	}
	.order-sm-11 {
		order: 11;
	}
	.order-sm-12 {
		order: 12;
	}
	.offset-sm-0 {
		margin-left: 0;
	}
	.offset-sm-1 {
		margin-left: 8.33333%;
	}
	.offset-sm-2 {
		margin-left: 16.66667%;
	}
	.offset-sm-3 {
		margin-left: 25%;
	}
	.offset-sm-4 {
		margin-left: 33.33333%;
	}
	.offset-sm-5 {
		margin-left: 41.66667%;
	}
	.offset-sm-6 {
		margin-left: 50%;
	}
	.offset-sm-7 {
		margin-left: 58.33333%;
	}
	.offset-sm-8 {
		margin-left: 66.66667%;
	}
	.offset-sm-9 {
		margin-left: 75%;
	}
	.offset-sm-10 {
		margin-left: 83.33333%;
	}
	.offset-sm-11 {
		margin-left: 91.66667%;
	}
}

@media (min-width: 768px) {
	.col-md {
		flex-basis: 0;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-md-auto {
		flex: 0 0 auto;
		width: auto;
		max-width: none;
	}
	.col-md-1 {
		flex: 0 0 8.33333%;
		max-width: 8.33333%;
	}
	.col-md-2 {
		flex: 0 0 16.66667%;
		max-width: 16.66667%;
	}
	.col-md-3 {
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-md-4 {
		flex: 0 0 33.33333%;
		max-width: 33.33333%;
	}
	.col-md-5 {
		flex: 0 0 41.66667%;
		max-width: 41.66667%;
	}
	.col-md-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-md-7 {
		flex: 0 0 58.33333%;
		max-width: 58.33333%;
	}
	.col-md-8 {
		flex: 0 0 66.66667%;
		max-width: 66.66667%;
	}
	.col-md-9 {
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-md-10 {
		flex: 0 0 83.33333%;
		max-width: 83.33333%;
	}
	.col-md-11 {
		flex: 0 0 91.66667%;
		max-width: 91.66667%;
	}
	.col-md-12 {
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-md-first {
		order: -1;
	}
	.order-md-last {
		order: 13;
	}
	.order-md-0 {
		order: 0;
	}
	.order-md-1 {
		order: 1;
	}
	.order-md-2 {
		order: 2;
	}
	.order-md-3 {
		order: 3;
	}
	.order-md-4 {
		order: 4;
	}
	.order-md-5 {
		order: 5;
	}
	.order-md-6 {
		order: 6;
	}
	.order-md-7 {
		order: 7;
	}
	.order-md-8 {
		order: 8;
	}
	.order-md-9 {
		order: 9;
	}
	.order-md-10 {
		order: 10;
	}
	.order-md-11 {
		order: 11;
	}
	.order-md-12 {
		order: 12;
	}
	.offset-md-0 {
		margin-left: 0;
	}
	.offset-md-1 {
		margin-left: 8.33333%;
	}
	.offset-md-2 {
		margin-left: 16.66667%;
	}
	.offset-md-3 {
		margin-left: 25%;
	}
	.offset-md-4 {
		margin-left: 33.33333%;
	}
	.offset-md-5 {
		margin-left: 41.66667%;
	}
	.offset-md-6 {
		margin-left: 50%;
	}
	.offset-md-7 {
		margin-left: 58.33333%;
	}
	.offset-md-8 {
		margin-left: 66.66667%;
	}
	.offset-md-9 {
		margin-left: 75%;
	}
	.offset-md-10 {
		margin-left: 83.33333%;
	}
	.offset-md-11 {
		margin-left: 91.66667%;
	}
}

@media (min-width: 992px) {
	.col-lg {
		flex-basis: 0;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-lg-auto {
		flex: 0 0 auto;
		width: auto;
		max-width: none;
	}
	.col-lg-1 {
		flex: 0 0 8.33333%;
		max-width: 8.33333%;
	}
	.col-lg-2 {
		flex: 0 0 16.66667%;
		max-width: 16.66667%;
	}
	.col-lg-3 {
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-lg-4 {
		flex: 0 0 33.33333%;
		max-width: 33.33333%;
	}
	.col-lg-5 {
		flex: 0 0 41.66667%;
		max-width: 41.66667%;
	}
	.col-lg-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-lg-7 {
		flex: 0 0 58.33333%;
		max-width: 58.33333%;
	}
	.col-lg-8 {
		flex: 0 0 66.66667%;
		max-width: 66.66667%;
	}
	.col-lg-9 {
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-lg-10 {
		flex: 0 0 83.33333%;
		max-width: 83.33333%;
	}
	.col-lg-11 {
		flex: 0 0 91.66667%;
		max-width: 91.66667%;
	}
	.col-lg-12 {
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-lg-first {
		order: -1;
	}
	.order-lg-last {
		order: 13;
	}
	.order-lg-0 {
		order: 0;
	}
	.order-lg-1 {
		order: 1;
	}
	.order-lg-2 {
		order: 2;
	}
	.order-lg-3 {
		order: 3;
	}
	.order-lg-4 {
		order: 4;
	}
	.order-lg-5 {
		order: 5;
	}
	.order-lg-6 {
		order: 6;
	}
	.order-lg-7 {
		order: 7;
	}
	.order-lg-8 {
		order: 8;
	}
	.order-lg-9 {
		order: 9;
	}
	.order-lg-10 {
		order: 10;
	}
	.order-lg-11 {
		order: 11;
	}
	.order-lg-12 {
		order: 12;
	}
	.offset-lg-0 {
		margin-left: 0;
	}
	.offset-lg-1 {
		margin-left: 8.33333%;
	}
	.offset-lg-2 {
		margin-left: 16.66667%;
	}
	.offset-lg-3 {
		margin-left: 25%;
	}
	.offset-lg-4 {
		margin-left: 33.33333%;
	}
	.offset-lg-5 {
		margin-left: 41.66667%;
	}
	.offset-lg-6 {
		margin-left: 50%;
	}
	.offset-lg-7 {
		margin-left: 58.33333%;
	}
	.offset-lg-8 {
		margin-left: 66.66667%;
	}
	.offset-lg-9 {
		margin-left: 75%;
	}
	.offset-lg-10 {
		margin-left: 83.33333%;
	}
	.offset-lg-11 {
		margin-left: 91.66667%;
	}
}

@media (min-width: 1200px) {
	.col-xl {
		flex-basis: 0;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-xl-auto {
		flex: 0 0 auto;
		width: auto;
		max-width: none;
	}
	.col-xl-1 {
		flex: 0 0 8.33333%;
		max-width: 8.33333%;
	}
	.col-xl-2 {
		flex: 0 0 16.66667%;
		max-width: 16.66667%;
	}
	.col-xl-3 {
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-xl-4 {
		flex: 0 0 33.33333%;
		max-width: 33.33333%;
	}
	.col-xl-5 {
		flex: 0 0 41.66667%;
		max-width: 41.66667%;
	}
	.col-xl-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-xl-7 {
		flex: 0 0 58.33333%;
		max-width: 58.33333%;
	}
	.col-xl-8 {
		flex: 0 0 66.66667%;
		max-width: 66.66667%;
	}
	.col-xl-9 {
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-xl-10 {
		flex: 0 0 83.33333%;
		max-width: 83.33333%;
	}
	.col-xl-11 {
		flex: 0 0 91.66667%;
		max-width: 91.66667%;
	}
	.col-xl-12 {
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-xl-first {
		order: -1;
	}
	.order-xl-last {
		order: 13;
	}
	.order-xl-0 {
		order: 0;
	}
	.order-xl-1 {
		order: 1;
	}
	.order-xl-2 {
		order: 2;
	}
	.order-xl-3 {
		order: 3;
	}
	.order-xl-4 {
		order: 4;
	}
	.order-xl-5 {
		order: 5;
	}
	.order-xl-6 {
		order: 6;
	}
	.order-xl-7 {
		order: 7;
	}
	.order-xl-8 {
		order: 8;
	}
	.order-xl-9 {
		order: 9;
	}
	.order-xl-10 {
		order: 10;
	}
	.order-xl-11 {
		order: 11;
	}
	.order-xl-12 {
		order: 12;
	}
	.offset-xl-0 {
		margin-left: 0;
	}
	.offset-xl-1 {
		margin-left: 8.33333%;
	}
	.offset-xl-2 {
		margin-left: 16.66667%;
	}
	.offset-xl-3 {
		margin-left: 25%;
	}
	.offset-xl-4 {
		margin-left: 33.33333%;
	}
	.offset-xl-5 {
		margin-left: 41.66667%;
	}
	.offset-xl-6 {
		margin-left: 50%;
	}
	.offset-xl-7 {
		margin-left: 58.33333%;
	}
	.offset-xl-8 {
		margin-left: 66.66667%;
	}
	.offset-xl-9 {
		margin-left: 75%;
	}
	.offset-xl-10 {
		margin-left: 83.33333%;
	}
	.offset-xl-11 {
		margin-left: 91.66667%;
	}
}

@media (min-width: 1600px) {
	.col-xxl {
		flex-basis: 0;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-xxl-auto {
		flex: 0 0 auto;
		width: auto;
		max-width: none;
	}
	.col-xxl-1 {
		flex: 0 0 8.33333%;
		max-width: 8.33333%;
	}
	.col-xxl-2 {
		flex: 0 0 16.66667%;
		max-width: 16.66667%;
	}
	.col-xxl-3 {
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-xxl-4 {
		flex: 0 0 33.33333%;
		max-width: 33.33333%;
	}
	.col-xxl-5 {
		flex: 0 0 41.66667%;
		max-width: 41.66667%;
	}
	.col-xxl-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-xxl-7 {
		flex: 0 0 58.33333%;
		max-width: 58.33333%;
	}
	.col-xxl-8 {
		flex: 0 0 66.66667%;
		max-width: 66.66667%;
	}
	.col-xxl-9 {
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-xxl-10 {
		flex: 0 0 83.33333%;
		max-width: 83.33333%;
	}
	.col-xxl-11 {
		flex: 0 0 91.66667%;
		max-width: 91.66667%;
	}
	.col-xxl-12 {
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-xxl-first {
		order: -1;
	}
	.order-xxl-last {
		order: 13;
	}
	.order-xxl-0 {
		order: 0;
	}
	.order-xxl-1 {
		order: 1;
	}
	.order-xxl-2 {
		order: 2;
	}
	.order-xxl-3 {
		order: 3;
	}
	.order-xxl-4 {
		order: 4;
	}
	.order-xxl-5 {
		order: 5;
	}
	.order-xxl-6 {
		order: 6;
	}
	.order-xxl-7 {
		order: 7;
	}
	.order-xxl-8 {
		order: 8;
	}
	.order-xxl-9 {
		order: 9;
	}
	.order-xxl-10 {
		order: 10;
	}
	.order-xxl-11 {
		order: 11;
	}
	.order-xxl-12 {
		order: 12;
	}
	.offset-xxl-0 {
		margin-left: 0;
	}
	.offset-xxl-1 {
		margin-left: 8.33333%;
	}
	.offset-xxl-2 {
		margin-left: 16.66667%;
	}
	.offset-xxl-3 {
		margin-left: 25%;
	}
	.offset-xxl-4 {
		margin-left: 33.33333%;
	}
	.offset-xxl-5 {
		margin-left: 41.66667%;
	}
	.offset-xxl-6 {
		margin-left: 50%;
	}
	.offset-xxl-7 {
		margin-left: 58.33333%;
	}
	.offset-xxl-8 {
		margin-left: 66.66667%;
	}
	.offset-xxl-9 {
		margin-left: 75%;
	}
	.offset-xxl-10 {
		margin-left: 83.33333%;
	}
	.offset-xxl-11 {
		margin-left: 91.66667%;
	}
}

.table {
	width: 100%;
	max-width: 100%;
	margin-bottom: 1rem;
	background-color: transparent;
}

.table th,
.table td {
	padding: 0.75rem;
	vertical-align: top;
	border-top: 1px solid #dee2e6;
}

.table thead th {
	vertical-align: bottom;
	border-bottom: 2px solid #dee2e6;
}

.table tbody + tbody {
	border-top: 2px solid #dee2e6;
}

.table .table {
	background-color: #fff;
}

.table-sm th,
.table-sm td {
	padding: 0.3rem;
}

.table-bordered {
	border: 1px solid #dee2e6;
}

.table-bordered th,
.table-bordered td {
	border: 1px solid #dee2e6;
}

.table-bordered thead th,
.table-bordered thead td {
	border-bottom-width: 2px;
}

.table-striped tbody tr:nth-of-type(odd) {
	background-color: rgba(0, 0, 0, 0.05);
}

.table-hover tbody tr:hover {
	background-color: rgba(0, 0, 0, 0.075);
}

.table-active,
.table-active > th,
.table-active > td {
	background-color: rgba(0, 0, 0, 0.075);
}

.table-hover .table-active:hover {
	background-color: rgba(0, 0, 0, 0.075);
}

.table-hover .table-active:hover > td,
.table-hover .table-active:hover > th {
	background-color: rgba(0, 0, 0, 0.075);
}

.table .thead-dark th {
	color: #fff;
	background-color: #212529;
	border-color: #32383e;
}

.table .thead-light th {
	color: #495057;
	background-color: #e9ecef;
	border-color: #dee2e6;
}

.table-dark {
	color: #fff;
	background-color: #212529;
}

.table-dark th,
.table-dark td,
.table-dark thead th {
	border-color: #32383e;
}

.table-dark.table-bordered {
	border: 0;
}

.table-dark.table-striped tbody tr:nth-of-type(odd) {
	background-color: rgba(255, 255, 255, 0.05);
}

.table-dark.table-hover tbody tr:hover {
	background-color: rgba(255, 255, 255, 0.075);
}

@media (max-width: 575.98px) {
	.table-responsive-sm {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-sm > .table-bordered {
		border: 0;
	}
}

@media (max-width: 767.98px) {
	.table-responsive-md {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-md > .table-bordered {
		border: 0;
	}
}

@media (max-width: 991.98px) {
	.table-responsive-lg {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-lg > .table-bordered {
		border: 0;
	}
}

@media (max-width: 1199.98px) {
	.table-responsive-xl {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-xl > .table-bordered {
		border: 0;
	}
}

@media (max-width: 1599.98px) {
	.table-responsive-xxl {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-xxl > .table-bordered {
		border: 0;
	}
}

.table-responsive {
	display: block;
	width: 100%;
	overflow-x: auto;
	-webkit-overflow-scrolling: touch;
	-ms-overflow-style: -ms-autohiding-scrollbar;
}

.table-responsive > .table-bordered {
	border: 0;
}

.form-control {
	display: block;
	width: 100%;
	padding: 0.375rem 0.75rem;
	font-size: 16px;
	line-height: 1.5;
	color: #495057;
	background-color: #fff;
	background-clip: padding-box;
	border: 1px solid #ced4da;
	border-radius: 0.25rem;
	transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

.form-control::-ms-expand {
	background-color: transparent;
	border: 0;
}

.form-control:focus {
	color: #495057;
	background-color: #fff;
	border-color: #80bdff;
	outline: 0;
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.form-control::placeholder {
	color: #6c757d;
	opacity: 1;
}

.form-control:disabled, .form-control[readonly] {
	background-color: #e9ecef;
	opacity: 1;
}

select.form-control:not([size]):not([multiple]) {
	height: calc(2.25rem + 2px);
}

select.form-control:focus::-ms-value {
	color: #495057;
	background-color: #fff;
}

.form-control-file,
.form-control-range {
	display: block;
	width: 100%;
}

.col-form-label {
	padding-top: calc(0.375rem + 1px);
	padding-bottom: calc(0.375rem + 1px);
	margin-bottom: 0;
	font-size: inherit;
	line-height: 1.5;
}

.col-form-label-lg {
	padding-top: calc(0.5rem + 1px);
	padding-bottom: calc(0.5rem + 1px);
	font-size: 20px;
	line-height: 1.5;
}

.col-form-label-sm {
	padding-top: calc(0.25rem + 1px);
	padding-bottom: calc(0.25rem + 1px);
	font-size: 12px;
	line-height: 1.5;
}

.form-control-plaintext {
	display: block;
	width: 100%;
	padding-top: 0.375rem;
	padding-bottom: 0.375rem;
	margin-bottom: 0;
	line-height: 1.5;
	background-color: transparent;
	border: solid transparent;
	border-width: 1px 0;
}

.form-control-plaintext.form-control-sm, .input-group-sm > .form-control-plaintext.form-control,
.input-group-sm > .input-group-prepend > .form-control-plaintext.input-group-text,
.input-group-sm > .input-group-append > .form-control-plaintext.input-group-text,
.input-group-sm > .input-group-prepend > .form-control-plaintext.btn,
.input-group-sm > .input-group-append > .form-control-plaintext.btn, .form-control-plaintext.form-control-lg, .input-group-lg > .form-control-plaintext.form-control,
.input-group-lg > .input-group-prepend > .form-control-plaintext.input-group-text,
.input-group-lg > .input-group-append > .form-control-plaintext.input-group-text,
.input-group-lg > .input-group-prepend > .form-control-plaintext.btn,
.input-group-lg > .input-group-append > .form-control-plaintext.btn {
	padding-right: 0;
	padding-left: 0;
}

.form-control-sm, .input-group-sm > .form-control,
.input-group-sm > .input-group-prepend > .input-group-text,
.input-group-sm > .input-group-append > .input-group-text,
.input-group-sm > .input-group-prepend > .btn,
.input-group-sm > .input-group-append > .btn {
	padding: 0.25rem 0.5rem;
	font-size: 12px;
	line-height: 1.5;
	border-radius: 0.2rem;
}

select.form-control-sm:not([size]):not([multiple]), .input-group-sm > select.form-control:not([size]):not([multiple]),
.input-group-sm > .input-group-prepend > select.input-group-text:not([size]):not([multiple]),
.input-group-sm > .input-group-append > select.input-group-text:not([size]):not([multiple]),
.input-group-sm > .input-group-prepend > select.btn:not([size]):not([multiple]),
.input-group-sm > .input-group-append > select.btn:not([size]):not([multiple]) {
	height: calc(1.8125rem + 2px);
}

.form-control-lg, .input-group-lg > .form-control,
.input-group-lg > .input-group-prepend > .input-group-text,
.input-group-lg > .input-group-append > .input-group-text,
.input-group-lg > .input-group-prepend > .btn,
.input-group-lg > .input-group-append > .btn {
	padding: 0.5rem 1rem;
	font-size: 20px;
	line-height: 1.5;
	border-radius: 0.3rem;
}

select.form-control-lg:not([size]):not([multiple]), .input-group-lg > select.form-control:not([size]):not([multiple]),
.input-group-lg > .input-group-prepend > select.input-group-text:not([size]):not([multiple]),
.input-group-lg > .input-group-append > select.input-group-text:not([size]):not([multiple]),
.input-group-lg > .input-group-prepend > select.btn:not([size]):not([multiple]),
.input-group-lg > .input-group-append > select.btn:not([size]):not([multiple]) {
	height: calc(2.875rem + 2px);
}

.form-group {
	margin-bottom: 1rem;
}

.form-text {
	display: block;
	margin-top: 0.25rem;
}

.form-row {
	display: flex;
	flex-wrap: wrap;
	margin-right: -5px;
	margin-left: -5px;
}

.form-row > .col,
.form-row > [class*="col-"] {
	padding-right: 5px;
	padding-left: 5px;
}

.form-check {
	position: relative;
	display: block;
	padding-left: 1.25rem;
}

.form-check-input {
	position: absolute;
	margin-top: 0.3rem;
	margin-left: -1.25rem;
}

.form-check-input:disabled ~ .form-check-label {
	color: #6c757d;
}

.form-check-label {
	margin-bottom: 0;
}

.form-check-inline {
	display: inline-flex;
	align-items: center;
	padding-left: 0;
	margin-right: 0.75rem;
}

.form-check-inline .form-check-input {
	position: static;
	margin-top: 0;
	margin-right: 0.3125rem;
	margin-left: 0;
}

.valid-feedback {
	display: none;
	width: 100%;
	margin-top: 0.25rem;
	font-size: 80%;
	color: #98bf44;
}

.valid-tooltip {
	position: absolute;
	top: 100%;
	z-index: 5;
	display: none;
	max-width: 100%;
	padding: .5rem;
	margin-top: .1rem;
	font-size: .875rem;
	line-height: 1;
	color: #fff;
	background-color: rgba(152, 191, 68, 0.8);
	border-radius: .2rem;
}

.was-validated .form-control:valid, .form-control.is-valid, .was-validated
.custom-select:valid,
.custom-select.is-valid {
	border-color: #98bf44;
}

.was-validated .form-control:valid:focus, .form-control.is-valid:focus, .was-validated
.custom-select:valid:focus,
.custom-select.is-valid:focus {
	border-color: #98bf44;
	box-shadow: 0 0 0 0.2rem rgba(152, 191, 68, 0.25);
}

.was-validated .form-control:valid ~ .valid-feedback,
.was-validated .form-control:valid ~ .valid-tooltip, .form-control.is-valid ~ .valid-feedback,
.form-control.is-valid ~ .valid-tooltip, .was-validated
.custom-select:valid ~ .valid-feedback,
.was-validated
.custom-select:valid ~ .valid-tooltip,
.custom-select.is-valid ~ .valid-feedback,
.custom-select.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .form-check-input:valid ~ .form-check-label, .form-check-input.is-valid ~ .form-check-label {
	color: #98bf44;
}

.was-validated .form-check-input:valid ~ .valid-feedback,
.was-validated .form-check-input:valid ~ .valid-tooltip, .form-check-input.is-valid ~ .valid-feedback,
.form-check-input.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .custom-control-input:valid ~ .custom-control-label, .custom-control-input.is-valid ~ .custom-control-label {
	color: #98bf44;
}

.was-validated .custom-control-input:valid ~ .custom-control-label::before, .custom-control-input.is-valid ~ .custom-control-label::before {
	background-color: #cce0a3;
}

.was-validated .custom-control-input:valid ~ .valid-feedback,
.was-validated .custom-control-input:valid ~ .valid-tooltip, .custom-control-input.is-valid ~ .valid-feedback,
.custom-control-input.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .custom-control-input:valid:checked ~ .custom-control-label::before, .custom-control-input.is-valid:checked ~ .custom-control-label::before {
	background-color: #adcc6a;
}

.was-validated .custom-control-input:valid:focus ~ .custom-control-label::before, .custom-control-input.is-valid:focus ~ .custom-control-label::before {
	box-shadow: 0 0 0 1px #fff, 0 0 0 0.2rem rgba(152, 191, 68, 0.25);
}

.was-validated .custom-file-input:valid ~ .custom-file-label, .custom-file-input.is-valid ~ .custom-file-label {
	border-color: #98bf44;
}

.was-validated .custom-file-input:valid ~ .custom-file-label::before, .custom-file-input.is-valid ~ .custom-file-label::before {
	border-color: inherit;
}

.was-validated .custom-file-input:valid ~ .valid-feedback,
.was-validated .custom-file-input:valid ~ .valid-tooltip, .custom-file-input.is-valid ~ .valid-feedback,
.custom-file-input.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .custom-file-input:valid:focus ~ .custom-file-label, .custom-file-input.is-valid:focus ~ .custom-file-label {
	box-shadow: 0 0 0 0.2rem rgba(152, 191, 68, 0.25);
}

.invalid-feedback {
	display: none;
	width: 100%;
	margin-top: 0.25rem;
	font-size: 80%;
	color: #dc0000;
}

.invalid-tooltip {
	position: absolute;
	top: 100%;
	z-index: 5;
	display: none;
	max-width: 100%;
	padding: .5rem;
	margin-top: .1rem;
	font-size: .875rem;
	line-height: 1;
	color: #fff;
	background-color: rgba(220, 0, 0, 0.8);
	border-radius: .2rem;
}

.was-validated .form-control:invalid, .form-control.is-invalid, .was-validated
.custom-select:invalid,
.custom-select.is-invalid {
	border-color: #dc0000;
}

.was-validated .form-control:invalid:focus, .form-control.is-invalid:focus, .was-validated
.custom-select:invalid:focus,
.custom-select.is-invalid:focus {
	border-color: #dc0000;
	box-shadow: 0 0 0 0.2rem rgba(220, 0, 0, 0.25);
}

.was-validated .form-control:invalid ~ .invalid-feedback,
.was-validated .form-control:invalid ~ .invalid-tooltip, .form-control.is-invalid ~ .invalid-feedback,
.form-control.is-invalid ~ .invalid-tooltip, .was-validated
.custom-select:invalid ~ .invalid-feedback,
.was-validated
.custom-select:invalid ~ .invalid-tooltip,
.custom-select.is-invalid ~ .invalid-feedback,
.custom-select.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .form-check-input:invalid ~ .form-check-label, .form-check-input.is-invalid ~ .form-check-label {
	color: #dc0000;
}

.was-validated .form-check-input:invalid ~ .invalid-feedback,
.was-validated .form-check-input:invalid ~ .invalid-tooltip, .form-check-input.is-invalid ~ .invalid-feedback,
.form-check-input.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .custom-control-input:invalid ~ .custom-control-label, .custom-control-input.is-invalid ~ .custom-control-label {
	color: #dc0000;
}

.was-validated .custom-control-input:invalid ~ .custom-control-label::before, .custom-control-input.is-invalid ~ .custom-control-label::before {
	background-color: #ff5d5d;
}

.was-validated .custom-control-input:invalid ~ .invalid-feedback,
.was-validated .custom-control-input:invalid ~ .invalid-tooltip, .custom-control-input.is-invalid ~ .invalid-feedback,
.custom-control-input.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .custom-control-input:invalid:checked ~ .custom-control-label::before, .custom-control-input.is-invalid:checked ~ .custom-control-label::before {
	background-color: #ff1010;
}

.was-validated .custom-control-input:invalid:focus ~ .custom-control-label::before, .custom-control-input.is-invalid:focus ~ .custom-control-label::before {
	box-shadow: 0 0 0 1px #fff, 0 0 0 0.2rem rgba(220, 0, 0, 0.25);
}

.was-validated .custom-file-input:invalid ~ .custom-file-label, .custom-file-input.is-invalid ~ .custom-file-label {
	border-color: #dc0000;
}

.was-validated .custom-file-input:invalid ~ .custom-file-label::before, .custom-file-input.is-invalid ~ .custom-file-label::before {
	border-color: inherit;
}

.was-validated .custom-file-input:invalid ~ .invalid-feedback,
.was-validated .custom-file-input:invalid ~ .invalid-tooltip, .custom-file-input.is-invalid ~ .invalid-feedback,
.custom-file-input.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .custom-file-input:invalid:focus ~ .custom-file-label, .custom-file-input.is-invalid:focus ~ .custom-file-label {
	box-shadow: 0 0 0 0.2rem rgba(220, 0, 0, 0.25);
}

.form-inline {
	display: flex;
	flex-flow: row wrap;
	align-items: center;
}

.form-inline .form-check {
	width: 100%;
}

@media (min-width: 576px) {
	.form-inline label {
		display: flex;
		align-items: center;
		justify-content: center;
		margin-bottom: 0;
	}
	.form-inline .form-group {
		display: flex;
		flex: 0 0 auto;
		flex-flow: row wrap;
		align-items: center;
		margin-bottom: 0;
	}
	.form-inline .form-control {
		display: inline-block;
		width: auto;
		vertical-align: middle;
	}
	.form-inline .form-control-plaintext {
		display: inline-block;
	}
	.form-inline .input-group {
		width: auto;
	}
	.form-inline .form-check {
		display: flex;
		align-items: center;
		justify-content: center;
		width: auto;
		padding-left: 0;
	}
	.form-inline .form-check-input {
		position: relative;
		margin-top: 0;
		margin-right: 0.25rem;
		margin-left: 0;
	}
	.form-inline .custom-control {
		align-items: center;
		justify-content: center;
	}
	.form-inline .custom-control-label {
		margin-bottom: 0;
	}
}

.btn {
	display: inline-block;
	font-weight: 500;
	text-align: center;
	white-space: nowrap;
	vertical-align: middle;
	user-select: none;
	border: 1px solid transparent;
	padding: 0.375rem 0.75rem;
	font-size: 16px;
	line-height: 1.5;
	border-radius: 6px;
	transition: all 0.15s ease-in-out;
}

.btn:hover, .btn:focus {
	text-decoration: none;
}

.btn:focus, .btn.focus {
	outline: 0;
	box-shadow: 0;
}

.btn.disabled, .btn:disabled {
	opacity: 0.65;
}

.btn:not(:disabled):not(.disabled) {
	cursor: pointer;
}

.btn:not(:disabled):not(.disabled):active, .btn:not(:disabled):not(.disabled).active {
	background-image: none;
}

a.btn.disabled,
fieldset:disabled a.btn {
	pointer-events: none;
}

.btn-link {
	font-weight: 400;
	color: #248cce;
	background-color: transparent;
}

.btn-link:hover {
	color: #790420;
	text-decoration: underline;
	background-color: transparent;
	border-color: transparent;
}

.btn-link:focus, .btn-link.focus {
	text-decoration: underline;
	border-color: transparent;
	box-shadow: none;
}

.btn-link:disabled, .btn-link.disabled {
	color: #868e96;
}

.btn-lg, .btn-group-lg > .btn {
	padding: 0.5rem 1rem;
	font-size: 20px;
	line-height: 1.5;
	border-radius: 6px;
}

.btn-sm, .btn-group-sm > .btn {
	padding: 0.25rem 0.5rem;
	font-size: 12px;
	line-height: 1.5;
	border-radius: 0.2rem;
}

.btn-block {
	display: block;
	width: 100%;
}

.btn-block + .btn-block {
	margin-top: 0.5rem;
}

input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
	width: 100%;
}

.fade {
	opacity: 0;
	transition: opacity 0.15s linear;
}

.fade.show {
	opacity: 1;
}

.collapse {
	display: none;
}

.collapse.show {
	display: block;
}

tr.collapse.show {
	display: table-row;
}

tbody.collapse.show {
	display: table-row-group;
}

.collapsing {
	position: relative;
	height: 0;
	overflow: hidden;
	transition: height 0.35s ease;
}

.dropup,
.dropdown {
	position: relative;
}

.dropdown-toggle::after {
	display: inline-block;
	width: 0;
	height: 0;
	margin-left: 0.255em;
	vertical-align: 0.255em;
	content: "";
	border-top: 0.3em solid;
	border-right: 0.3em solid transparent;
	border-bottom: 0;
	border-left: 0.3em solid transparent;
}

.dropdown-toggle:empty::after {
	margin-left: 0;
}

.dropdown-menu {
	position: absolute;
	top: 100%;
	left: 0;
	z-index: 1000;
	display: none;
	float: left;
	min-width: 10rem;
	padding: 0.5rem 0;
	margin: 0.125rem 0 0;
	font-size: 16px;
	color: #74757f;
	text-align: left;
	list-style: none;
	background-color: #fff;
	background-clip: padding-box;
	border: 1px solid rgba(0, 0, 0, 0.15);
	border-radius: 0.25rem;
}

.dropup .dropdown-menu {
	margin-top: 0;
	margin-bottom: 0.125rem;
}

.dropup .dropdown-toggle::after {
	display: inline-block;
	width: 0;
	height: 0;
	margin-left: 0.255em;
	vertical-align: 0.255em;
	content: "";
	border-top: 0;
	border-right: 0.3em solid transparent;
	border-bottom: 0.3em solid;
	border-left: 0.3em solid transparent;
}

.dropup .dropdown-toggle:empty::after {
	margin-left: 0;
}

.dropright .dropdown-menu {
	margin-top: 0;
	margin-left: 0.125rem;
}

.dropright .dropdown-toggle::after {
	display: inline-block;
	width: 0;
	height: 0;
	margin-left: 0.255em;
	vertical-align: 0.255em;
	content: "";
	border-top: 0.3em solid transparent;
	border-bottom: 0.3em solid transparent;
	border-left: 0.3em solid;
}

.dropright .dropdown-toggle:empty::after {
	margin-left: 0;
}

.dropright .dropdown-toggle::after {
	vertical-align: 0;
}

.dropleft .dropdown-menu {
	margin-top: 0;
	margin-right: 0.125rem;
}

.dropleft .dropdown-toggle::after {
	display: inline-block;
	width: 0;
	height: 0;
	margin-left: 0.255em;
	vertical-align: 0.255em;
	content: "";
}

.dropleft .dropdown-toggle::after {
	display: none;
}

.dropleft .dropdown-toggle::before {
	display: inline-block;
	width: 0;
	height: 0;
	margin-right: 0.255em;
	vertical-align: 0.255em;
	content: "";
	border-top: 0.3em solid transparent;
	border-right: 0.3em solid;
	border-bottom: 0.3em solid transparent;
}

.dropleft .dropdown-toggle:empty::after {
	margin-left: 0;
}

.dropleft .dropdown-toggle::before {
	vertical-align: 0;
}

.dropdown-divider {
	height: 0;
	margin: 0.5rem 0;
	overflow: hidden;
	border-top: 1px solid #e9ecef;
}

.dropdown-item {
	display: block;
	width: 100%;
	padding: 0.25rem 1.5rem;
	clear: both;
	font-weight: 400;
	color: #212529;
	text-align: inherit;
	white-space: nowrap;
	background-color: transparent;
	border: 0;
}

.dropdown-item:hover, .dropdown-item:focus {
	color: #16181b;
	text-decoration: none;
	background-color: #f8f9fa;
}

.dropdown-item.active, .dropdown-item:active {
	color: #fff;
	text-decoration: none;
	background-color: #007bff;
}

.dropdown-item.disabled, .dropdown-item:disabled {
	color: #6c757d;
	background-color: transparent;
}

.dropdown-menu.show {
	display: block;
}

.dropdown-header {
	display: block;
	padding: 0.5rem 1.5rem;
	margin-bottom: 0;
	font-size: 12px;
	color: #6c757d;
	white-space: nowrap;
}

.btn-group,
.btn-group-vertical {
	position: relative;
	display: inline-flex;
	vertical-align: middle;
}

.btn-group > .btn,
.btn-group-vertical > .btn {
	position: relative;
	flex: 0 1 auto;
}

.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover {
	z-index: 1;
}

.btn-group > .btn:focus, .btn-group > .btn:active, .btn-group > .btn.active,
.btn-group-vertical > .btn:focus,
.btn-group-vertical > .btn:active,
.btn-group-vertical > .btn.active {
	z-index: 1;
}

.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group,
.btn-group-vertical .btn + .btn,
.btn-group-vertical .btn + .btn-group,
.btn-group-vertical .btn-group + .btn,
.btn-group-vertical .btn-group + .btn-group {
	margin-left: -1px;
}

.btn-toolbar {
	display: flex;
	flex-wrap: wrap;
	justify-content: flex-start;
}

.btn-toolbar .input-group {
	width: auto;
}

.btn-group > .btn:first-child {
	margin-left: 0;
}

.btn-group > .btn:not(:last-child):not(.dropdown-toggle),
.btn-group > .btn-group:not(:last-child) > .btn {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.btn-group > .btn:not(:first-child),
.btn-group > .btn-group:not(:first-child) > .btn {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.dropdown-toggle-split {
	padding-right: 0.5625rem;
	padding-left: 0.5625rem;
}

.dropdown-toggle-split::after {
	margin-left: 0;
}

.btn-sm + .dropdown-toggle-split, .btn-group-sm > .btn + .dropdown-toggle-split {
	padding-right: 0.375rem;
	padding-left: 0.375rem;
}

.btn-lg + .dropdown-toggle-split, .btn-group-lg > .btn + .dropdown-toggle-split {
	padding-right: 0.75rem;
	padding-left: 0.75rem;
}

.btn-group-vertical {
	flex-direction: column;
	align-items: flex-start;
	justify-content: center;
}

.btn-group-vertical .btn,
.btn-group-vertical .btn-group {
	width: 100%;
}

.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
	margin-top: -1px;
	margin-left: 0;
}

.btn-group-vertical > .btn:not(:last-child):not(.dropdown-toggle),
.btn-group-vertical > .btn-group:not(:last-child) > .btn {
	border-bottom-right-radius: 0;
	border-bottom-left-radius: 0;
}

.btn-group-vertical > .btn:not(:first-child),
.btn-group-vertical > .btn-group:not(:first-child) > .btn {
	border-top-left-radius: 0;
	border-top-right-radius: 0;
}

.btn-group-toggle > .btn,
.btn-group-toggle > .btn-group > .btn {
	margin-bottom: 0;
}

.btn-group-toggle > .btn input[type="radio"],
.btn-group-toggle > .btn input[type="checkbox"],
.btn-group-toggle > .btn-group > .btn input[type="radio"],
.btn-group-toggle > .btn-group > .btn input[type="checkbox"] {
	position: absolute;
	clip: rect(0, 0, 0, 0);
	pointer-events: none;
}

.input-group {
	position: relative;
	display: flex;
	flex-wrap: wrap;
	align-items: stretch;
	width: 100%;
}

.input-group > .form-control,
.input-group > .custom-select,
.input-group > .custom-file {
	position: relative;
	flex: 1 1 auto;
	width: 1%;
	margin-bottom: 0;
}

.input-group > .form-control:focus,
.input-group > .custom-select:focus,
.input-group > .custom-file:focus {
	z-index: 3;
}

.input-group > .form-control + .form-control,
.input-group > .form-control + .custom-select,
.input-group > .form-control + .custom-file,
.input-group > .custom-select + .form-control,
.input-group > .custom-select + .custom-select,
.input-group > .custom-select + .custom-file,
.input-group > .custom-file + .form-control,
.input-group > .custom-file + .custom-select,
.input-group > .custom-file + .custom-file {
	margin-left: -1px;
}

.input-group > .form-control:not(:last-child),
.input-group > .custom-select:not(:last-child) {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.input-group > .form-control:not(:first-child),
.input-group > .custom-select:not(:first-child) {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.input-group > .custom-file {
	display: flex;
	align-items: center;
}

.input-group > .custom-file:not(:last-child) .custom-file-label,
.input-group > .custom-file:not(:last-child) .custom-file-label::before {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.input-group > .custom-file:not(:first-child) .custom-file-label,
.input-group > .custom-file:not(:first-child) .custom-file-label::before {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.input-group-prepend,
.input-group-append {
	display: flex;
}

.input-group-prepend .btn,
.input-group-append .btn {
	position: relative;
	z-index: 2;
}

.input-group-prepend .btn + .btn,
.input-group-prepend .btn + .input-group-text,
.input-group-prepend .input-group-text + .input-group-text,
.input-group-prepend .input-group-text + .btn,
.input-group-append .btn + .btn,
.input-group-append .btn + .input-group-text,
.input-group-append .input-group-text + .input-group-text,
.input-group-append .input-group-text + .btn {
	margin-left: -1px;
}

.input-group-prepend {
	margin-right: -1px;
}

.input-group-append {
	margin-left: -1px;
}

.input-group-text {
	display: flex;
	align-items: center;
	padding: 0.375rem 0.75rem;
	margin-bottom: 0;
	font-size: 16px;
	font-weight: 400;
	line-height: 1.5;
	color: #495057;
	text-align: center;
	white-space: nowrap;
	background-color: #e9ecef;
	border: 1px solid #ced4da;
	border-radius: 0.25rem;
}

.input-group-text input[type="radio"],
.input-group-text input[type="checkbox"] {
	margin-top: 0;
}

.input-group > .input-group-prepend > .btn,
.input-group > .input-group-prepend > .input-group-text,
.input-group > .input-group-append:not(:last-child) > .btn,
.input-group > .input-group-append:not(:last-child) > .input-group-text,
.input-group > .input-group-append:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group > .input-group-append:last-child > .input-group-text:not(:last-child) {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.input-group > .input-group-append > .btn,
.input-group > .input-group-append > .input-group-text,
.input-group > .input-group-prepend:not(:first-child) > .btn,
.input-group > .input-group-prepend:not(:first-child) > .input-group-text,
.input-group > .input-group-prepend:first-child > .btn:not(:first-child),
.input-group > .input-group-prepend:first-child > .input-group-text:not(:first-child) {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.custom-control {
	position: relative;
	display: block;
	min-height: 1.4875rem;
	padding-left: 1.5rem;
}

.custom-control-inline {
	display: inline-flex;
	margin-right: 1rem;
}

.custom-control-input {
	position: absolute;
	z-index: -1;
	opacity: 0;
}

.custom-control-input:checked ~ .custom-control-label::before {
	color: #fff;
	background-color: #007bff;
}

.custom-control-input:focus ~ .custom-control-label::before {
	box-shadow: 0 0 0 1px #fff, 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.custom-control-input:active ~ .custom-control-label::before {
	color: #fff;
	background-color: #b3d7ff;
}

.custom-control-input:disabled ~ .custom-control-label {
	color: #6c757d;
}

.custom-control-input:disabled ~ .custom-control-label::before {
	background-color: #e9ecef;
}

.custom-control-label {
	margin-bottom: 0;
}

.custom-control-label::before {
	position: absolute;
	top: 0.24375rem;
	left: 0;
	display: block;
	width: 1rem;
	height: 1rem;
	pointer-events: none;
	content: "";
	user-select: none;
	background-color: #dee2e6;
}

.custom-control-label::after {
	position: absolute;
	top: 0.24375rem;
	left: 0;
	display: block;
	width: 1rem;
	height: 1rem;
	content: "";
	background-repeat: no-repeat;
	background-position: center center;
	background-size: 50% 50%;
}

.custom-checkbox .custom-control-label::before {
	border-radius: 0.25rem;
}

.custom-checkbox .custom-control-input:checked ~ .custom-control-label::before {
	background-color: #007bff;
}

.custom-checkbox .custom-control-input:checked ~ .custom-control-label::after {
	background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3E%3Cpath fill='%23fff' d='M6.564.75l-3.59 3.612-1.538-1.55L0 4.26 2.974 7.25 8 2.193z'/%3E%3C/svg%3E");
}

.custom-checkbox .custom-control-input:indeterminate ~ .custom-control-label::before {
	background-color: #007bff;
}

.custom-checkbox .custom-control-input:indeterminate ~ .custom-control-label::after {
	background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 4'%3E%3Cpath stroke='%23fff' d='M0 2h4'/%3E%3C/svg%3E");
}

.custom-checkbox .custom-control-input:disabled:checked ~ .custom-control-label::before {
	background-color: rgba(0, 123, 255, 0.5);
}

.custom-checkbox .custom-control-input:disabled:indeterminate ~ .custom-control-label::before {
	background-color: rgba(0, 123, 255, 0.5);
}

.custom-radio .custom-control-label::before {
	border-radius: 50%;
}

.custom-radio .custom-control-input:checked ~ .custom-control-label::before {
	background-color: #007bff;
}

.custom-radio .custom-control-input:checked ~ .custom-control-label::after {
	background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3E%3Ccircle r='3' fill='%23fff'/%3E%3C/svg%3E");
}

.custom-radio .custom-control-input:disabled:checked ~ .custom-control-label::before {
	background-color: rgba(0, 123, 255, 0.5);
}

.custom-select {
	display: inline-block;
	width: 100%;
	height: calc(2.25rem + 2px);
	padding: 0.375rem 1.75rem 0.375rem 0.75rem;
	line-height: 1.5;
	color: #495057;
	vertical-align: middle;
	background: #fff url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3E%3Cpath fill='%23343a40' d='M2 0L0 2h4zm0 5L0 3h4z'/%3E%3C/svg%3E") no-repeat right 0.75rem center;
	background-size: 8px 10px;
	border: 1px solid #ced4da;
	border-radius: 0.25rem;
	appearance: none;
}

.custom-select:focus {
	border-color: #80bdff;
	outline: 0;
	box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.075), 0 0 5px rgba(128, 189, 255, 0.5);
}

.custom-select:focus::-ms-value {
	color: #495057;
	background-color: #fff;
}

.custom-select[multiple], .custom-select[size]:not([size="1"]) {
	height: auto;
	padding-right: 0.75rem;
	background-image: none;
}

.custom-select:disabled {
	color: #6c757d;
	background-color: #e9ecef;
}

.custom-select::-ms-expand {
	opacity: 0;
}

.custom-select-sm {
	height: calc(1.8125rem + 2px);
	padding-top: 0.375rem;
	padding-bottom: 0.375rem;
	font-size: 75%;
}

.custom-select-lg {
	height: calc(2.875rem + 2px);
	padding-top: 0.375rem;
	padding-bottom: 0.375rem;
	font-size: 125%;
}

.custom-file {
	position: relative;
	display: inline-block;
	width: 100%;
	height: calc(2.25rem + 2px);
	margin-bottom: 0;
}

.custom-file-input {
	position: relative;
	z-index: 2;
	width: 100%;
	height: calc(2.25rem + 2px);
	margin: 0;
	opacity: 0;
}

.custom-file-input:focus ~ .custom-file-control {
	border-color: #80bdff;
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.custom-file-input:focus ~ .custom-file-control::before {
	border-color: #80bdff;
}

.custom-file-input:lang(en) ~ .custom-file-label::after {
	content: "Browse";
}

.custom-file-label {
	position: absolute;
	top: 0;
	right: 0;
	left: 0;
	z-index: 1;
	height: calc(2.25rem + 2px);
	padding: 0.375rem 0.75rem;
	line-height: 1.5;
	color: #495057;
	background-color: #fff;
	border: 1px solid #ced4da;
	border-radius: 0.25rem;
}

.custom-file-label::after {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	z-index: 3;
	display: block;
	height: calc(calc(2.25rem + 2px) - 1px * 2);
	padding: 0.375rem 0.75rem;
	line-height: 1.5;
	color: #495057;
	content: "Browse";
	background-color: #e9ecef;
	border-left: 1px solid #ced4da;
	border-radius: 0 0.25rem 0.25rem 0;
}

.nav {
	display: flex;
	flex-wrap: wrap;
	padding-left: 0;
	margin-bottom: 0;
	list-style: none;
}

.nav-link {
	display: block;
	padding: 0.5rem 1rem;
}

.nav-link:hover, .nav-link:focus {
	text-decoration: none;
}

.nav-link.disabled {
	color: #6c757d;
}

.nav-tabs {
	border-bottom: 1px solid #dee2e6;
}

.nav-tabs .nav-item {
	margin-bottom: -1px;
}

.nav-tabs .nav-link {
	border: 1px solid transparent;
	border-top-left-radius: 0.25rem;
	border-top-right-radius: 0.25rem;
}

.nav-tabs .nav-link:hover, .nav-tabs .nav-link:focus {
	border-color: #e9ecef #e9ecef #dee2e6;
}

.nav-tabs .nav-link.disabled {
	color: #6c757d;
	background-color: transparent;
	border-color: transparent;
}

.nav-tabs .nav-link.active,
.nav-tabs .nav-item.show .nav-link {
	color: #495057;
	background-color: #fff;
	border-color: #dee2e6 #dee2e6 #fff;
}

.nav-tabs .dropdown-menu {
	margin-top: -1px;
	border-top-left-radius: 0;
	border-top-right-radius: 0;
}

.nav-pills .nav-link {
	border-radius: 0.25rem;
}

.nav-pills .nav-link.active,
.nav-pills .show > .nav-link {
	color: #fff;
	background-color: #007bff;
}

.nav-fill .nav-item {
	flex: 1 1 auto;
	text-align: center;
}

.nav-justified .nav-item {
	flex-basis: 0;
	flex-grow: 1;
	text-align: center;
}

.tab-content > .tab-pane {
	display: none;
}

.tab-content > .active {
	display: block;
}

.navbar {
	position: relative;
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
	padding: 0.5rem 1rem;
}

.navbar > .container,
.navbar > .container-fluid {
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}

.navbar-brand {
	display: inline-block;
	padding-top: 0.3125rem;
	padding-bottom: 0.3125rem;
	margin-right: 1rem;
	font-size: 1.25rem;
	line-height: inherit;
	white-space: nowrap;
}

.navbar-brand:hover, .navbar-brand:focus {
	text-decoration: none;
}

.navbar-nav {
	display: flex;
	flex-direction: column;
	padding-left: 0;
	margin-bottom: 0;
	list-style: none;
}

.navbar-nav .nav-link {
	padding-right: 0;
	padding-left: 0;
}

.navbar-nav .dropdown-menu {
	position: static;
	float: none;
}

.navbar-text {
	display: inline-block;
	padding-top: 0.5rem;
	padding-bottom: 0.5rem;
}

.navbar-collapse {
	flex-basis: 100%;
	flex-grow: 1;
	align-items: center;
}

.navbar-toggler {
	padding: 0.25rem 0.75rem;
	font-size: 1.25rem;
	line-height: 1;
	background-color: transparent;
	border: 1px solid transparent;
	border-radius: 0.25rem;
}

.navbar-toggler:hover, .navbar-toggler:focus {
	text-decoration: none;
}

.navbar-toggler:not(:disabled):not(.disabled) {
	cursor: pointer;
}

.navbar-toggler-icon {
	display: inline-block;
	width: 1.5em;
	height: 1.5em;
	vertical-align: middle;
	content: "";
	background: no-repeat center center;
	background-size: 100% 100%;
}

@media (max-width: 575.98px) {
	.navbar-expand-sm > .container,
	.navbar-expand-sm > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 576px) {
	.navbar-expand-sm {
		flex-flow: row nowrap;
		justify-content: flex-start;
	}
	.navbar-expand-sm .navbar-nav {
		flex-direction: row;
	}
	.navbar-expand-sm .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-sm .navbar-nav .dropdown-menu-right {
		right: 0;
		left: auto;
	}
	.navbar-expand-sm .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-sm > .container,
	.navbar-expand-sm > .container-fluid {
		flex-wrap: nowrap;
	}
	.navbar-expand-sm .navbar-collapse {
		display: flex !important;
		flex-basis: auto;
	}
	.navbar-expand-sm .navbar-toggler {
		display: none;
	}
	.navbar-expand-sm .dropup .dropdown-menu {
		top: auto;
		bottom: 100%;
	}
}

@media (max-width: 767.98px) {
	.navbar-expand-md > .container,
	.navbar-expand-md > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 768px) {
	.navbar-expand-md {
		flex-flow: row nowrap;
		justify-content: flex-start;
	}
	.navbar-expand-md .navbar-nav {
		flex-direction: row;
	}
	.navbar-expand-md .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-md .navbar-nav .dropdown-menu-right {
		right: 0;
		left: auto;
	}
	.navbar-expand-md .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-md > .container,
	.navbar-expand-md > .container-fluid {
		flex-wrap: nowrap;
	}
	.navbar-expand-md .navbar-collapse {
		display: flex !important;
		flex-basis: auto;
	}
	.navbar-expand-md .navbar-toggler {
		display: none;
	}
	.navbar-expand-md .dropup .dropdown-menu {
		top: auto;
		bottom: 100%;
	}
}

@media (max-width: 991.98px) {
	.navbar-expand-lg > .container,
	.navbar-expand-lg > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 992px) {
	.navbar-expand-lg {
		flex-flow: row nowrap;
		justify-content: flex-start;
	}
	.navbar-expand-lg .navbar-nav {
		flex-direction: row;
	}
	.navbar-expand-lg .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-lg .navbar-nav .dropdown-menu-right {
		right: 0;
		left: auto;
	}
	.navbar-expand-lg .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-lg > .container,
	.navbar-expand-lg > .container-fluid {
		flex-wrap: nowrap;
	}
	.navbar-expand-lg .navbar-collapse {
		display: flex !important;
		flex-basis: auto;
	}
	.navbar-expand-lg .navbar-toggler {
		display: none;
	}
	.navbar-expand-lg .dropup .dropdown-menu {
		top: auto;
		bottom: 100%;
	}
}

@media (max-width: 1199.98px) {
	.navbar-expand-xl > .container,
	.navbar-expand-xl > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 1200px) {
	.navbar-expand-xl {
		flex-flow: row nowrap;
		justify-content: flex-start;
	}
	.navbar-expand-xl .navbar-nav {
		flex-direction: row;
	}
	.navbar-expand-xl .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-xl .navbar-nav .dropdown-menu-right {
		right: 0;
		left: auto;
	}
	.navbar-expand-xl .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-xl > .container,
	.navbar-expand-xl > .container-fluid {
		flex-wrap: nowrap;
	}
	.navbar-expand-xl .navbar-collapse {
		display: flex !important;
		flex-basis: auto;
	}
	.navbar-expand-xl .navbar-toggler {
		display: none;
	}
	.navbar-expand-xl .dropup .dropdown-menu {
		top: auto;
		bottom: 100%;
	}
}

@media (max-width: 1599.98px) {
	.navbar-expand-xxl > .container,
	.navbar-expand-xxl > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 1600px) {
	.navbar-expand-xxl {
		flex-flow: row nowrap;
		justify-content: flex-start;
	}
	.navbar-expand-xxl .navbar-nav {
		flex-direction: row;
	}
	.navbar-expand-xxl .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-xxl .navbar-nav .dropdown-menu-right {
		right: 0;
		left: auto;
	}
	.navbar-expand-xxl .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-xxl > .container,
	.navbar-expand-xxl > .container-fluid {
		flex-wrap: nowrap;
	}
	.navbar-expand-xxl .navbar-collapse {
		display: flex !important;
		flex-basis: auto;
	}
	.navbar-expand-xxl .navbar-toggler {
		display: none;
	}
	.navbar-expand-xxl .dropup .dropdown-menu {
		top: auto;
		bottom: 100%;
	}
}

.navbar-expand {
	flex-flow: row nowrap;
	justify-content: flex-start;
}

.navbar-expand > .container,
.navbar-expand > .container-fluid {
	padding-right: 0;
	padding-left: 0;
}

.navbar-expand .navbar-nav {
	flex-direction: row;
}

.navbar-expand .navbar-nav .dropdown-menu {
	position: absolute;
}

.navbar-expand .navbar-nav .dropdown-menu-right {
	right: 0;
	left: auto;
}

.navbar-expand .navbar-nav .nav-link {
	padding-right: 0.5rem;
	padding-left: 0.5rem;
}

.navbar-expand > .container,
.navbar-expand > .container-fluid {
	flex-wrap: nowrap;
}

.navbar-expand .navbar-collapse {
	display: flex !important;
	flex-basis: auto;
}

.navbar-expand .navbar-toggler {
	display: none;
}

.navbar-expand .dropup .dropdown-menu {
	top: auto;
	bottom: 100%;
}

.navbar-light .navbar-brand {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:hover, .navbar-light .navbar-brand:focus {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
	color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:hover, .navbar-light .navbar-nav .nav-link:focus {
	color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
	color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
	color: rgba(0, 0, 0, 0.5);
	border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
	background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-text {
	color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-text a {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-text a:hover, .navbar-light .navbar-text a:focus {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-dark .navbar-brand {
	color: #fff;
}

.navbar-dark .navbar-brand:hover, .navbar-dark .navbar-brand:focus {
	color: #fff;
}

.navbar-dark .navbar-nav .nav-link {
	color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:hover, .navbar-dark .navbar-nav .nav-link:focus {
	color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
	color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
	color: #fff;
}

.navbar-dark .navbar-toggler {
	color: rgba(255, 255, 255, 0.5);
	border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
	background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-dark .navbar-text {
	color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-text a {
	color: #fff;
}

.navbar-dark .navbar-text a:hover, .navbar-dark .navbar-text a:focus {
	color: #fff;
}

.card {
	position: relative;
	display: flex;
	flex-direction: column;
	min-width: 0;
	word-wrap: break-word;
	background-color: #fff;
	background-clip: border-box;
	border: 1px solid rgba(0, 0, 0, 0.125);
	border-radius: 0.25rem;
}

.card > hr {
	margin-right: 0;
	margin-left: 0;
}

.card > .list-group:first-child .list-group-item:first-child {
	border-top-left-radius: 0.25rem;
	border-top-right-radius: 0.25rem;
}

.card > .list-group:last-child .list-group-item:last-child {
	border-bottom-right-radius: 0.25rem;
	border-bottom-left-radius: 0.25rem;
}

.card-body {
	flex: 1 1 auto;
	padding: 1.25rem;
}

.card-title {
	margin-bottom: 0.75rem;
}

.card-subtitle {
	margin-top: -0.375rem;
	margin-bottom: 0;
}

.card-text:last-child {
	margin-bottom: 0;
}

.card-link:hover {
	text-decoration: none;
}

.card-link + .card-link {
	margin-left: 1.25rem;
}

.card-header {
	padding: 0.75rem 1.25rem;
	margin-bottom: 0;
	background-color: rgba(0, 0, 0, 0.03);
	border-bottom: 1px solid rgba(0, 0, 0, 0.125);
}

.card-header:first-child {
	border-radius: calc(0.25rem - 1px) calc(0.25rem - 1px) 0 0;
}

.card-header + .list-group .list-group-item:first-child {
	border-top: 0;
}

.card-footer {
	padding: 0.75rem 1.25rem;
	background-color: rgba(0, 0, 0, 0.03);
	border-top: 1px solid rgba(0, 0, 0, 0.125);
}

.card-footer:last-child {
	border-radius: 0 0 calc(0.25rem - 1px) calc(0.25rem - 1px);
}

.card-header-tabs {
	margin-right: -0.625rem;
	margin-bottom: -0.75rem;
	margin-left: -0.625rem;
	border-bottom: 0;
}

.card-header-pills {
	margin-right: -0.625rem;
	margin-left: -0.625rem;
}

.card-img-overlay {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	padding: 1.25rem;
}

.card-img {
	width: 100%;
	border-radius: calc(0.25rem - 1px);
}

.card-img-top {
	width: 100%;
	border-top-left-radius: calc(0.25rem - 1px);
	border-top-right-radius: calc(0.25rem - 1px);
}

.card-img-bottom {
	width: 100%;
	border-bottom-right-radius: calc(0.25rem - 1px);
	border-bottom-left-radius: calc(0.25rem - 1px);
}

.card-deck {
	display: flex;
	flex-direction: column;
}

.card-deck .card {
	margin-bottom: 15px;
}

@media (min-width: 576px) {
	.card-deck {
		flex-flow: row wrap;
		margin-right: -15px;
		margin-left: -15px;
	}
	.card-deck .card {
		display: flex;
		flex: 1 0 0%;
		flex-direction: column;
		margin-right: 15px;
		margin-bottom: 0;
		margin-left: 15px;
	}
}

.card-group {
	display: flex;
	flex-direction: column;
}

.card-group > .card {
	margin-bottom: 15px;
}

@media (min-width: 576px) {
	.card-group {
		flex-flow: row wrap;
	}
	.card-group > .card {
		flex: 1 0 0%;
		margin-bottom: 0;
	}
	.card-group > .card + .card {
		margin-left: 0;
		border-left: 0;
	}
	.card-group > .card:first-child {
		border-top-right-radius: 0;
		border-bottom-right-radius: 0;
	}
	.card-group > .card:first-child .card-img-top,
	.card-group > .card:first-child .card-header {
		border-top-right-radius: 0;
	}
	.card-group > .card:first-child .card-img-bottom,
	.card-group > .card:first-child .card-footer {
		border-bottom-right-radius: 0;
	}
	.card-group > .card:last-child {
		border-top-left-radius: 0;
		border-bottom-left-radius: 0;
	}
	.card-group > .card:last-child .card-img-top,
	.card-group > .card:last-child .card-header {
		border-top-left-radius: 0;
	}
	.card-group > .card:last-child .card-img-bottom,
	.card-group > .card:last-child .card-footer {
		border-bottom-left-radius: 0;
	}
	.card-group > .card:only-child {
		border-radius: 0.25rem;
	}
	.card-group > .card:only-child .card-img-top,
	.card-group > .card:only-child .card-header {
		border-top-left-radius: 0.25rem;
		border-top-right-radius: 0.25rem;
	}
	.card-group > .card:only-child .card-img-bottom,
	.card-group > .card:only-child .card-footer {
		border-bottom-right-radius: 0.25rem;
		border-bottom-left-radius: 0.25rem;
	}
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) {
		border-radius: 0;
	}
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-img-top,
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-img-bottom,
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-header,
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-footer {
		border-radius: 0;
	}
}

.card-columns .card {
	margin-bottom: 0.75rem;
}

@media (min-width: 576px) {
	.card-columns {
		column-count: 3;
		column-gap: 1.25rem;
	}
	.card-columns .card {
		display: inline-block;
		width: 100%;
	}
}

.breadcrumb {
	display: flex;
	flex-wrap: wrap;
	padding: 0.75rem 1rem;
	margin-bottom: 1rem;
	list-style: none;
	background-color: #e9ecef;
	border-radius: 5;
}

.breadcrumb-item + .breadcrumb-item::before {
	display: inline-block;
	padding-right: 0.5rem;
	padding-left: 0.5rem;
	color: #6c757d;
	content: "/";
}

.breadcrumb-item + .breadcrumb-item:hover::before {
	text-decoration: underline;
}

.breadcrumb-item + .breadcrumb-item:hover::before {
	text-decoration: none;
}

.breadcrumb-item.active {
	color: #6c757d;
}

.pagination {
	display: flex;
	padding-left: 0;
	list-style: none;
	border-radius: 5;
}

.page-link {
	position: relative;
	display: block;
	padding: 0 9px;
	margin-left: -1px;
	line-height: 48px;
	color: #248cce;
	background-color: transparent;
	border: 1px solid #248cce;
}

.page-link:hover {
	color: #fff;
	text-decoration: none;
	background-color: #248cce;
	border-color: #248cce;
}

.page-link:focus {
	z-index: 2;
	outline: 0;
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.page-link:not(:disabled):not(.disabled) {
	cursor: pointer;
}

.page-item:first-child .page-link {
	margin-left: 0;
	border-top-left-radius: 5;
	border-bottom-left-radius: 5;
}

.page-item:last-child .page-link {
	border-top-right-radius: 5;
	border-bottom-right-radius: 5;
}

.page-item.active .page-link {
	z-index: 1;
	color: #fff;
	background-color: #248cce;
	border-color: #248cce;
}

.page-item.disabled .page-link {
	color: #74757f;
	pointer-events: none;
	cursor: auto;
	background-color: #e8e9ee;
	border-color: #e8e9ee;
}

.pagination-lg .page-link {
	padding: 0.75rem 1.5rem;
	font-size: 20px;
	line-height: 1.6;
}

.pagination-lg .page-item:first-child .page-link {
	border-top-left-radius: 6px;
	border-bottom-left-radius: 6px;
}

.pagination-lg .page-item:last-child .page-link {
	border-top-right-radius: 6px;
	border-bottom-right-radius: 6px;
}

.pagination-sm .page-link {
	padding: 0.25rem 0.5rem;
	font-size: 12px;
	line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
	border-top-left-radius: 0.2rem;
	border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
	border-top-right-radius: 0.2rem;
	border-bottom-right-radius: 0.2rem;
}

.badge {
	display: inline-block;
	padding: 0.25em 0.4em;
	font-size: 75%;
	font-weight: 700;
	line-height: 1;
	text-align: center;
	white-space: nowrap;
	vertical-align: baseline;
	border-radius: 0.25rem;
}

.badge:empty {
	display: none;
}

.btn .badge {
	position: relative;
	top: -1px;
}

.badge-pill {
	padding-right: 0.6em;
	padding-left: 0.6em;
	border-radius: 10rem;
}

.jumbotron {
	padding: 2rem 1rem;
	margin-bottom: 2rem;
	background-color: #e9ecef;
	border-radius: 6px;
}

@media (min-width: 576px) {
	.jumbotron {
		padding: 4rem 2rem;
	}
}

.jumbotron-fluid {
	padding-right: 0;
	padding-left: 0;
	border-radius: 0;
}

.alert {
	position: relative;
	padding: 0.75rem 1.25rem;
	margin-bottom: 1rem;
	border: 1px solid transparent;
	border-radius: 0.25rem;
}

.alert-heading {
	color: inherit;
}

.alert-link {
	font-weight: 700;
}

.alert-dismissible {
	padding-right: 4rem;
}

.alert-dismissible .close {
	position: absolute;
	top: 0;
	right: 0;
	padding: 0.75rem 1.25rem;
	color: inherit;
}

@keyframes progress-bar-stripes {
	from {
		background-position: 1rem 0;
	}
	to {
		background-position: 0 0;
	}
}

.progress {
	display: flex;
	height: 1rem;
	overflow: hidden;
	font-size: 0.75rem;
	background-color: #e9ecef;
	border-radius: 0.25rem;
}

.progress-bar {
	display: flex;
	flex-direction: column;
	justify-content: center;
	color: #fff;
	text-align: center;
	background-color: #007bff;
	transition: width 0.6s ease;
}

.progress-bar-striped {
	background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
	background-size: 1rem 1rem;
}

.progress-bar-animated {
	animation: progress-bar-stripes 1s linear infinite;
}

.media {
	display: flex;
	align-items: flex-start;
}

.media-body {
	flex: 1;
}

.list-group {
	display: flex;
	flex-direction: column;
	padding-left: 0;
	margin-bottom: 0;
}

.list-group-item-action {
	width: 100%;
	color: #495057;
	text-align: inherit;
}

.list-group-item-action:hover, .list-group-item-action:focus {
	color: #495057;
	text-decoration: none;
	background-color: #f8f9fa;
}

.list-group-item-action:active {
	color: #212529;
	background-color: #e9ecef;
}

.list-group-item {
	position: relative;
	display: block;
	padding: 0.75rem 1.25rem;
	margin-bottom: -1px;
	background-color: #fff;
	border: 1px solid rgba(0, 0, 0, 0.125);
}

.list-group-item:first-child {
	border-top-left-radius: 0.25rem;
	border-top-right-radius: 0.25rem;
}

.list-group-item:last-child {
	margin-bottom: 0;
	border-bottom-right-radius: 0.25rem;
	border-bottom-left-radius: 0.25rem;
}

.list-group-item:hover, .list-group-item:focus {
	z-index: 1;
	text-decoration: none;
}

.list-group-item.disabled, .list-group-item:disabled {
	color: #6c757d;
	background-color: #fff;
}

.list-group-item.active {
	z-index: 2;
	color: #fff;
	background-color: #007bff;
	border-color: #007bff;
}

.list-group-flush .list-group-item {
	border-right: 0;
	border-left: 0;
	border-radius: 0;
}

.list-group-flush:first-child .list-group-item:first-child {
	border-top: 0;
}

.list-group-flush:last-child .list-group-item:last-child {
	border-bottom: 0;
}

.close {
	float: right;
	font-size: 1.5rem;
	font-weight: 700;
	line-height: 1;
	color: #000;
	text-shadow: 0 1px 0 #fff;
	opacity: .5;
}

.close:hover, .close:focus {
	color: #000;
	text-decoration: none;
	opacity: .75;
}

.close:not(:disabled):not(.disabled) {
	cursor: pointer;
}

button.close {
	padding: 0;
	background-color: transparent;
	border: 0;
	-webkit-appearance: none;
}

.modal-open {
	overflow: hidden;
}

.modal {
	position: fixed;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1150;
	display: none;
	overflow: hidden;
	outline: 0;
}

.modal-open .modal {
	overflow-x: hidden;
	overflow-y: auto;
}

.modal-dialog {
	position: relative;
	width: auto;
	margin: 0.5rem;
	pointer-events: none;
}

.modal.fade .modal-dialog {
	transition: transform 0.3s ease-out;
	transform: translate(0, -25%);
}

.modal.show .modal-dialog {
	transform: translate(0, 0);
}

.modal-dialog-centered {
	display: flex;
	align-items: center;
	min-height: calc(100% - (0.5rem * 2));
}

.modal-content {
	position: relative;
	display: flex;
	flex-direction: column;
	width: 100%;
	pointer-events: auto;
	background-color: #fff;
	background-clip: padding-box;
	border: 1px solid rgba(0, 0, 0, 0.2);
	border-radius: 6px;
	outline: 0;
}

.modal-backdrop {
	position: fixed;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1140;
	background-color: #000;
}

.modal-backdrop.fade {
	opacity: 0;
}

.modal-backdrop.show {
	opacity: 0.5;
}

.modal-header {
	display: flex;
	align-items: flex-start;
	justify-content: space-between;
	padding: 1rem;
	border-bottom: 1px solid #e9ecef;
	border-top-left-radius: 6px;
	border-top-right-radius: 6px;
}

.modal-header .close {
	padding: 1rem;
	margin: -1rem -1rem -1rem auto;
}

.modal-title {
	margin-bottom: 0;
	line-height: 1.5;
}

.modal-body {
	position: relative;
	flex: 1 1 auto;
	padding: 1rem;
}

.modal-footer {
	display: flex;
	align-items: center;
	justify-content: flex-end;
	padding: 1rem;
	border-top: 1px solid #e9ecef;
}

.modal-footer > :not(:first-child) {
	margin-left: .25rem;
}

.modal-footer > :not(:last-child) {
	margin-right: .25rem;
}

.modal-scrollbar-measure {
	position: absolute;
	top: -9999px;
	width: 50px;
	height: 50px;
	overflow: scroll;
}

@media (min-width: 576px) {
	.modal-dialog {
		max-width: 500px;
		margin: 1.75rem auto;
	}
	.modal-dialog-centered {
		min-height: calc(100% - (1.75rem * 2));
	}
	.modal-sm {
		max-width: 300px;
	}
}

@media (min-width: 992px) {
	.modal-lg {
		max-width: 800px;
	}
}

.tooltip {
	position: absolute;
	z-index: 1070;
	display: block;
	margin: 0;
	font-family: "Averia Libre";
	font-style: normal;
	font-weight: 400;
	line-height: 1.4875;
	text-align: left;
	text-align: start;
	text-decoration: none;
	text-shadow: none;
	text-transform: none;
	letter-spacing: normal;
	word-break: normal;
	word-spacing: normal;
	white-space: normal;
	line-break: auto;
	font-size: 0.875rem;
	word-wrap: break-word;
	opacity: 0;
}

.tooltip.show {
	opacity: 1;
}

.tooltip .arrow {
	position: absolute;
	display: block;
	width: 14px;
	height: 7px;
}

.tooltip .arrow::before {
	position: absolute;
	content: "";
	border-color: transparent;
	border-style: solid;
}

.bs-tooltip-top, .bs-tooltip-auto[x-placement^="top"] {
	padding: 7px 0;
}

.bs-tooltip-top .arrow, .bs-tooltip-auto[x-placement^="top"] .arrow {
	bottom: 0;
}

.bs-tooltip-top .arrow::before, .bs-tooltip-auto[x-placement^="top"] .arrow::before {
	top: 0;
	border-width: 7px 7px 0;
	border-top-color: #248cce;
}

.bs-tooltip-right, .bs-tooltip-auto[x-placement^="right"] {
	padding: 0 7px;
}

.bs-tooltip-right .arrow, .bs-tooltip-auto[x-placement^="right"] .arrow {
	left: 0;
	width: 7px;
	height: 14px;
}

.bs-tooltip-right .arrow::before, .bs-tooltip-auto[x-placement^="right"] .arrow::before {
	right: 0;
	border-width: 7px 7px 7px 0;
	border-right-color: #248cce;
}

.bs-tooltip-bottom, .bs-tooltip-auto[x-placement^="bottom"] {
	padding: 7px 0;
}

.bs-tooltip-bottom .arrow, .bs-tooltip-auto[x-placement^="bottom"] .arrow {
	top: 0;
}

.bs-tooltip-bottom .arrow::before, .bs-tooltip-auto[x-placement^="bottom"] .arrow::before {
	bottom: 0;
	border-width: 0 7px 7px;
	border-bottom-color: #248cce;
}

.bs-tooltip-left, .bs-tooltip-auto[x-placement^="left"] {
	padding: 0 7px;
}

.bs-tooltip-left .arrow, .bs-tooltip-auto[x-placement^="left"] .arrow {
	right: 0;
	width: 7px;
	height: 14px;
}

.bs-tooltip-left .arrow::before, .bs-tooltip-auto[x-placement^="left"] .arrow::before {
	left: 0;
	border-width: 7px 0 7px 7px;
	border-left-color: #248cce;
}

.tooltip-inner {
	max-width: 200px;
	padding: 6px 10px;
	color: #fff;
	text-align: center;
	background-color: #248cce;
	border-radius: 0.25rem;
}

.popover {
	position: absolute;
	top: 0;
	left: 0;
	z-index: 1060;
	display: block;
	max-width: 276px;
	font-family: "Averia Libre";
	font-style: normal;
	font-weight: 400;
	line-height: 1.4875;
	text-align: left;
	text-align: start;
	text-decoration: none;
	text-shadow: none;
	text-transform: none;
	letter-spacing: normal;
	word-break: normal;
	word-spacing: normal;
	white-space: normal;
	line-break: auto;
	font-size: 0.875rem;
	word-wrap: break-word;
	background-color: #fff;
	background-clip: padding-box;
	border: 1px solid rgba(0, 0, 0, 0.2);
	border-radius: 0.3rem;
}

.popover .arrow {
	position: absolute;
	display: block;
	width: 1rem;
	height: 0.5rem;
	margin: 0 6px;
}

.popover .arrow::before, .popover .arrow::after {
	position: absolute;
	display: block;
	content: "";
	border-color: transparent;
	border-style: solid;
}

.bs-popover-top, .bs-popover-auto[x-placement^="top"] {
	margin-bottom: 0.5rem;
}

.bs-popover-top .arrow, .bs-popover-auto[x-placement^="top"] .arrow {
	bottom: calc((0.5rem + 1px) * -1);
}

.bs-popover-top .arrow::before, .bs-popover-auto[x-placement^="top"] .arrow::before,
.bs-popover-top .arrow::after,
.bs-popover-auto[x-placement^="top"] .arrow::after {
	border-width: 0.5rem 0.5rem 0;
}

.bs-popover-top .arrow::before, .bs-popover-auto[x-placement^="top"] .arrow::before {
	bottom: 0;
	border-top-color: rgba(0, 0, 0, 0.25);
}


.bs-popover-top .arrow::after,
.bs-popover-auto[x-placement^="top"] .arrow::after {
	bottom: 1px;
	border-top-color: #fff;
}

.bs-popover-right, .bs-popover-auto[x-placement^="right"] {
	margin-left: 0.5rem;
}

.bs-popover-right .arrow, .bs-popover-auto[x-placement^="right"] .arrow {
	left: calc((0.5rem + 1px) * -1);
	width: 0.5rem;
	height: 1rem;
	margin: 6px 0;
}

.bs-popover-right .arrow::before, .bs-popover-auto[x-placement^="right"] .arrow::before,
.bs-popover-right .arrow::after,
.bs-popover-auto[x-placement^="right"] .arrow::after {
	border-width: 0.5rem 0.5rem 0.5rem 0;
}

.bs-popover-right .arrow::before, .bs-popover-auto[x-placement^="right"] .arrow::before {
	left: 0;
	border-right-color: rgba(0, 0, 0, 0.25);
}


.bs-popover-right .arrow::after,
.bs-popover-auto[x-placement^="right"] .arrow::after {
	left: 1px;
	border-right-color: #fff;
}

.bs-popover-bottom, .bs-popover-auto[x-placement^="bottom"] {
	margin-top: 0.5rem;
}

.bs-popover-bottom .arrow, .bs-popover-auto[x-placement^="bottom"] .arrow {
	top: calc((0.5rem + 1px) * -1);
}

.bs-popover-bottom .arrow::before, .bs-popover-auto[x-placement^="bottom"] .arrow::before,
.bs-popover-bottom .arrow::after,
.bs-popover-auto[x-placement^="bottom"] .arrow::after {
	border-width: 0 0.5rem 0.5rem 0.5rem;
}

.bs-popover-bottom .arrow::before, .bs-popover-auto[x-placement^="bottom"] .arrow::before {
	top: 0;
	border-bottom-color: rgba(0, 0, 0, 0.25);
}


.bs-popover-bottom .arrow::after,
.bs-popover-auto[x-placement^="bottom"] .arrow::after {
	top: 1px;
	border-bottom-color: #fff;
}

.bs-popover-bottom .popover-header::before, .bs-popover-auto[x-placement^="bottom"] .popover-header::before {
	position: absolute;
	top: 0;
	left: 50%;
	display: block;
	width: 1rem;
	margin-left: -0.5rem;
	content: "";
	border-bottom: 1px solid #f7f7f7;
}

.bs-popover-left, .bs-popover-auto[x-placement^="left"] {
	margin-right: 0.5rem;
}

.bs-popover-left .arrow, .bs-popover-auto[x-placement^="left"] .arrow {
	right: calc((0.5rem + 1px) * -1);
	width: 0.5rem;
	height: 1rem;
	margin: 6px 0;
}

.bs-popover-left .arrow::before, .bs-popover-auto[x-placement^="left"] .arrow::before,
.bs-popover-left .arrow::after,
.bs-popover-auto[x-placement^="left"] .arrow::after {
	border-width: 0.5rem 0 0.5rem 0.5rem;
}

.bs-popover-left .arrow::before, .bs-popover-auto[x-placement^="left"] .arrow::before {
	right: 0;
	border-left-color: rgba(0, 0, 0, 0.25);
}


.bs-popover-left .arrow::after,
.bs-popover-auto[x-placement^="left"] .arrow::after {
	right: 1px;
	border-left-color: #fff;
}

.popover-header {
	padding: 0.5rem 0.75rem;
	margin-bottom: 0;
	font-size: 16px;
	color: inherit;
	background-color: #f7f7f7;
	border-bottom: 1px solid #ebebeb;
	border-top-left-radius: calc(6px - 1px);
	border-top-right-radius: calc(6px - 1px);
}

.popover-header:empty {
	display: none;
}

.popover-body {
	padding: 0.5rem 0.75rem;
	color: #212529;
}

.carousel {
	position: relative;
}

.carousel-inner {
	position: relative;
	width: 100%;
	overflow: hidden;
}

.carousel-item {
	position: relative;
	display: none;
	align-items: center;
	width: 100%;
	transition: transform 0.6s ease;
	backface-visibility: hidden;
	perspective: 1000px;
}

.carousel-item.active,
.carousel-item-next,
.carousel-item-prev {
	display: block;
}

.carousel-item-next,
.carousel-item-prev {
	position: absolute;
	top: 0;
}

.carousel-item-next.carousel-item-left,
.carousel-item-prev.carousel-item-right {
	transform: translateX(0);
}

@supports (transform-style: preserve-3d) {
	.carousel-item-next.carousel-item-left,
	.carousel-item-prev.carousel-item-right {
		transform: translate3d(0, 0, 0);
	}
}

.carousel-item-next,
.active.carousel-item-right {
	transform: translateX(100%);
}

@supports (transform-style: preserve-3d) {
	.carousel-item-next,
	.active.carousel-item-right {
		transform: translate3d(100%, 0, 0);
	}
}

.carousel-item-prev,
.active.carousel-item-left {
	transform: translateX(-100%);
}

@supports (transform-style: preserve-3d) {
	.carousel-item-prev,
	.active.carousel-item-left {
		transform: translate3d(-100%, 0, 0);
	}
}

.carousel-control-prev,
.carousel-control-next {
	position: absolute;
	top: 0;
	bottom: 0;
	display: flex;
	align-items: center;
	justify-content: center;
	width: 15%;
	color: #fff;
	text-align: center;
	opacity: 0.5;
}

.carousel-control-prev:hover, .carousel-control-prev:focus,
.carousel-control-next:hover,
.carousel-control-next:focus {
	color: #fff;
	text-decoration: none;
	outline: 0;
	opacity: .9;
}

.carousel-control-prev {
	left: 0;
}

.carousel-control-next {
	right: 0;
}

.carousel-control-prev-icon,
.carousel-control-next-icon {
	display: inline-block;
	width: 20px;
	height: 20px;
	background: transparent no-repeat center center;
	background-size: 100% 100%;
}

.carousel-control-prev-icon {
	background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E");
}

.carousel-control-next-icon {
	background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E");
}

.carousel-indicators {
	position: absolute;
	right: 0;
	bottom: 10px;
	left: 0;
	z-index: 15;
	display: flex;
	justify-content: center;
	padding-left: 0;
	margin-right: 15%;
	margin-left: 15%;
	list-style: none;
}

.carousel-indicators li {
	position: relative;
	flex: 0 1 auto;
	width: 30px;
	height: 3px;
	margin-right: 3px;
	margin-left: 3px;
	text-indent: -999px;
	background-color: rgba(255, 255, 255, 0.5);
}

.carousel-indicators li::before {
	position: absolute;
	top: -10px;
	left: 0;
	display: inline-block;
	width: 100%;
	height: 10px;
	content: "";
}

.carousel-indicators li::after {
	position: absolute;
	bottom: -10px;
	left: 0;
	display: inline-block;
	width: 100%;
	height: 10px;
	content: "";
}

.carousel-indicators .active {
	background-color: #fff;
}

.carousel-caption {
	position: absolute;
	right: 15%;
	bottom: 20px;
	left: 15%;
	z-index: 10;
	padding-top: 20px;
	padding-bottom: 20px;
	color: #fff;
	text-align: center;
}

.align-baseline {
	vertical-align: baseline !important;
}

.align-top {
	vertical-align: top !important;
}

.align-middle {
	vertical-align: middle !important;
}

.align-bottom {
	vertical-align: bottom !important;
}

.align-text-bottom {
	vertical-align: text-bottom !important;
}

.align-text-top {
	vertical-align: text-top !important;
}

.bg-white {
	background-color: #fff !important;
}

.bg-transparent {
	background-color: transparent !important;
}

.border {
	border: 1px solid #dee2e6 !important;
}

.border-top {
	border-top: 1px solid #dee2e6 !important;
}

.border-right {
	border-right: 1px solid #dee2e6 !important;
}

.border-bottom {
	border-bottom: 1px solid #dee2e6 !important;
}

.border-left {
	border-left: 1px solid #dee2e6 !important;
}

.border-0 {
	border: 0 !important;
}

.border-top-0 {
	border-top: 0 !important;
}

.border-right-0 {
	border-right: 0 !important;
}

.border-bottom-0 {
	border-bottom: 0 !important;
}

.border-left-0 {
	border-left: 0 !important;
}

.border-white {
	border-color: #fff !important;
}

.rounded {
	border-radius: 5 !important;
}

.rounded-top {
	border-top-left-radius: 5 !important;
	border-top-right-radius: 5 !important;
}

.rounded-right {
	border-top-right-radius: 5 !important;	border-bottom-right-radius: 5 !important;
}

.rounded-bottom {
	border-bottom-right-radius: 5 !important;
	border-bottom-left-radius: 5 !important;
}

.rounded-left {
	border-top-left-radius: 5 !important;
	border-bottom-left-radius: 5 !important;
}

.rounded-circle {
	border-radius: 50% !important;
}

.rounded-0 {
	border-radius: 0 !important;
}

.clearfix::after {
	display: block;
	clear: both;
	content: "";
}

.d-none {
	display: none !important;
}

.d-inline {
	display: inline !important;
}

.d-inline-block {
	display: inline-block !important;
}

.d-block {
	display: block !important;
}

.d-table {
	display: table !important;
}

.d-table-row {
	display: table-row !important;
}

.d-table-cell {
	display: table-cell !important;
}

.d-flex {
	display: flex !important;
}

.d-inline-flex {
	display: inline-flex !important;
}

@media (min-width: 576px) {
	.d-sm-none {
		display: none !important;
	}
	.d-sm-inline {
		display: inline !important;
	}
	.d-sm-inline-block {
		display: inline-block !important;
	}
	.d-sm-block {
		display: block !important;
	}
	.d-sm-table {
		display: table !important;
	}
	.d-sm-table-row {
		display: table-row !important;
	}
	.d-sm-table-cell {
		display: table-cell !important;
	}
	.d-sm-flex {
		display: flex !important;
	}
	.d-sm-inline-flex {
		display: inline-flex !important;
	}
}

@media (min-width: 768px) {
	.d-md-none {
		display: none !important;
	}
	.d-md-inline {
		display: inline !important;
	}
	.d-md-inline-block {
		display: inline-block !important;
	}
	.d-md-block {
		display: block !important;
	}
	.d-md-table {
		display: table !important;
	}
	.d-md-table-row {
		display: table-row !important;
	}
	.d-md-table-cell {
		display: table-cell !important;
	}
	.d-md-flex {
		display: flex !important;
	}
	.d-md-inline-flex {
		display: inline-flex !important;
	}
}

@media (min-width: 992px) {
	.d-lg-none {
		display: none !important;
	}
	.d-lg-inline {
		display: inline !important;
	}
	.d-lg-inline-block {
		display: inline-block !important;
	}
	.d-lg-block {
		display: block !important;
	}
	.d-lg-table {
		display: table !important;
	}
	.d-lg-table-row {
		display: table-row !important;
	}
	.d-lg-table-cell {
		display: table-cell !important;
	}
	.d-lg-flex {
		display: flex !important;
	}
	.d-lg-inline-flex {
		display: inline-flex !important;
	}
}

@media (min-width: 1200px) {
	.d-xl-none {
		display: none !important;
	}
	.d-xl-inline {
		display: inline !important;
	}
	.d-xl-inline-block {
		display: inline-block !important;
	}
	.d-xl-block {
		display: block !important;
	}
	.d-xl-table {
		display: table !important;
	}
	.d-xl-table-row {
		display: table-row !important;
	}
	.d-xl-table-cell {
		display: table-cell !important;
	}
	.d-xl-flex {
		display: flex !important;
	}
	.d-xl-inline-flex {
		display: inline-flex !important;
	}
}

@media (min-width: 1600px) {
	.d-xxl-none {
		display: none !important;
	}
	.d-xxl-inline {
		display: inline !important;
	}
	.d-xxl-inline-block {
		display: inline-block !important;
	}
	.d-xxl-block {
		display: block !important;
	}
	.d-xxl-table {
		display: table !important;
	}
	.d-xxl-table-row {
		display: table-row !important;
	}
	.d-xxl-table-cell {
		display: table-cell !important;
	}
	.d-xxl-flex {
		display: flex !important;
	}
	.d-xxl-inline-flex {
		display: inline-flex !important;
	}
}

@media print {
	.d-print-none {
		display: none !important;
	}
	.d-print-inline {
		display: inline !important;
	}
	.d-print-inline-block {
		display: inline-block !important;
	}
	.d-print-block {
		display: block !important;
	}
	.d-print-table {
		display: table !important;
	}
	.d-print-table-row {
		display: table-row !important;
	}
	.d-print-table-cell {
		display: table-cell !important;
	}
	.d-print-flex {
		display: flex !important;
	}
	.d-print-inline-flex {
		display: inline-flex !important;
	}
}

.embed-responsive {
	position: relative;
	display: block;
	width: 100%;
	padding: 0;
	overflow: hidden;
}

.embed-responsive::before {
	display: block;
	content: "";
}

.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
	position: absolute;
	top: 0;
	bottom: 0;
	left: 0;
	width: 100%;
	height: 100%;
	border: 0;
}

.embed-responsive-21by9::before {
	padding-top: 42.85714%;
}

.embed-responsive-16by9::before {
	padding-top: 56.25%;
}

.embed-responsive-4by3::before {
	padding-top: 75%;
}

.embed-responsive-1by1::before {
	padding-top: 100%;
}

.flex-row {
	flex-direction: row !important;
}

.flex-column {
	flex-direction: column !important;
}

.flex-row-reverse {
	flex-direction: row-reverse !important;
}

.flex-column-reverse {
	flex-direction: column-reverse !important;
}

.flex-wrap {
	flex-wrap: wrap !important;
}

.flex-nowrap {
	flex-wrap: nowrap !important;
}

.flex-wrap-reverse {
	flex-wrap: wrap-reverse !important;
}

.justify-content-start {
	justify-content: flex-start !important;
}

.justify-content-end {
	justify-content: flex-end !important;
}

.justify-content-center {
	justify-content: center !important;
}

.justify-content-between {
	justify-content: space-between !important;
}

.justify-content-around {
	justify-content: space-around !important;
}

.align-items-start {
	align-items: flex-start !important;
}

.align-items-end {
	align-items: flex-end !important;
}

.align-items-center {
	align-items: center !important;
}

.align-items-baseline {
	align-items: baseline !important;
}

.align-items-stretch {
	align-items: stretch !important;
}

.align-content-start {
	align-content: flex-start !important;
}

.align-content-end {
	align-content: flex-end !important;
}

.align-content-center {
	align-content: center !important;
}

.align-content-between {
	align-content: space-between !important;
}

.align-content-around {
	align-content: space-around !important;
}

.align-content-stretch {
	align-content: stretch !important;
}

.align-self-auto {
	align-self: auto !important;
}

.align-self-start {
	align-self: flex-start !important;
}

.align-self-end {
	align-self: flex-end !important;
}

.align-self-center {
	align-self: center !important;
}

.align-self-baseline {
	align-self: baseline !important;
}

.align-self-stretch {
	align-self: stretch !important;
}

@media (min-width: 576px) {
	.flex-sm-row {
		flex-direction: row !important;
	}
	.flex-sm-column {
		flex-direction: column !important;
	}
	.flex-sm-row-reverse {
		flex-direction: row-reverse !important;
	}
	.flex-sm-column-reverse {
		flex-direction: column-reverse !important;
	}
	.flex-sm-wrap {
		flex-wrap: wrap !important;
	}
	.flex-sm-nowrap {
		flex-wrap: nowrap !important;
	}
	.flex-sm-wrap-reverse {
		flex-wrap: wrap-reverse !important;
	}
	.justify-content-sm-start {
		justify-content: flex-start !important;
	}
	.justify-content-sm-end {
		justify-content: flex-end !important;
	}
	.justify-content-sm-center {
		justify-content: center !important;
	}
	.justify-content-sm-between {
		justify-content: space-between !important;
	}
	.justify-content-sm-around {
		justify-content: space-around !important;
	}
	.align-items-sm-start {
		align-items: flex-start !important;
	}
	.align-items-sm-end {
		align-items: flex-end !important;
	}
	.align-items-sm-center {
		align-items: center !important;
	}
	.align-items-sm-baseline {
		align-items: baseline !important;
	}
	.align-items-sm-stretch {
		align-items: stretch !important;
	}
	.align-content-sm-start {
		align-content: flex-start !important;
	}
	.align-content-sm-end {
		align-content: flex-end !important;
	}
	.align-content-sm-center {
		align-content: center !important;
	}
	.align-content-sm-between {
		align-content: space-between !important;
	}
	.align-content-sm-around {
		align-content: space-around !important;
	}
	.align-content-sm-stretch {
		align-content: stretch !important;
	}
	.align-self-sm-auto {
		align-self: auto !important;
	}
	.align-self-sm-start {
		align-self: flex-start !important;
	}
	.align-self-sm-end {
		align-self: flex-end !important;
	}
	.align-self-sm-center {
		align-self: center !important;
	}
	.align-self-sm-baseline {
		align-self: baseline !important;
	}
	.align-self-sm-stretch {
		align-self: stretch !important;
	}}

@media (min-width: 768px) {
	.flex-md-row {
		flex-direction: row !important;
	}
	.flex-md-column {
		flex-direction: column !important;
	}
	.flex-md-row-reverse {
		flex-direction: row-reverse !important;
	}
	.flex-md-column-reverse {
		flex-direction: column-reverse !important;
	}
	.flex-md-wrap {
		flex-wrap: wrap !important;
	}
	.flex-md-nowrap {
		flex-wrap: nowrap !important;
	}
	.flex-md-wrap-reverse {
		flex-wrap: wrap-reverse !important;
	}
	.justify-content-md-start {
		justify-content: flex-start !important;
	}
	.justify-content-md-end {
		justify-content: flex-end !important;
	}
	.justify-content-md-center {
		justify-content: center !important;
	}
	.justify-content-md-between {
		justify-content: space-between !important;
	}
	.justify-content-md-around {
		justify-content: space-around !important;
	}
	.align-items-md-start {
		align-items: flex-start !important;
	}
	.align-items-md-end {
		align-items: flex-end !important;
	}
	.align-items-md-center {
		align-items: center !important;
	}
	.align-items-md-baseline {
		align-items: baseline !important;
	}
	.align-items-md-stretch {
		align-items: stretch !important;
	}
	.align-content-md-start {
		align-content: flex-start !important;
	}
	.align-content-md-end {
		align-content: flex-end !important;
	}
	.align-content-md-center {
		align-content: center !important;
	}
	.align-content-md-between {
		align-content: space-between !important;
	}
	.align-content-md-around {
		align-content: space-around !important;
	}
	.align-content-md-stretch {
		align-content: stretch !important;
	}
	.align-self-md-auto {
		align-self: auto !important;
	}
	.align-self-md-start {
		align-self: flex-start !important;
	}
	.align-self-md-end {
		align-self: flex-end !important;
	}
	.align-self-md-center {
		align-self: center !important;
	}
	.align-self-md-baseline {
		align-self: baseline !important;
	}
	.align-self-md-stretch {
		align-self: stretch !important;
	}
}

@media (min-width: 992px) {
	.flex-lg-row {
		flex-direction: row !important;
	}
	.flex-lg-column {
		flex-direction: column !important;
	}
	.flex-lg-row-reverse {
		flex-direction: row-reverse !important;
	}
	.flex-lg-column-reverse {
		flex-direction: column-reverse !important;
	}
	.flex-lg-wrap {
		flex-wrap: wrap !important;
	}
	.flex-lg-nowrap {
		flex-wrap: nowrap !important;
	}
	.flex-lg-wrap-reverse {
		flex-wrap: wrap-reverse !important;
	}
	.justify-content-lg-start {
		justify-content: flex-start !important;
	}
	.justify-content-lg-end {
		justify-content: flex-end !important;
	}
	.justify-content-lg-center {
		justify-content: center !important;
	}
	.justify-content-lg-between {
		justify-content: space-between !important;
	}
	.justify-content-lg-around {
		justify-content: space-around !important;
	}
	.align-items-lg-start {
		align-items: flex-start !important;
	}
	.align-items-lg-end {
		align-items: flex-end !important;
	}
	.align-items-lg-center {
		align-items: center !important;
	}
	.align-items-lg-baseline {
		align-items: baseline !important;
	}
	.align-items-lg-stretch {
		align-items: stretch !important;
	}
	.align-content-lg-start {
		align-content: flex-start !important;
	}
	.align-content-lg-end {
		align-content: flex-end !important;
	}
	.align-content-lg-center {
		align-content: center !important;
	}
	.align-content-lg-between {
		align-content: space-between !important;
	}
	.align-content-lg-around {
		align-content: space-around !important;
	}
	.align-content-lg-stretch {
		align-content: stretch !important;
	}
	.align-self-lg-auto {
		align-self: auto !important;
	}
	.align-self-lg-start {
		align-self: flex-start !important;
	}
	.align-self-lg-end {
		align-self: flex-end !important;
	}
	.align-self-lg-center {
		align-self: center !important;
	}
	.align-self-lg-baseline {
		align-self: baseline !important;
	}
	.align-self-lg-stretch {
		align-self: stretch !important;
	}
}

@media (min-width: 1200px) {
	.flex-xl-row {
		flex-direction: row !important;
	}
	.flex-xl-column {
		flex-direction: column !important;
	}
	.flex-xl-row-reverse {
		flex-direction: row-reverse !important;	}
	.flex-xl-column-reverse {
		flex-direction: column-reverse !important;
	}
	.flex-xl-wrap {
		flex-wrap: wrap !important;
	}
	.flex-xl-nowrap {
		flex-wrap: nowrap !important;
	}
	.flex-xl-wrap-reverse {
		flex-wrap: wrap-reverse !important;
	}
	.justify-content-xl-start {
		justify-content: flex-start !important;
	}
	.justify-content-xl-end {
		justify-content: flex-end !important;
	}
	.justify-content-xl-center {
		justify-content: center !important;
	}
	.justify-content-xl-between {
		justify-content: space-between !important;
	}
	.justify-content-xl-around {
		justify-content: space-around !important;
	}
	.align-items-xl-start {
		align-items: flex-start !important;
	}
	.align-items-xl-end {
		align-items: flex-end !important;
	}
	.align-items-xl-center {
		align-items: center !important;
	}
	.align-items-xl-baseline {
		align-items: baseline !important;
	}
	.align-items-xl-stretch {
		align-items: stretch !important;
	}
	.align-content-xl-start {
		align-content: flex-start !important;
	}
	.align-content-xl-end {
		align-content: flex-end !important;
	}
	.align-content-xl-center {
		align-content: center !important;
	}
	.align-content-xl-between {
		align-content: space-between !important;
	}
	.align-content-xl-around {
		align-content: space-around !important;
	}
	.align-content-xl-stretch {
		align-content: stretch !important;
	}
	.align-self-xl-auto {
		align-self: auto !important;
	}
	.align-self-xl-start {
		align-self: flex-start !important;
	}
	.align-self-xl-end {
		align-self: flex-end !important;
	}
	.align-self-xl-center {
		align-self: center !important;
	}
	.align-self-xl-baseline {
		align-self: baseline !important;
	}
	.align-self-xl-stretch {
		align-self: stretch !important;
	}
}

@media (min-width: 1600px) {
	.flex-xxl-row {
		flex-direction: row !important;
	}
	.flex-xxl-column {
		flex-direction: column !important;
	}
	.flex-xxl-row-reverse {
		flex-direction: row-reverse !important;
	}
	.flex-xxl-column-reverse {
		flex-direction: column-reverse !important;
	}
	.flex-xxl-wrap {
		flex-wrap: wrap !important;
	}
	.flex-xxl-nowrap {
		flex-wrap: nowrap !important;
	}
	.flex-xxl-wrap-reverse {
		flex-wrap: wrap-reverse !important;
	}
	.justify-content-xxl-start {
		justify-content: flex-start !important;
	}
	.justify-content-xxl-end {
		justify-content: flex-end !important;
	}
	.justify-content-xxl-center {
		justify-content: center !important;
	}
	.justify-content-xxl-between {
		justify-content: space-between !important;
	}
	.justify-content-xxl-around {
		justify-content: space-around !important;
	}
	.align-items-xxl-start {
		align-items: flex-start !important;
	}
	.align-items-xxl-end {
		align-items: flex-end !important;
	}
	.align-items-xxl-center {
		align-items: center !important;
	}
	.align-items-xxl-baseline {
		align-items: baseline !important;
	}
	.align-items-xxl-stretch {
		align-items: stretch !important;
	}
	.align-content-xxl-start {
		align-content: flex-start !important;
	}
	.align-content-xxl-end {
		align-content: flex-end !important;
	}
	.align-content-xxl-center {
		align-content: center !important;
	}
	.align-content-xxl-between {
		align-content: space-between !important;
	}
	.align-content-xxl-around {
		align-content: space-around !important;
	}
	.align-content-xxl-stretch {
		align-content: stretch !important;
	}
	.align-self-xxl-auto {
		align-self: auto !important;
	}
	.align-self-xxl-start {
		align-self: flex-start !important;
	}
	.align-self-xxl-end {
		align-self: flex-end !important;
	}
	.align-self-xxl-center {
		align-self: center !important;
	}
	.align-self-xxl-baseline {
		align-self: baseline !important;
	}
	.align-self-xxl-stretch {
		align-self: stretch !important;
	}
}

.float-left {
	float: left !important;
}

.float-right {
	float: right !important;
}

.float-none {
	float: none !important;
}

@media (min-width: 576px) {
	.float-sm-left {
		float: left !important;
	}
	.float-sm-right {
		float: right !important;
	}
	.float-sm-none {
		float: none !important;
	}
}

@media (min-width: 768px) {
	.float-md-left {
		float: left !important;
	}
	.float-md-right {
		float: right !important;
	}
	.float-md-none {
		float: none !important;
	}
}

@media (min-width: 992px) {
	.float-lg-left {
		float: left !important;
	}
	.float-lg-right {
		float: right !important;
	}
	.float-lg-none {
		float: none !important;
	}
}

@media (min-width: 1200px) {
	.float-xl-left {
		float: left !important;
	}
	.float-xl-right {
		float: right !important;
	}
	.float-xl-none {
		float: none !important;
	}
}

@media (min-width: 1600px) {
	.float-xxl-left {
		float: left !important;
	}
	.float-xxl-right {
		float: right !important;
	}
	.float-xxl-none {
		float: none !important;
	}
}

.position-static {
	position: static !important;
}

.position-relative {
	position: relative !important;
}

.position-absolute {
	position: absolute !important;
}

.position-fixed {
	position: fixed !important;
}

.position-sticky {
	position: sticky !important;
}

.fixed-top {
	position: fixed;
	top: 0;
	right: 0;
	left: 0;
	z-index: 1030;
}

.fixed-bottom {
	position: fixed;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1030;
}

@supports (position: sticky) {
	.sticky-top {
		position: sticky;
		top: 0;
		z-index: 1020;
	}
}

.sr-only {
	position: absolute;
	width: 1px;
	height: 1px;
	padding: 0;
	overflow: hidden;
	clip: rect(0, 0, 0, 0);
	white-space: nowrap;
	clip-path: inset(50%);
	border: 0;
}

.sr-only-focusable:active, .sr-only-focusable:focus {
	position: static;
	width: auto;
	height: auto;
	overflow: visible;
	clip: auto;
	white-space: normal;
	clip-path: none;
}

.w-25 {
	width: 25% !important;
}

.w-50 {
	width: 50% !important;
}

.w-75 {
	width: 75% !important;
}

.w-100 {
	width: 100% !important;
}

.h-25 {
	height: 25% !important;
}

.h-50 {
	height: 50% !important;
}

.h-75 {
	height: 75% !important;
}

.h-100 {
	height: 100% !important;
}

.mw-100 {
	max-width: 100% !important;
}

.mh-100 {
	max-height: 100% !important;
}

.m-0 {
	margin: 0 !important;
}

.mt-0,
.my-0 {
	margin-top: 0 !important;
}

.mr-0,
.mx-0 {
	margin-right: 0 !important;
}

.mb-0,
.my-0 {
	margin-bottom: 0 !important;}

.ml-0,
.mx-0 {
	margin-left: 0 !important;
}

.m-1 {
	margin: 0.25rem !important;
}

.mt-1,
.my-1 {
	margin-top: 0.25rem !important;
}

.mr-1,
.mx-1 {
	margin-right: 0.25rem !important;
}

.mb-1,
.my-1 {
	margin-bottom: 0.25rem !important;
}

.ml-1,
.mx-1 {
	margin-left: 0.25rem !important;
}

.m-2 {
	margin: 0.5rem !important;
}

.mt-2,
.my-2 {
	margin-top: 0.5rem !important;
}

.mr-2,
.mx-2 {
	margin-right: 0.5rem !important;
}

.mb-2,
.my-2 {
	margin-bottom: 0.5rem !important;
}

.ml-2,
.mx-2 {
	margin-left: 0.5rem !important;
}

.m-3 {
	margin: 1rem !important;
}

.mt-3,
.my-3 {
	margin-top: 1rem !important;
}

.mr-3,
.mx-3 {
	margin-right: 1rem !important;
}

.mb-3,
.my-3 {
	margin-bottom: 1rem !important;
}

.ml-3,
.mx-3 {
	margin-left: 1rem !important;
}

.m-4 {
	margin: 1.5rem !important;
}

.mt-4,
.my-4 {
	margin-top: 1.5rem !important;
}

.mr-4,
.mx-4 {
	margin-right: 1.5rem !important;
}

.mb-4,
.my-4 {
	margin-bottom: 1.5rem !important;
}

.ml-4,
.mx-4 {
	margin-left: 1.5rem !important;
}

.m-5 {
	margin: 3rem !important;
}

.mt-5,
.my-5 {
	margin-top: 3rem !important;
}

.mr-5,
.mx-5 {
	margin-right: 3rem !important;
}

.mb-5,
.my-5 {
	margin-bottom: 3rem !important;
}

.ml-5,
.mx-5 {
	margin-left: 3rem !important;
}

.p-0 {
	padding: 0 !important;
}

.pt-0,
.py-0 {
	padding-top: 0 !important;
}

.pr-0,
.px-0 {
	padding-right: 0 !important;
}

.pb-0,
.py-0 {
	padding-bottom: 0 !important;
}

.pl-0,
.px-0 {
	padding-left: 0 !important;
}

.p-1 {
	padding: 0.25rem !important;
}

.pt-1,
.py-1 {
	padding-top: 0.25rem !important;
}

.pr-1,
.px-1 {
	padding-right: 0.25rem !important;
}

.pb-1,
.py-1 {
	padding-bottom: 0.25rem !important;
}

.pl-1,
.px-1 {
	padding-left: 0.25rem !important;
}

.p-2 {
	padding: 0.5rem !important;
}

.pt-2,
.py-2 {
	padding-top: 0.5rem !important;
}

.pr-2,
.px-2 {
	padding-right: 0.5rem !important;
}

.pb-2,
.py-2 {
	padding-bottom: 0.5rem !important;
}

.pl-2,
.px-2 {
	padding-left: 0.5rem !important;
}

.p-3 {
	padding: 1rem !important;
}

.pt-3,
.py-3 {
	padding-top: 1rem !important;
}

.pr-3,
.px-3 {
	padding-right: 1rem !important;
}

.pb-3,
.py-3 {
	padding-bottom: 1rem !important;
}

.pl-3,
.px-3 {
	padding-left: 1rem !important;
}

.p-4 {
	padding: 1.5rem !important;
}

.pt-4,
.py-4 {
	padding-top: 1.5rem !important;
}

.pr-4,
.px-4 {
	padding-right: 1.5rem !important;
}

.pb-4,
.py-4 {
	padding-bottom: 1.5rem !important;
}

.pl-4,
.px-4 {
	padding-left: 1.5rem !important;
}

.p-5 {
	padding: 3rem !important;
}

.pt-5,
.py-5 {
	padding-top: 3rem !important;
}

.pr-5,
.px-5 {
	padding-right: 3rem !important;
}

.pb-5,
.py-5 {
	padding-bottom: 3rem !important;
}

.pl-5,
.px-5 {
	padding-left: 3rem !important;
}

.m-auto {
	margin: auto !important;
}

.mt-auto,
.my-auto {
	margin-top: auto !important;
}

.mr-auto,
.mx-auto {
	margin-right: auto !important;
}

.mb-auto,
.my-auto {
	margin-bottom: auto !important;
}

.ml-auto,
.mx-auto {
	margin-left: auto !important;
}

@media (min-width: 576px) {
	.m-sm-0 {
		margin: 0 !important;
	}
	.mt-sm-0,
	.my-sm-0 {
		margin-top: 0 !important;
	}
	.mr-sm-0,
	.mx-sm-0 {
		margin-right: 0 !important;
	}
	.mb-sm-0,
	.my-sm-0 {
		margin-bottom: 0 !important;
	}
	.ml-sm-0,
	.mx-sm-0 {
		margin-left: 0 !important;
	}
	.m-sm-1 {
		margin: 0.25rem !important;
	}
	.mt-sm-1,
	.my-sm-1 {
		margin-top: 0.25rem !important;
	}
	.mr-sm-1,
	.mx-sm-1 {
		margin-right: 0.25rem !important;
	}
	.mb-sm-1,
	.my-sm-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-sm-1,
	.mx-sm-1 {
		margin-left: 0.25rem !important;
	}
	.m-sm-2 {
		margin: 0.5rem !important;
	}
	.mt-sm-2,
	.my-sm-2 {
		margin-top: 0.5rem !important;
	}
	.mr-sm-2,
	.mx-sm-2 {
		margin-right: 0.5rem !important;
	}
	.mb-sm-2,
	.my-sm-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-sm-2,
	.mx-sm-2 {
		margin-left: 0.5rem !important;
	}
	.m-sm-3 {
		margin: 1rem !important;
	}
	.mt-sm-3,
	.my-sm-3 {
		margin-top: 1rem !important;
	}
	.mr-sm-3,
	.mx-sm-3 {
		margin-right: 1rem !important;
	}
	.mb-sm-3,
	.my-sm-3 {
		margin-bottom: 1rem !important;
	}
	.ml-sm-3,
	.mx-sm-3 {
		margin-left: 1rem !important;
	}
	.m-sm-4 {
		margin: 1.5rem !important;
	}
	.mt-sm-4,
	.my-sm-4 {
		margin-top: 1.5rem !important;
	}
	.mr-sm-4,
	.mx-sm-4 {
		margin-right: 1.5rem !important;
	}
	.mb-sm-4,
	.my-sm-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-sm-4,
	.mx-sm-4 {
		margin-left: 1.5rem !important;
	}
	.m-sm-5 {
		margin: 3rem !important;
	}
	.mt-sm-5,
	.my-sm-5 {
		margin-top: 3rem !important;
	}
	.mr-sm-5,
	.mx-sm-5 {
		margin-right: 3rem !important;
	}
	.mb-sm-5,
	.my-sm-5 {
		margin-bottom: 3rem !important;
	}
	.ml-sm-5,
	.mx-sm-5 {
		margin-left: 3rem !important;
	}
	.p-sm-0 {
		padding: 0 !important;
	}
	.pt-sm-0,
	.py-sm-0 {
		padding-top: 0 !important;
	}
	.pr-sm-0,
	.px-sm-0 {
		padding-right: 0 !important;
	}
	.pb-sm-0,
	.py-sm-0 {
		padding-bottom: 0 !important;
	}
	.pl-sm-0,
	.px-sm-0 {
		padding-left: 0 !important;
	}
	.p-sm-1 {
		padding: 0.25rem !important;
	}
	.pt-sm-1,
	.py-sm-1 {
		padding-top: 0.25rem !important;
	}
	.pr-sm-1,
	.px-sm-1 {
		padding-right: 0.25rem !important;
	}
	.pb-sm-1,
	.py-sm-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-sm-1,
	.px-sm-1 {
		padding-left: 0.25rem !important;
	}
	.p-sm-2 {
		padding: 0.5rem !important;
	}
	.pt-sm-2,
	.py-sm-2 {
		padding-top: 0.5rem !important;
	}
	.pr-sm-2,
	.px-sm-2 {
		padding-right: 0.5rem !important;
	}
	.pb-sm-2,
	.py-sm-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-sm-2,
	.px-sm-2 {
		padding-left: 0.5rem !important;
	}
	.p-sm-3 {
		padding: 1rem !important;
	}
	.pt-sm-3,
	.py-sm-3 {
		padding-top: 1rem !important;
	}
	.pr-sm-3,
	.px-sm-3 {
		padding-right: 1rem !important;
	}
	.pb-sm-3,
	.py-sm-3 {
		padding-bottom: 1rem !important;
	}
	.pl-sm-3,
	.px-sm-3 {
		padding-left: 1rem !important;
	}
	.p-sm-4 {
		padding: 1.5rem !important;
	}
	.pt-sm-4,
	.py-sm-4 {
		padding-top: 1.5rem !important;
	}
	.pr-sm-4,
	.px-sm-4 {
		padding-right: 1.5rem !important;
	}
	.pb-sm-4,
	.py-sm-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-sm-4,
	.px-sm-4 {
		padding-left: 1.5rem !important;
	}
	.p-sm-5 {
		padding: 3rem !important;
	}
	.pt-sm-5,
	.py-sm-5 {
		padding-top: 3rem !important;
	}
	.pr-sm-5,
	.px-sm-5 {
		padding-right: 3rem !important;
	}
	.pb-sm-5,
	.py-sm-5 {
		padding-bottom: 3rem !important;
	}
	.pl-sm-5,
	.px-sm-5 {
		padding-left: 3rem !important;
	}
	.m-sm-auto {
		margin: auto !important;
	}
	.mt-sm-auto,
	.my-sm-auto {
		margin-top: auto !important;
	}
	.mr-sm-auto,
	.mx-sm-auto {
		margin-right: auto !important;
	}
	.mb-sm-auto,
	.my-sm-auto {
		margin-bottom: auto !important;
	}
	.ml-sm-auto,
	.mx-sm-auto {
		margin-left: auto !important;
	}
}

@media (min-width: 768px) {
	.m-md-0 {
		margin: 0 !important;
	}
	.mt-md-0,
	.my-md-0 {
		margin-top: 0 !important;
	}
	.mr-md-0,
	.mx-md-0 {
		margin-right: 0 !important;
	}
	.mb-md-0,
	.my-md-0 {
		margin-bottom: 0 !important;
	}
	.ml-md-0,
	.mx-md-0 {
		margin-left: 0 !important;
	}
	.m-md-1 {
		margin: 0.25rem !important;
	}
	.mt-md-1,
	.my-md-1 {
		margin-top: 0.25rem !important;
	}
	.mr-md-1,
	.mx-md-1 {
		margin-right: 0.25rem !important;
	}
	.mb-md-1,
	.my-md-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-md-1,
	.mx-md-1 {
		margin-left: 0.25rem !important;
	}
	.m-md-2 {
		margin: 0.5rem !important;
	}
	.mt-md-2,
	.my-md-2 {
		margin-top: 0.5rem !important;
	}
	.mr-md-2,
	.mx-md-2 {
		margin-right: 0.5rem !important;
	}
	.mb-md-2,
	.my-md-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-md-2,
	.mx-md-2 {
		margin-left: 0.5rem !important;
	}
	.m-md-3 {
		margin: 1rem !important;
	}
	.mt-md-3,
	.my-md-3 {
		margin-top: 1rem !important;
	}
	.mr-md-3,
	.mx-md-3 {
		margin-right: 1rem !important;
	}
	.mb-md-3,
	.my-md-3 {
		margin-bottom: 1rem !important;
	}
	.ml-md-3,
	.mx-md-3 {
		margin-left: 1rem !important;
	}
	.m-md-4 {
		margin: 1.5rem !important;
	}
	.mt-md-4,
	.my-md-4 {
		margin-top: 1.5rem !important;
	}
	.mr-md-4,
	.mx-md-4 {
		margin-right: 1.5rem !important;
	}
	.mb-md-4,
	.my-md-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-md-4,
	.mx-md-4 {
		margin-left: 1.5rem !important;
	}
	.m-md-5 {
		margin: 3rem !important;
	}
	.mt-md-5,
	.my-md-5 {
		margin-top: 3rem !important;
	}
	.mr-md-5,
	.mx-md-5 {
		margin-right: 3rem !important;
	}
	.mb-md-5,
	.my-md-5 {
		margin-bottom: 3rem !important;
	}
	.ml-md-5,
	.mx-md-5 {
		margin-left: 3rem !important;
	}
	.p-md-0 {
		padding: 0 !important;
	}
	.pt-md-0,
	.py-md-0 {
		padding-top: 0 !important;
	}
	.pr-md-0,
	.px-md-0 {
		padding-right: 0 !important;
	}
	.pb-md-0,
	.py-md-0 {
		padding-bottom: 0 !important;
	}
	.pl-md-0,
	.px-md-0 {
		padding-left: 0 !important;
	}
	.p-md-1 {
		padding: 0.25rem !important;
	}
	.pt-md-1,
	.py-md-1 {
		padding-top: 0.25rem !important;
	}
	.pr-md-1,
	.px-md-1 {
		padding-right: 0.25rem !important;
	}
	.pb-md-1,
	.py-md-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-md-1,
	.px-md-1 {
		padding-left: 0.25rem !important;
	}
	.p-md-2 {
		padding: 0.5rem !important;
	}
	.pt-md-2,
	.py-md-2 {
		padding-top: 0.5rem !important;
	}
	.pr-md-2,
	.px-md-2 {
		padding-right: 0.5rem !important;
	}
	.pb-md-2,
	.py-md-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-md-2,
	.px-md-2 {
		padding-left: 0.5rem !important;
	}
	.p-md-3 {
		padding: 1rem !important;
	}
	.pt-md-3,
	.py-md-3 {
		padding-top: 1rem !important;
	}
	.pr-md-3,
	.px-md-3 {
		padding-right: 1rem !important;
	}
	.pb-md-3,
	.py-md-3 {
		padding-bottom: 1rem !important;
	}
	.pl-md-3,
	.px-md-3 {
		padding-left: 1rem !important;
	}
	.p-md-4 {
		padding: 1.5rem !important;
	}
	.pt-md-4,
	.py-md-4 {
		padding-top: 1.5rem !important;
	}
	.pr-md-4,
	.px-md-4 {
		padding-right: 1.5rem !important;
	}
	.pb-md-4,
	.py-md-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-md-4,
	.px-md-4 {
		padding-left: 1.5rem !important;
	}
	.p-md-5 {
		padding: 3rem !important;
	}
	.pt-md-5,
	.py-md-5 {
		padding-top: 3rem !important;
	}
	.pr-md-5,
	.px-md-5 {
		padding-right: 3rem !important;
	}
	.pb-md-5,
	.py-md-5 {
		padding-bottom: 3rem !important;
	}
	.pl-md-5,
	.px-md-5 {
		padding-left: 3rem !important;
	}
	.m-md-auto {
		margin: auto !important;
	}
	.mt-md-auto,
	.my-md-auto {
		margin-top: auto !important;
	}
	.mr-md-auto,
	.mx-md-auto {
		margin-right: auto !important;
	}
	.mb-md-auto,
	.my-md-auto {
		margin-bottom: auto !important;
	}
	.ml-md-auto,
	.mx-md-auto {
		margin-left: auto !important;
	}
}

@media (min-width: 992px) {
	.m-lg-0 {
		margin: 0 !important;
	}
	.mt-lg-0,
	.my-lg-0 {
		margin-top: 0 !important;
	}
	.mr-lg-0,
	.mx-lg-0 {
		margin-right: 0 !important;
	}
	.mb-lg-0,
	.my-lg-0 {
		margin-bottom: 0 !important;
	}
	.ml-lg-0,
	.mx-lg-0 {
		margin-left: 0 !important;
	}
	.m-lg-1 {
		margin: 0.25rem !important;
	}
	.mt-lg-1,
	.my-lg-1 {
		margin-top: 0.25rem !important;
	}
	.mr-lg-1,
	.mx-lg-1 {
		margin-right: 0.25rem !important;
	}
	.mb-lg-1,
	.my-lg-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-lg-1,
	.mx-lg-1 {
		margin-left: 0.25rem !important;
	}
	.m-lg-2 {
		margin: 0.5rem !important;
	}
	.mt-lg-2,
	.my-lg-2 {
		margin-top: 0.5rem !important;
	}
	.mr-lg-2,
	.mx-lg-2 {
		margin-right: 0.5rem !important;
	}
	.mb-lg-2,
	.my-lg-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-lg-2,
	.mx-lg-2 {
		margin-left: 0.5rem !important;
	}
	.m-lg-3 {
		margin: 1rem !important;
	}
	.mt-lg-3,
	.my-lg-3 {
		margin-top: 1rem !important;
	}
	.mr-lg-3,
	.mx-lg-3 {
		margin-right: 1rem !important;
	}
	.mb-lg-3,
	.my-lg-3 {
		margin-bottom: 1rem !important;
	}
	.ml-lg-3,
	.mx-lg-3 {
		margin-left: 1rem !important;
	}
	.m-lg-4 {
		margin: 1.5rem !important;
	}
	.mt-lg-4,
	.my-lg-4 {
		margin-top: 1.5rem !important;
	}
	.mr-lg-4,
	.mx-lg-4 {
		margin-right: 1.5rem !important;
	}
	.mb-lg-4,
	.my-lg-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-lg-4,
	.mx-lg-4 {
		margin-left: 1.5rem !important;
	}
	.m-lg-5 {
		margin: 3rem !important;
	}
	.mt-lg-5,
	.my-lg-5 {
		margin-top: 3rem !important;
	}
	.mr-lg-5,
	.mx-lg-5 {
		margin-right: 3rem !important;
	}
	.mb-lg-5,
	.my-lg-5 {
		margin-bottom: 3rem !important;
	}
	.ml-lg-5,
	.mx-lg-5 {
		margin-left: 3rem !important;
	}
	.p-lg-0 {
		padding: 0 !important;
	}
	.pt-lg-0,
	.py-lg-0 {
		padding-top: 0 !important;
	}
	.pr-lg-0,
	.px-lg-0 {
		padding-right: 0 !important;
	}
	.pb-lg-0,
	.py-lg-0 {
		padding-bottom: 0 !important;
	}
	.pl-lg-0,
	.px-lg-0 {
		padding-left: 0 !important;
	}
	.p-lg-1 {
		padding: 0.25rem !important;
	}
	.pt-lg-1,
	.py-lg-1 {
		padding-top: 0.25rem !important;
	}
	.pr-lg-1,
	.px-lg-1 {
		padding-right: 0.25rem !important;
	}
	.pb-lg-1,
	.py-lg-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-lg-1,
	.px-lg-1 {
		padding-left: 0.25rem !important;
	}
	.p-lg-2 {
		padding: 0.5rem !important;
	}
	.pt-lg-2,
	.py-lg-2 {
		padding-top: 0.5rem !important;
	}
	.pr-lg-2,
	.px-lg-2 {
		padding-right: 0.5rem !important;
	}
	.pb-lg-2,
	.py-lg-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-lg-2,
	.px-lg-2 {
		padding-left: 0.5rem !important;
	}
	.p-lg-3 {
		padding: 1rem !important;
	}
	.pt-lg-3,
	.py-lg-3 {
		padding-top: 1rem !important;
	}
	.pr-lg-3,
	.px-lg-3 {
		padding-right: 1rem !important;
	}
	.pb-lg-3,
	.py-lg-3 {
		padding-bottom: 1rem !important;
	}
	.pl-lg-3,
	.px-lg-3 {
		padding-left: 1rem !important;
	}
	.p-lg-4 {
		padding: 1.5rem !important;
	}
	.pt-lg-4,
	.py-lg-4 {
		padding-top: 1.5rem !important;
	}
	.pr-lg-4,
	.px-lg-4 {
		padding-right: 1.5rem !important;
	}
	.pb-lg-4,
	.py-lg-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-lg-4,
	.px-lg-4 {
		padding-left: 1.5rem !important;
	}
	.p-lg-5 {
		padding: 3rem !important;
	}
	.pt-lg-5,
	.py-lg-5 {
		padding-top: 3rem !important;
	}
	.pr-lg-5,
	.px-lg-5 {
		padding-right: 3rem !important;
	}
	.pb-lg-5,
	.py-lg-5 {
		padding-bottom: 3rem !important;
	}
	.pl-lg-5,
	.px-lg-5 {
		padding-left: 3rem !important;
	}
	.m-lg-auto {
		margin: auto !important;
	}
	.mt-lg-auto,
	.my-lg-auto {
		margin-top: auto !important;
	}
	.mr-lg-auto,
	.mx-lg-auto {
		margin-right: auto !important;
	}
	.mb-lg-auto,
	.my-lg-auto {
		margin-bottom: auto !important;
	}
	.ml-lg-auto,
	.mx-lg-auto {
		margin-left: auto !important;
	}
}

@media (min-width: 1200px) {
	.m-xl-0 {
		margin: 0 !important;
	}
	.mt-xl-0,
	.my-xl-0 {
		margin-top: 0 !important;
	}
	.mr-xl-0,
	.mx-xl-0 {
		margin-right: 0 !important;
	}
	.mb-xl-0,
	.my-xl-0 {
		margin-bottom: 0 !important;
	}
	.ml-xl-0,
	.mx-xl-0 {
		margin-left: 0 !important;
	}
	.m-xl-1 {
		margin: 0.25rem !important;
	}
	.mt-xl-1,
	.my-xl-1 {
		margin-top: 0.25rem !important;
	}
	.mr-xl-1,
	.mx-xl-1 {
		margin-right: 0.25rem !important;
	}
	.mb-xl-1,
	.my-xl-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-xl-1,
	.mx-xl-1 {
		margin-left: 0.25rem !important;
	}
	.m-xl-2 {
		margin: 0.5rem !important;
	}
	.mt-xl-2,
	.my-xl-2 {
		margin-top: 0.5rem !important;
	}
	.mr-xl-2,
	.mx-xl-2 {
		margin-right: 0.5rem !important;
	}
	.mb-xl-2,
	.my-xl-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-xl-2,
	.mx-xl-2 {
		margin-left: 0.5rem !important;
	}
	.m-xl-3 {
		margin: 1rem !important;
	}
	.mt-xl-3,
	.my-xl-3 {
		margin-top: 1rem !important;
	}
	.mr-xl-3,
	.mx-xl-3 {
		margin-right: 1rem !important;
	}
	.mb-xl-3,
	.my-xl-3 {
		margin-bottom: 1rem !important;
	}
	.ml-xl-3,
	.mx-xl-3 {
		margin-left: 1rem !important;
	}
	.m-xl-4 {
		margin: 1.5rem !important;
	}
	.mt-xl-4,
	.my-xl-4 {
		margin-top: 1.5rem !important;
	}
	.mr-xl-4,
	.mx-xl-4 {
		margin-right: 1.5rem !important;
	}
	.mb-xl-4,
	.my-xl-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-xl-4,
	.mx-xl-4 {
		margin-left: 1.5rem !important;
	}
	.m-xl-5 {
		margin: 3rem !important;
	}
	.mt-xl-5,
	.my-xl-5 {
		margin-top: 3rem !important;
	}
	.mr-xl-5,
	.mx-xl-5 {
		margin-right: 3rem !important;
	}
	.mb-xl-5,
	.my-xl-5 {
		margin-bottom: 3rem !important;
	}
	.ml-xl-5,
	.mx-xl-5 {
		margin-left: 3rem !important;
	}
	.p-xl-0 {
		padding: 0 !important;
	}
	.pt-xl-0,
	.py-xl-0 {
		padding-top: 0 !important;
	}
	.pr-xl-0,
	.px-xl-0 {
		padding-right: 0 !important;
	}
	.pb-xl-0,
	.py-xl-0 {
		padding-bottom: 0 !important;
	}
	.pl-xl-0,
	.px-xl-0 {
		padding-left: 0 !important;
	}
	.p-xl-1 {
		padding: 0.25rem !important;
	}
	.pt-xl-1,
	.py-xl-1 {
		padding-top: 0.25rem !important;
	}
	.pr-xl-1,
	.px-xl-1 {
		padding-right: 0.25rem !important;
	}
	.pb-xl-1,
	.py-xl-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-xl-1,
	.px-xl-1 {
		padding-left: 0.25rem !important;
	}
	.p-xl-2 {
		padding: 0.5rem !important;
	}
	.pt-xl-2,
	.py-xl-2 {
		padding-top: 0.5rem !important;
	}
	.pr-xl-2,
	.px-xl-2 {
		padding-right: 0.5rem !important;
	}
	.pb-xl-2,
	.py-xl-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-xl-2,
	.px-xl-2 {
		padding-left: 0.5rem !important;
	}
	.p-xl-3 {
		padding: 1rem !important;
	}
	.pt-xl-3,
	.py-xl-3 {
		padding-top: 1rem !important;
	}
	.pr-xl-3,
	.px-xl-3 {
		padding-right: 1rem !important;
	}
	.pb-xl-3,
	.py-xl-3 {
		padding-bottom: 1rem !important;
	}
	.pl-xl-3,
	.px-xl-3 {
		padding-left: 1rem !important;
	}
	.p-xl-4 {
		padding: 1.5rem !important;
	}
	.pt-xl-4,
	.py-xl-4 {
		padding-top: 1.5rem !important;
	}
	.pr-xl-4,
	.px-xl-4 {
		padding-right: 1.5rem !important;
	}
	.pb-xl-4,
	.py-xl-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-xl-4,
	.px-xl-4 {
		padding-left: 1.5rem !important;
	}
	.p-xl-5 {
		padding: 3rem !important;
	}
	.pt-xl-5,
	.py-xl-5 {
		padding-top: 3rem !important;
	}
	.pr-xl-5,
	.px-xl-5 {
		padding-right: 3rem !important;
	}
	.pb-xl-5,
	.py-xl-5 {
		padding-bottom: 3rem !important;
	}
	.pl-xl-5,
	.px-xl-5 {
		padding-left: 3rem !important;
	}
	.m-xl-auto {
		margin: auto !important;
	}
	.mt-xl-auto,
	.my-xl-auto {
		margin-top: auto !important;
	}
	.mr-xl-auto,
	.mx-xl-auto {
		margin-right: auto !important;
	}
	.mb-xl-auto,
	.my-xl-auto {
		margin-bottom: auto !important;
	}
	.ml-xl-auto,
	.mx-xl-auto {
		margin-left: auto !important;
	}
}

@media (min-width: 1600px) {
	.m-xxl-0 {
		margin: 0 !important;
	}
	.mt-xxl-0,
	.my-xxl-0 {
		margin-top: 0 !important;
	}
	.mr-xxl-0,
	.mx-xxl-0 {
		margin-right: 0 !important;
	}
	.mb-xxl-0,
	.my-xxl-0 {
		margin-bottom: 0 !important;
	}
	.ml-xxl-0,
	.mx-xxl-0 {
		margin-left: 0 !important;
	}
	.m-xxl-1 {
		margin: 0.25rem !important;
	}
	.mt-xxl-1,
	.my-xxl-1 {
		margin-top: 0.25rem !important;
	}
	.mr-xxl-1,
	.mx-xxl-1 {
		margin-right: 0.25rem !important;
	}
	.mb-xxl-1,
	.my-xxl-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-xxl-1,
	.mx-xxl-1 {
		margin-left: 0.25rem !important;
	}
	.m-xxl-2 {
		margin: 0.5rem !important;
	}
	.mt-xxl-2,
	.my-xxl-2 {
		margin-top: 0.5rem !important;
	}
	.mr-xxl-2,
	.mx-xxl-2 {
		margin-right: 0.5rem !important;
	}
	.mb-xxl-2,
	.my-xxl-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-xxl-2,
	.mx-xxl-2 {
		margin-left: 0.5rem !important;
	}
	.m-xxl-3 {
		margin: 1rem !important;
	}
	.mt-xxl-3,
	.my-xxl-3 {
		margin-top: 1rem !important;
	}
	.mr-xxl-3,
	.mx-xxl-3 {
		margin-right: 1rem !important;
	}
	.mb-xxl-3,
	.my-xxl-3 {
		margin-bottom: 1rem !important;
	}
	.ml-xxl-3,
	.mx-xxl-3 {
		margin-left: 1rem !important;
	}
	.m-xxl-4 {
		margin: 1.5rem !important;
	}
	.mt-xxl-4,
	.my-xxl-4 {
		margin-top: 1.5rem !important;
	}
	.mr-xxl-4,
	.mx-xxl-4 {
		margin-right: 1.5rem !important;
	}
	.mb-xxl-4,
	.my-xxl-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-xxl-4,
	.mx-xxl-4 {
		margin-left: 1.5rem !important;
	}
	.m-xxl-5 {
		margin: 3rem !important;
	}
	.mt-xxl-5,
	.my-xxl-5 {
		margin-top: 3rem !important;
	}
	.mr-xxl-5,
	.mx-xxl-5 {
		margin-right: 3rem !important;
	}
	.mb-xxl-5,
	.my-xxl-5 {
		margin-bottom: 3rem !important;
	}
	.ml-xxl-5,
	.mx-xxl-5 {
		margin-left: 3rem !important;
	}
	.p-xxl-0 {
		padding: 0 !important;
	}
	.pt-xxl-0,
	.py-xxl-0 {
		padding-top: 0 !important;
	}
	.pr-xxl-0,
	.px-xxl-0 {
		padding-right: 0 !important;
	}
	.pb-xxl-0,
	.py-xxl-0 {
		padding-bottom: 0 !important;
	}
	.pl-xxl-0,
	.px-xxl-0 {
		padding-left: 0 !important;
	}
	.p-xxl-1 {
		padding: 0.25rem !important;
	}
	.pt-xxl-1,
	.py-xxl-1 {
		padding-top: 0.25rem !important;
	}
	.pr-xxl-1,
	.px-xxl-1 {
		padding-right: 0.25rem !important;
	}
	.pb-xxl-1,
	.py-xxl-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-xxl-1,
	.px-xxl-1 {
		padding-left: 0.25rem !important;
	}
	.p-xxl-2 {
		padding: 0.5rem !important;
	}
	.pt-xxl-2,
	.py-xxl-2 {
		padding-top: 0.5rem !important;
	}
	.pr-xxl-2,
	.px-xxl-2 {
		padding-right: 0.5rem !important;
	}
	.pb-xxl-2,
	.py-xxl-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-xxl-2,
	.px-xxl-2 {
		padding-left: 0.5rem !important;
	}
	.p-xxl-3 {
		padding: 1rem !important;
	}
	.pt-xxl-3,
	.py-xxl-3 {
		padding-top: 1rem !important;
	}
	.pr-xxl-3,
	.px-xxl-3 {
		padding-right: 1rem !important;
	}
	.pb-xxl-3,
	.py-xxl-3 {
		padding-bottom: 1rem !important;
	}
	.pl-xxl-3,
	.px-xxl-3 {
		padding-left: 1rem !important;
	}
	.p-xxl-4 {
		padding: 1.5rem !important;
	}
	.pt-xxl-4,
	.py-xxl-4 {
		padding-top: 1.5rem !important;
	}
	.pr-xxl-4,
	.px-xxl-4 {
		padding-right: 1.5rem !important;
	}
	.pb-xxl-4,
	.py-xxl-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-xxl-4,
	.px-xxl-4 {
		padding-left: 1.5rem !important;
	}
	.p-xxl-5 {
		padding: 3rem !important;
	}
	.pt-xxl-5,
	.py-xxl-5 {
		padding-top: 3rem !important;
	}
	.pr-xxl-5,
	.px-xxl-5 {
		padding-right: 3rem !important;
	}
	.pb-xxl-5,
	.py-xxl-5 {
		padding-bottom: 3rem !important;
	}
	.pl-xxl-5,
	.px-xxl-5 {
		padding-left: 3rem !important;
	}
	.m-xxl-auto {
		margin: auto !important;
	}
	.mt-xxl-auto,
	.my-xxl-auto {
		margin-top: auto !important;
	}
	.mr-xxl-auto,
	.mx-xxl-auto {
		margin-right: auto !important;
	}
	.mb-xxl-auto,
	.my-xxl-auto {
		margin-bottom: auto !important;
	}
	.ml-xxl-auto,
	.mx-xxl-auto {
		margin-left: auto !important;
	}
}

.text-justify {
	text-align: justify !important;
}

.text-nowrap {
	white-space: nowrap !important;
}

.text-truncate {
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}

.text-left {
	text-align: left !important;
}

.text-right {
	text-align: right !important;
}

.text-center {
	text-align: center !important;
}

@media (min-width: 576px) {
	.text-sm-left {
		text-align: left !important;
	}
	.text-sm-right {
		text-align: right !important;
	}
	.text-sm-center {
		text-align: center !important;
	}
}

@media (min-width: 768px) {
	.text-md-left {
		text-align: left !important;
	}
	.text-md-right {
		text-align: right !important;
	}
	.text-md-center {
		text-align: center !important;
	}
}

@media (min-width: 992px) {
	.text-lg-left {
		text-align: left !important;
	}
	.text-lg-right {
		text-align: right !important;
	}
	.text-lg-center {
		text-align: center !important;
	}
}
@media (min-width: 1200px) {
	.text-xl-left {
		text-align: left !important;
	}
	.text-xl-right {
		text-align: right !important;
	}
	.text-xl-center {
		text-align: center !important;
	}
}

@media (min-width: 1600px) {
	.text-xxl-left {
		text-align: left !important;
	}
	.text-xxl-right {
		text-align: right !important;
	}
	.text-xxl-center {
		text-align: center !important;
	}
}

.text-lowercase {
	text-transform: lowercase !important;
}

.text-uppercase {
	text-transform: uppercase !important;
}

.text-capitalize {
	text-transform: capitalize !important;
}

.font-weight-light {
	font-weight: 300 !important;
}

.font-weight-normal {
	font-weight: 400 !important;
}

.font-weight-bold {
	font-weight: 700 !important;
}

.font-italic {
	font-style: italic !important;
}

.text-white {
	color: #fff !important;
}

.text-muted {
	color: #6c757d !important;
}

.text-hide {
	font: 0/0 a;
	color: transparent;
	text-shadow: none;
	background-color: transparent;
	border: 0;
}

.visible {
	visibility: visible !important;
}

.invisible {
	visibility: hidden !important;
}

@media print {
	*,
	*::before,
	*::after {
		text-shadow: none !important;
		box-shadow: none !important;
	}
	a:not(.btn) {
		text-decoration: underline;
	}
	abbr[title]::after {
		content: " (" attr(title) ")";
	}
	pre {
		white-space: pre-wrap !important;
	}
	pre,
	blockquote {
		border: 1px solid #999;
		page-break-inside: avoid;
	}
	thead {
		display: table-header-group;
	}
	tr,
	img {
		page-break-inside: avoid;
	}
	p,
	h2,
	h3 {
		orphans: 3;
		widows: 3;
	}
	h2,
	h3 {
		page-break-after: avoid;
	}
	@page {
		size: a3;
	}
	body {
		min-width: 992px !important;
	}
	.container {
		min-width: 992px !important;
	}
	.navbar {
		display: none;
	}
	.badge {
		border: 1px solid #000;
	}
	.table {
		border-collapse: collapse !important;
	}
	.table td,
	.table th {
		background-color: #fff !important;
	}
	.table-bordered th,
	.table-bordered td {
		border: 1px solid #ddd !important;
	}
}

@charset "UTF-8";
/*
* Trunk version 2.0.0
*/
a:focus,
button:focus {
	outline: none !important;
}
a.disabled{
	pointer-events: none;
}
button::-moz-focus-inner {
	border: 0;
}

*:focus {
	outline: none;
}

blockquote {
	padding: 0;
	margin: 0;
}

input,
button,
select,
textarea {
	outline: none;
}

label {
	margin-bottom: 0;
}

p {
	margin: 0;
}

ul,
ol {
	list-style: none;
	padding: 0;
	margin: 0;
}

ul li,
ol li {
	display: block;
}

dl {
	margin: 0;
}

dt,
dd {
	line-height: inherit;
}

dt {
	font-weight: inherit;
}

dd {
	margin-bottom: 0;
}

cite {
	font-style: normal;
}

form {
	margin-bottom: 0;
}

blockquote {
	padding-left: 0;
	border-left: 0;
}

address {
	margin-top: 0;
	margin-bottom: 0;
}

figure {
	margin-bottom: 0;
}

html p a:hover {
	text-decoration: none;
}

/*
*
* Typography
*/
@font-face {
	font-family: "graphiklcweb";
	src: url(../fonts/graphiklcweb_medium.ttf);
	font-weight: 400;
	font-style: normal;
}


body {
	font-family: "graphiklcweb", sans-serif;
	font-size: 16px;
	line-height: 1.7;
	font-weight: 300;
	color: #15191f;
	background-color: #fff;
	-webkit-text-size-adjust: none;
	-webkit-font-smoothing: subpixel-antialiased;
	letter-spacing: .03em;
}

@media (min-width: 768px) {
	body {
		/*font-size: 16px;*/
		line-height: 1.4875;
	}
}

h1, h2, h3, h4, h5, h6, [class^='heading-'] {
	margin-top: 0;
	margin-bottom: 0;
	color: #29293a;
}

h1 a, h1 a:focus, h1 a:active, h2 a, h2 a:focus, h2 a:active, h3 a, h3 a:focus, h3 a:active, h4 a, h4 a:focus, h4 a:active, h5 a, h5 a:focus, h5 a:active, h6 a, h6 a:focus, h6 a:active, [class^='heading-'] a, [class^='heading-'] a:focus, [class^='heading-'] a:active {
	color: inherit;
}

h1 a:hover, h2 a:hover, h3 a:hover, h4 a:hover, h5 a:hover, h6 a:hover, [class^='heading-'] a:hover {
	color: #ef172c;
}

h1 span, h2 span, h3 span, h4 span, h5 span, h6 span, [class^='heading-'] span {
	display: inline-block;
}

h1 span[data-toggle='modal'], h2 span[data-toggle='modal'], h3 span[data-toggle='modal'], h4 span[data-toggle='modal'], h5 span[data-toggle='modal'], h6 span[data-toggle='modal'], [class^='heading-'] span[data-toggle='modal'] {
	border-bottom: 2px dashed rgba(195, 7, 52, 0.3);
	cursor: pointer;
}

h1 > span.icon, h2 > span.icon, h3 > span.icon, h4 > span.icon, h5 > span.icon, h6 > span.icon, [class^='heading-'] > span.icon {
	display: inline-block;
	margin-right: 5px;
}

h1,
.heading-1 {
	font-size: 30px;
	line-height: 1.15;
	letter-spacing: 0;
}

@media (min-width: 576px) {
	h1,
	.heading-1 {
		font-size: 32px;
	}
}

@media (min-width: 768px) {
	h1,
	.heading-1 {
		font-size: 46px;
		line-height: 1.25;
	}
}

@media (min-width: 992px) {
	h1,
	.heading-1 {
		font-size: 54px;
	}
}

@media (min-width: 1200px) {
	h1,
	.heading-1 {
		font-size: 58px;
	}
}

@media (min-width: 1600px) {
	h1,
	.heading-1 {
		font-size: 68px;
		line-height: 1.17647;
	}
}

h2,
.heading-2 {
	font-family: "Averia Libre";
	font-weight: 300;
	font-size: 28px;
	line-height: 1.4;
	letter-spacing: 0;
}

@media (min-width: 576px) {
	h2,
	.heading-2 {
		font-size: 30px;
	}
}

@media (min-width: 768px) {
	h2,
	.heading-2 {
		font-size: 44px;
	}
}

@media (min-width: 1200px) {
	h2,
	.heading-2 {
		font-size: 48px;
		line-height: 1.33333;
	}
}

h3,
.heading-3 {
	font-size: 24px;
	line-height: 1.3;
	letter-spacing: 0;
}

@media (min-width: 768px) {
	h3,
	.heading-3 {
		font-size: 30px;
		line-height: 1.4;
	}
}

@media (min-width: 1200px) {
	h3,
	.heading-3 {
		font-size: 36px;
		line-height: 1.33333;
	}
}

h3 .big,
.heading-3 .big {
	font-size: 2em;
	line-height: 1;
}

h4,
.heading-4 {
	font-size: 18px;
	line-height: 1.5;
	letter-spacing: 0;
}

@media (min-width: 1200px) {
	h4,
	.heading-4 {
		font-size: 24px;
		line-height: 1.33333;
	}
}

@media (min-width: 1200px) {
	h4.h4-smaller,
	.heading-4.h4-smaller {
		font-size: 22px;
		line-height: 1.45455;
	}
}

h5,
.heading-5 {
	font-size: 16px;
	line-height: 1.4;
	letter-spacing: .01em;
}

@media (min-width: 768px) {
	h5,
	.heading-5 {
		font-size: 20px;
		line-height: 1.4;
	}
}

h6,
.heading-6 {
	font-family: "Averia Libre";
	font-size: 14px;
	line-height: 1.8;
	letter-spacing: .2em;
	text-transform: uppercase;
	color: #aeb1be;
}

@media (min-width: 768px) {
	h6,
	.heading-6 {
		font-size: 16px;
		line-height: 1.5;
	}
}

.title-decorated {
	position: relative;
	padding-left: 40px;
	text-align: left;
}

.title-decorated::before {
	content: '';
	position: absolute;
	left: 0;
	top: .8em;
	width: 30px;
	border-bottom: 1px solid;
}

@media (min-width: 768px) {
	.title-decorated {
		padding-left: 70px;
	}
	.title-decorated::before {
		width: 50px;
		top: .7em;
		border-bottom-width: 2px;
	}
}

@media (min-width: 768px) {
	.title-decorated-lg {
		padding-left: 80px;
	}
	.title-decorated-lg::before {
		width: 62px;
	}
	.title-decorated-lg + p {
		margin-top: 32px;
	}
}

small,
.small {
	display: block;
	font-size: 12px;
	line-height: 1.5;
}

mark,
.mark {
	padding: 3px 5px;
	color: #fff;
	background: #ef172c;
}

strong {
	font-weight: 700;
	color: #15191f;
}

.big {
	font-size: 16px;
	line-height: 1.55;
}

@media (min-width: 768px) {
	.big {
		font-size: 20px;
		line-height: 1.6;
	}
}

.lead {
	font-size: 24px;
	line-height: 34px;
	font-weight: 300;
}

code {
	padding: 4px 5px;
	border-radius: 0;
	font-size: 90%;
	color: #111111;
	background: #f5f6fa;
}

.text-large {
	font-family: "Averia Libre";
	font-size: 30px;
	font-weight: 500;
	letter-spacing: 0;
	line-height: 1.2;
	text-transform: uppercase;
}

@media (min-width: 576px) {
	.text-large {
		font-size: 55px;
	}
}

@media (min-width: 768px) {
	.text-large {
		font-size: 68px;
	}
}

@media (min-width: 992px) {
	.text-large {
		font-size: 80px;
	}
}

@media (min-width: 1200px) {
	.text-large {
		font-size: 100px;
	}
}

.context-dark .text-large, .bg-gray-700 .text-large, .bg-gray-800 .text-large, .bg-primary .text-large, .bg-secondary .text-large, .bg-primary-darker .text-large {
	color: #fff;
}

.text-extra-large {
	font-size: 100px;
	line-height: .8;
	font-weight: 800;
}

@media (min-width: 768px) {
	.text-extra-large {
		font-size: 130px;
		line-height: .7;
	}
}

@media (min-width: 992px) {
	.text-extra-large {
		font-size: 150px;
	}
}

@media (min-width: 1600px) {
	.text-extra-large {
		font-size: 180px;
	}
}

.wow-outer span {
	display: block;
}

.wow-outer .wow > span {
	display: inline;
}

p [data-toggle='tooltip'] {
	padding-left: .25em;
	padding-right: .25em;
	color: #ef172c;
}

p [style*='max-width'] {
	display: inline-block;
}

p a {
	color: inherit;
}

p .text-width-1 {
	display: inline-block;
	max-width: 730px;
}

.text-width-2 {
	display: inline-block;
	max-width: 350px;
}

html .page .text-primary {
	color: #ef172c;
}

.page .text-danger {
	color: #dc0000;
}

.page .text-gray-700 {
	color: #29293a;
}

.page .text-color-1 {
	color: #d3d5db;
}

.context-dark .text-gray-700, .bg-gray-700 .text-gray-700, .bg-gray-800 .text-gray-700, .bg-primary .text-gray-700, .bg-secondary .text-gray-700, .bg-primary-darker .text-gray-700 {
	color: #fff;
}

/*
*
* Brand
*/
.brand {
	display: inline-block;
}

.brand .brand-logo-light {
	display: none;
}

.brand .brand-logo-dark {
	display: block;
}

/*
*
* Links
*/
a {
	transition: all 0.3s ease-in-out;
}

a, a:focus, a:active, a:hover {
	text-decoration: none;
}

a, a:focus, a:active {
	color: #ef172c;
}

a:hover {
	color: #790420;
}

a[href*='tel'], a[href*='mailto'] {
	white-space: normal;
}

[data-lightgallery="dynamic"] {
	cursor: pointer;
}

.link-hover {
	color: #37020e;
}

.link-default, .link-default:active, .link-default:focus {
	color: #15191f;
}

.link-default:hover {
	color: #ef172c;
}

.context-dark .link-default, .bg-gray-700 .link-default, .bg-gray-800 .link-default, .bg-primary .link-default, .bg-secondary .link-default, .bg-primary-darker .link-default {
	color: #aeb1be;
}

.context-dark .link-default:hover, .bg-gray-700 .link-default:hover, .bg-gray-800 .link-default:hover, .bg-primary .link-default:hover, .bg-secondary .link-default:hover, .bg-primary-darker .link-default:hover {
	color: #fff;
}

.link-image {
	display: block;
	max-width: 75%;
	margin-left: auto;
	margin-right: auto;
	opacity: .45;
	transition: all 0.3s ease-in-out;
}

.link-image:hover {
	opacity: 1;
}

.privacy-link {
	display: inline-block;
}

* + .privacy-link {
	margin-top: 25px;
}

/*
*
* Blocks
*/
.block-center, .block-sm, .block-lg {
	margin-left: auto;
	margin-right: auto;
}

.block-sm {
	max-width: 560px;
}

.block-lg {
	max-width: 768px;
}

.block-center {
	padding: 10px;
}

.block-center:hover .block-center-header {
	background-color: #ef172c;
}

.block-center-title {
	background-color: #fff;
}

@media (max-width: 1599.98px) {
	.block-center {
		padding: 20px;
	}
	.block-center:hover .block-center-header {
		background-color: #fff;
	}
	.block-center-header {
		background-color: #ef172c;
	}
}

/*
*
* Boxes
*/
.box-minimal {
	display: flex;
	margin-left: -15px;
	text-align: left;
}

.box-minimal > * {
	margin-left: 15px;
}

.box-minimal-icon {
	position: relative;
	top: 4px;
	font-size: 24px;
	line-height: 1;
	color: #ef172c;
}

.box-minimal-icon.fl-bigmug-line-checkmark14 {
	font-size: 20px;
}

.box-minimal-text {
	width: 100%;
	max-width: 320px;
	margin-left: auto;
	margin-right: auto;
}

* + .box-minimal {
	margin-top: 30px;
}

* + .box-minimal-title {
	margin-top: 10px;
}

* + .box-minimal-text {
	margin-top: 15px;
}

@media (max-width: 575.98px) {
	.box-minimal {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (max-width: 767.98px) {
	.box-minimal * + p {
		margin-top: 7px;
	}
}

@media (min-width: 768px) {
	.box-minimal {
		padding-right: 15px;
		margin-left: -30px;
	}
	.box-minimal > * {
		margin-left: 30px;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.box-minimal {
		padding-right: 0;
	}
	.box-minimal-title {
		font-size: 22px;
	}
}

@media (min-width: 1200px) {
	.box-minimal-icon {
		top: 0;
		font-size: 36px;
	}
	.box-minimal-icon.fl-bigmug-line-checkmark14 {
		font-size: 30px;
	}
}

.box-light {
	text-align: left;
}

.box-light-icon {
	font-size: 30px;
	line-height: 1;
	color: #ef172c;
}

* + .box-light-title {
	margin-top: 10px;
}

@media (max-width: 575.98px) {
	.box-light {
		max-width: 300px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 768px) {
	.box-light {
		max-width: 240px;
	}
	* + .box-light-title {
		margin-top: 16px;
	}
}

@media (min-width: 768px) and (max-width: 1199.98px) {
	.box-light-title {
		font-size: 20px;
	}
}

@media (min-width: 992px) {
	.box-light-icon {
		font-size: 32px;
	}
	* + .box-light-title {
		margin-top: 25px;
	}
}

@media (min-width: 1200px) {
	.box-light-icon {
		font-size: 40px;
	}
}

.box-creative {
	max-width: 330px;
	margin-left: auto;
	margin-right: auto;
	text-align: center;
	cursor: default;
}

.box-creative:hover .box-creative-icon {
	color: #fff;
}

.box-creative:hover .box-creative-icon::after {
	opacity: 1;
	visibility: visible;
	transform: translate3d(0, 0, 0);
}

.box-creative-shadow .box-creative-icon {
	background: #fff;
	border: 0;
	box-shadow: 0 17px 24px 0 rgba(0, 0, 0, 0.05);
}

.box-creative-icon {
	position: relative;
	z-index: 0;
	display: inline-flex;
	align-items: center;
	justify-content: center;
	width: 2.8em;
	height: 2.8em;
	border: 2px solid #e8e9ee;
	border-radius: 50%;
	font-size: 24px;
	line-height: 1;
	color: #ef172c;
}

.box-creative-icon::before {
	position: relative;
	z-index: 2;
}

.box-creative-icon::after {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: -1;
	border-radius: inherit;
	background: #ef172c;
	border-color: #ef172c;
	pointer-events: none;
	opacity: 0;
	visibility: hidden;
	transition: .15s ease-in;
	transform: scale3d(1.05, 1.05, 1.05);
}

* + .box-creative-icon {
	margin-top: 10px;
}

* + .box-creative-title {
	margin-top: 10px;
}

@media (min-width: 768px) {
	.box-creative-icon {
		font-size: 30px;
	}
	* + .box-creative-title {
		margin-top: 15px;
	}
}

@media (max-width: 991.98px) {
	.box-creative * + p {
		margin-top: 10px;
	}
}

@media (min-width: 1200px) {
	.box-creative-icon {
		width: 2.4em;
		height: 2.4em;
		font-size: 40px;
	}
	* + .box-creative-title {
		margin-top: 24px;
	}
}

.box-1 {
	max-width: 280px;
	margin-left: auto;
	margin-right: auto;
}

@media (min-width: 768px) {
	.box-2 {
		padding-right: 30px;
	}
}

@media (min-width: 992px) {
	.box-2 {
		padding-right: 35px;
	}
}

@media (min-width: 1200px) {
	.box-2 {
		padding-right: 100px;
	}
}

@media (min-width: 992px) {
	.box-3 {
		padding-left: 10px;
	}
}

@media (min-width: 1200px) {
	.box-3 {
		padding-left: 70px;
	}
}

div.box-cta-1 {
	display: inline-table;
	text-align: center;
	vertical-align: middle;
	margin-bottom: -25px;
	margin-left: -40px;
}

div.box-cta-1:empty {
	margin-bottom: 0;
	margin-left: 0;
}

div.box-cta-1 > * {
	display: inline-block;
	margin: 0 0 25px 40px;
}

div.box-cta-1 > * {
	margin-top: 0;
	vertical-align: middle;
}

div.box-cta-2 {
	display: inline-table;
	text-align: center;
	vertical-align: middle;
	margin-bottom: -25px;
	margin-left: -40px;
}

div.box-cta-2:empty {
	margin-bottom: 0;
	margin-left: 0;
}

div.box-cta-2 > * {
	display: inline-block;
	margin: 0 0 25px 40px;
}

div.box-cta-2 > * {
	margin-top: 0;
	vertical-align: middle;
}

@media (min-width: 1200px) {
	div.box-cta-2 {
		margin-bottom: -25px;
		margin-left: -60px;
	}
	div.box-cta-2:empty {
		margin-bottom: 0;
		margin-left: 0;
	}
	div.box-cta-2 > * {
		display: inline-block;
		margin: 0 0 25px 60px;
	}
}

div.box-cta-3 {
	display: inline-table;
	text-align: center;
	vertical-align: middle;
	margin-bottom: -25px;
	margin-left: -40px;
}

div.box-cta-3:empty {
	margin-bottom: 0;
	margin-left: 0;
}

div.box-cta-3 > * {
	display: inline-block;
	margin: 0 0 25px 40px;
}

div.box-cta-3 > * {
	margin-top: 0;
	vertical-align: middle;
}

@media (min-width: 1200px) {
	div.box-cta-3 {
		margin-bottom: -25px;
		margin-left: -50px;
	}
	div.box-cta-3:empty {
		margin-bottom: 0;
		margin-left: 0;
	}
	div.box-cta-3 > * {
		display: inline-block;
		margin: 0 0 25px 50px;
	}
}

div.box-cta-thin {
	display: inline-table;
	text-align: center;
	vertical-align: middle;
	margin-bottom: -25px;
	margin-left: -30px;
}

div.box-cta-thin:empty {
	margin-bottom: 0;
	margin-left: 0;
}

div.box-cta-thin > * {
	display: inline-block;
	margin: 0 0 25px 30px;
}

div.box-cta-thin > * {
	margin-top: 0;
	vertical-align: middle;
}

@media (min-width: 768px) and (max-width: 991.98px) {
	div.box-cta-thin > * {
		max-width: 500px;
	}
}

.box-indigo {
	position: relative;
	padding: 5px 0 22px;
	max-width: 500px;
}

.box-indigo::before {
	content: '';
	position: absolute;
	top: 0;
	right: 100px;
	bottom: 0;
	left: 30px;
	z-index: -1;
	background: rgba(41, 41, 58, 0.12);
	pointer-events: none;
}

.box-indigo p {
	line-height: 1.35;
}

.box-indigo-header > * {
	padding-left: 60px;
}

.box-indigo-header > * + * {
	margin-top: 0;
}

.box-indigo-mark {
	font-weight: 300;
	color: #d3d5db;
}

.box-indigo-title,
.box-indigo-subtitle {
	font-weight: 700;
	letter-spacing: 0;
	color: #29293a;
}

p.box-indigo-title {
	position: relative;
	font-size: 30px;
	line-height: 1.15;
}

p.box-indigo-title::before {
	content: '';
	position: absolute;
	top: 50%;
	left: 0;
	transform: translate3d(0, -50%, 0);
	display: inline-block;
	width: 37px;
	height: 0.05em;
	margin-right: 15px;
	vertical-align: middle;
	background: #ef172c;
}

@media (min-width: 576px) {
	p.box-indigo-title {
		font-size: 60px;
	}
}

@media (min-width: 768px) {
	p.box-indigo-title {
		font-size: 75px;
		line-height: 1.2;
	}
}

p.box-indigo-subtitle {
	font-size: 24px;
	line-height: 1.2;
}

p.box-indigo-subtitle .box-indigo-mark {
	font-size: 0.85em;
}

@media (min-width: 576px) {
	p.box-indigo-subtitle {
		font-size: 34px;
	}
}

@media (min-width: 768px) {
	p.box-indigo-subtitle {
		font-size: 40px;
	}
}

.context-dark .box-indigo::before, .bg-gray-700 .box-indigo::before, .bg-gray-800 .box-indigo::before, .bg-primary .box-indigo::before, .bg-secondary .box-indigo::before, .bg-primary-darker .box-indigo::before {
	background: rgba(255, 255, 255, 0.12);
}

.context-dark .box-indigo p, .bg-gray-700 .box-indigo p, .bg-gray-800 .box-indigo p, .bg-primary .box-indigo p, .bg-secondary .box-indigo p, .bg-primary-darker .box-indigo p {
	color: #aeb1be;
}

.context-dark p.box-indigo-title, .bg-gray-700 p.box-indigo-title, .bg-gray-800 p.box-indigo-title, .bg-primary p.box-indigo-title, .bg-secondary p.box-indigo-title, .bg-primary-darker p.box-indigo-title,
.context-dark p.box-indigo-subtitle,
.bg-gray-700 p.box-indigo-subtitle,
.bg-gray-800 p.box-indigo-subtitle,
.bg-primary p.box-indigo-subtitle,
.bg-secondary p.box-indigo-subtitle,
.bg-primary-darker p.box-indigo-subtitle {
	color: #fff;
}

.box-promo {
	position: relative;
	display: flex;
	max-width: 750px;
	margin-left: auto;
	margin-right: auto;
	text-align: left;
	box-shadow: 0 2px 24px 0 rgba(0, 0, 0, 0.15);
	transition: .33s ease-in-out;
}

.box-promo h6,
.box-promo .heading-6 {
	color: #ff747b;
}

.box-promo:hover {
	transform: translate(0, -5px);
	box-shadow: 0 2px 24px 1px rgba(0, 0, 0, 0.2);
}

.box-promo-mark {
	position: absolute;
	top: 14%;
	right: 6.5%;
	display: flex;
	align-items: center;
	justify-content: center;
	line-height: 1;
	border-radius: 50%;
	color: rgba(195, 7, 52, 0.1);
	border: 2px solid;
	pointer-events: none;
}

.box-promo-mark::before, .box-promo-mark::after {
	content: '';
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate3d(-50%, -50%, 0);
	background: rgba(195, 7, 52, 0.1);
}

.box-promo-mark::before {
	width: 2px;
	height: 50%;
}

.box-promo-mark::after {
	height: 2px;
	width: 50%;
}

.box-promo-inner,
.box-promo-dummy {
	width: 100%;
	flex-shrink: 0;
}

.box-promo-inner {
	display: flex;
	align-items: center;
	padding: 30px;
}

.box-promo-dummy {
	visibility: hidden;
	opacity: 0;
	pointer-events: none;
}

.box-promo-dummy::before {
	content: '';
	display: block;
	padding-bottom: 48.53333%;
}

.box-promo-content {
	width: 100%;
	max-width: 500px;
}

.box-promo-content * + h3,
.box-promo-content * + .heading-3 {
	margin-top: 15px;
}

.box-promo-content * + p {
	margin-top: 10px;
}

.box-promo-content * + .button {
	margin-top: 30px;
}

@media (min-width: 768px) {
	.box-promo-inner {
		padding: 39px 35px;
	}
}

@media (min-width: 1200px) {
	.box-promo-inner {
		padding: 60px 70px;
	}
	.box-promo-mark {
		top: 24%;
		right: 6.5%;
		width: 120px;
		height: 120px;
	}
}

/*
* Element groups
*/
html .group {
	margin-bottom: -15px;
	margin-left: -20px;
}

html .group:empty {
	margin-bottom: 0;
	margin-left: 0;
}

html .group > * {
	display: inline-block;
	margin: 0 0 15px 20px;
}

@media (min-width: 992px) {
	html .group {
		margin-left: -30px;
	}
	html .group > * {
		margin-left: 30px;
	}
}

html .group-xs {
	margin-bottom: -7px;
	margin-left: -7px;
}

html .group-xs:empty {
	margin-bottom: 0;
	margin-left: 0;
}

html .group-xs > * {
	display: inline-block;
	margin: 0 0 7px 7px;
}

html .group-sm {
	margin-bottom: -10px;
	margin-left: -10px;
}

html .group-sm:empty {
	margin-bottom: 0;
	margin-left: 0;
}

html .group-sm > * {
	display: inline-block;
	margin: 0 0 10px 10px;
}

html .group-lg {
	margin-bottom: -25px;
	margin-left: -40px;
}

html .group-lg:empty {
	margin-bottom: 0;
	margin-left: 0;
}

html .group-lg > * {
	display: inline-block;
	margin: 0 0 25px 40px;
}

html .group-xl {
	margin-bottom: -20px;
	margin-left: -30px;
}

html .group-xl:empty {
	margin-bottom: 0;
	margin-left: 0;
}

html .group-xl > * {
	display: inline-block;
	margin: 0 0 20px 30px;
}

@media (min-width: 992px) {
	html .group-xl {
		margin-bottom: -20px;
		margin-left: -45px;
	}
	html .group-xl > * {
		margin-bottom: 20px;
		margin-left: 45px;
	}
}

html .group-sm-justify .button {
	padding-left: 20px;
	padding-right: 20px;
}

@media (min-width: 768px) {
	html .group-sm-justify {
		display: flex;
		align-items: center;
		justify-content: center;
	}
	html .group-sm-justify > * {
		flex-grow: 1;
		flex-shrink: 0;
	}
	html .group-sm-justify .button {
		min-width: 130px;
		padding-left: 20px;
		padding-right: 20px;
	}
}

html .group-middle {
	display: table;
	vertical-align: middle;
}

html .group-middle > * {
	vertical-align: middle;
}

* + .group {
	margin-top: 30px;
}

* + .group-xs {
	margin-top: 35px;
}

* + .group-sm {
	margin-top: 30px;
}

* + .group-xl {
	margin-top: 20px;
}

/*
*
* Responsive units
*/
.unit {
	display: flex;
	flex: 0 1 100%;
	margin-bottom: -30px;
	margin-left: -20px;
}

.unit > * {
	margin-bottom: 30px;
	margin-left: 20px;
}

.unit:empty {
	margin-bottom: 0;
	margin-left: 0;
}

.unit-body {
	flex: 0 1 auto;
}

.unit-left,
.unit-right {
	flex: 0 0 auto;
	max-width: 100%;
}

.unit-spacing-xs {
	margin-bottom: -15px;
	margin-left: -7px;
}

.unit-spacing-xs > * {
	margin-bottom: 15px;
	margin-left: 7px;
}

/*
*
* Lists
*/
.list > li + li {
	margin-top: 10px;
}

.list-xs > li + li {
	margin-top: 8px;
}

.list-sm > li + li {
	margin-top: 15px;
}

.list-md > li + li {
	margin-top: 18px;
}

.list-lg > li + li {
	margin-top: 25px;
}

.list-xl li + li {
	margin-top: 30px;
}

@media (min-width: 1200px) {
	.list-xl * + p {
		margin-top: 18px;
	}
}

@media (min-width: 1600px) {
	.list-xl * + p {
		margin-top: 24px;
	}
}

@media (min-width: 768px) {
	.list-xl > li + li {
		margin-top: 60px;
	}
}

@media (min-width: 1600px) {
	.list-xl > li + li {
		margin-top: 78px;
	}
}

.list-inline > li {
	display: inline-block;
}

html .list-inline-sm {
	transform: translate3d(0, -8px, 0);
	margin-bottom: -8px;
	margin-left: -10px;
	margin-right: -10px;
}

html .list-inline-sm > * {
	margin-top: 8px;
	padding-left: 10px;
	padding-right: 10px;
}

html .list-inline-md {
	transform: translate3d(0, -8px, 0);
	margin-bottom: -8px;
	margin-left: -10px;
	margin-right: -10px;
}

html .list-inline-md > * {
	margin-top: 8px;
	padding-left: 10px;
	padding-right: 10px;
}

@media (min-width: 992px) {
	html .list-inline-md {
		margin-left: -14px;
		margin-right: -14px;
	}
	html .list-inline-md > * {
		padding-left: 14px;
		padding-right: 14px;
	}
}

.list-terms dt {
	font-size: 20px;
	line-height: 1.3;
	font-weight: 700;
	letter-spacing: 0;
	color: #29293a;
}

.list-terms dt + dd {
	margin-top: 8px;
}

.list-terms dd + dt {
	margin-top: 25px;
}

* + .list-terms {
	margin-top: 25px;
}

.list-terms + .privacy-link {
	margin-top: 20px;
}

@media (min-width: 768px) {
	.list-terms dt {
		font-size: 24px;
	}
	.list-terms dd + dt {
		margin-top: 40px;
	}
}

@media (min-width: 992px) {
	.list-terms dt + dd {
		margin-top: 18px;
	}
	.list-terms dd + dt {
		margin-top: 55px;
	}
}

@media (min-width: 1200px) {
	.list-terms dt {
		max-width: 85%;
	}
}

@media (min-width: 1600px) {
	.list-terms dd + dt {
		margin-top: 75px;
	}
	.list-terms + .privacy-link {
		margin-top: 75px;
	}
}

.index-list {
	counter-reset: li;
}

.index-list > li .list-index-counter:before {
	content: counter(li, decimal-leading-zero);
	counter-increment: li;
}

.list-marked {
	text-align: left;
}

.list-marked > li {
	text-indent: -25px;
	padding-left: 25px;
}

.list-marked > li::before {
	position: relative;
	top: 1px;
	display: inline-block;
	left: 25px;
	min-width: 25px;
	content: '\f14f';
	font: 400 14px 'Material Design Icons';
	line-height: inherit;
	color: #aeb1be;
}

.list-marked > li + li {
	margin-top: 9px;
}

* + .list-marked {
	margin-top: 15px;
}

.list-ordered {
	counter-reset: li;
	text-align: left;
}

.list-ordered > li {
	position: relative;
	padding-left: 25px;
}

.list-ordered > li:before {
	content: counter(li, decimal) ".";
	counter-increment: li;
	position: absolute;
	top: 0;
	left: 0;
	display: inline-block;
	width: 15px;
	color: #aeb1be;
}

.list-ordered > li + li {
	margin-top: 9px;
}

* + .list-ordered {
	margin-top: 15px;
}

.list-nav {
	transform: translate3d(0, -10px, 0);
	margin-bottom: -10px;
	margin-left: -10px;
	margin-right: -10px;
	font-family: "Averia Libre";
	font-weight: 400;
	font-size: .875em;
	letter-spacing: .08em;
	text-transform: uppercase;
	color: #29293a;
}

.list-nav > * {
	margin-top: 10px;
	padding-left: 10px;
	padding-right: 10px;
}

.list-nav li {
	display: inline-block;
	vertical-align: middle;
}

.list-nav a {
	color: inherit;
}

.list-nav a:hover {
	color: #ef172c;
}

@media (min-width: 768px) {
	.list-nav {
		margin-left: -13px;
		margin-right: -13px;
	}
	.list-nav > * {
		padding-left: 13px;
		padding-right: 13px;
	}
}

@media (min-width: 992px) {
	.list-nav {
		margin-left: -26px;
		margin-right: -26px;
	}
	.list-nav > * {
		padding-left: 10px;
		padding-right: 10px;
	}
}

.context-dark .list-nav, .bg-gray-700 .list-nav, .bg-gray-800 .list-nav, .bg-primary .list-nav, .bg-secondary .list-nav, .bg-primary-darker .list-nav {
	color: #fff;
}

.context-dark .list-nav a:hover, .bg-gray-700 .list-nav a:hover, .bg-gray-800 .list-nav a:hover, .bg-primary .list-nav a:hover, .bg-secondary .list-nav a:hover, .bg-primary-darker .list-nav a:hover {
	color: #aeb1be;
}

.list-inline-bordered {
	margin-left: -18px;
	margin-right: -18px;
	color: #29293a;
}

.list-inline-bordered > * {
	padding-left: 18px;
	padding-right: 18px;
}

.list-inline-bordered * {
	color: inherit;
}

.list-inline-bordered > li > button {
	background: none;
	border: none;
	display: inline-block;
	padding: 0;
	outline: none;
	outline-offset: 0;
	cursor: pointer;
	-webkit-appearance: none;
	transition: .22s;
}

.list-inline-bordered > li > button::-moz-focus-inner {
	border: none;
	padding: 0;
}

.list-inline-bordered > li {
	display: inline-block;
	line-height: 24px;
}

.list-inline-bordered > li:not(:last-child) {
	border-right: 1px solid #15191f;
}

.context-dark .list-inline-bordered, .bg-gray-700 .list-inline-bordered, .bg-gray-800 .list-inline-bordered, .bg-primary .list-inline-bordered, .bg-secondary .list-inline-bordered, .bg-primary-darker .list-inline-bordered {
	color: #fff;
}

.context-dark .list-inline-bordered button.active, .bg-gray-700 .list-inline-bordered button.active, .bg-gray-800 .list-inline-bordered button.active, .bg-primary .list-inline-bordered button.active, .bg-secondary .list-inline-bordered button.active, .bg-primary-darker .list-inline-bordered button.active,
.context-dark .list-inline-bordered button:hover,
.bg-gray-700 .list-inline-bordered button:hover,
.bg-gray-800 .list-inline-bordered button:hover,
.bg-primary .list-inline-bordered button:hover,
.bg-secondary .list-inline-bordered button:hover,
.bg-primary-darker .list-inline-bordered button:hover {
	color: #aeb1be;
}

.list-inline-comma > li {
	display: inline-block;
	color: #ef172c;
}

.list-inline-comma > li:not(:last-child)::after {
	content: '\002C';
}

.list-inline-comma a {
	color: inherit;
}

.list-inline-comma a:hover {
	color: #37020e;
}

.list-inline-comma-default > li {
	color: #15191f;
}

.list-inline-comma-default a:hover {
	color: #ef172c;
}

/*
*
* Images
*/
img {
	display: inline-block;
	/*max-width: 100%;*/
	height: auto;
}

.img-responsive {
	width: 100%;
}

/*
*
* Icons
*/
.icon {
	display: inline-block;
	font-size: 16px;
	line-height: 1;
}

.icon::before {
	position: relative;
	display: inline-block;
	font-weight: 400;
	font-style: normal;
	speak: none;
	text-transform: none;
}

.list-inline > [class*="icon"] {
	vertical-align: middle;
}

.icon-creative {
	display: inline-block;
	text-align: center;
	width: 2em;
	height: 2em;
	line-height: 2em;
	border-radius: 50%;
}

.icon-creative, .icon-creative:active, .icon-creative:focus {
	color: #aeb1be;
}

.icon-creative::after {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: -1;
	border-radius: inherit;
	pointer-events: none;
	opacity: 0;
	transform: scale3d(0, 0, 0);
	transition: .22s;
}

.icon-creative:hover {
	color: #fff;
}

.icon-creative:hover::after {
	opacity: 1;
	transform: scale3d(1, 1, 1);
	background: #ef172c;
}

.icon-creative[class*='facebook']::after {
	background: #2059a0;
}

.icon-creative[class*='twitter']::after {
	background: #00aae6;
}

.icon-creative[class*='instagram']::after {
	background: linear-gradient(to top, #f15823 0%, #a7058e 100%);
}

.icon-creative[class*='google']::after {
	background: #ff3807;
}

.icon-creative[class*='linkedin']::after {
	background: #2881a8;
}

.icon-modern {
	width: 2em;
	height: 2em;
	line-height: 2em;
	text-align: center;
	border-radius: 50%;
	border: 1px solid #e8e9ee;
	color: #6c6f74;
}

.icon-circle {
	border-radius: 50%;
}

.icon-sm {
	font-size: 20px;
}

.icon-md {
	font-size: 1.5em;
}

.icon-lg {
	font-size: 1.875em;
}

/*
*
* Tables custom
*/
.table {
	width: 100%;
	max-width: 100%;
	text-align: left;
	background: #fff;
	border-collapse: collapse;
}

.table th,
.table td {
	vertical-align: middle;
}

.table th {
	color: #29293a;
	padding: 13px 24px;
	border-top: 0;
	font-size: 16px;
	font-weight: 300;
}

.table thead th {
	border-bottom: 1px solid #aeb1be;
}

.table td {
	color: #15191f;
	padding: 23px 24px;
}

.table tbody tr:first-child td {
	border-top: 0;
}

.table tr td {
	border-bottom: 1px solid #e8e9ee;
}

.table tfoot td {
	font-weight: 700;
}

* + .table-responsive {
	margin-top: 30px;
}

@media (min-width: 768px) {
	* + .table-responsive {
		margin-top: 40px;
	}
}

.table-hover tbody tr {
	transition: .55s;
}

.table-hover tbody tr:hover {
	background: #f5f6fa;
}

.table-job-positions th,
.table-job-positions td {
	white-space: nowrap;
}

.table-job-positions td:first-child {
	width: 8%;
	padding-right: 6px;
	text-align: center;
}

.table-job-positions .position {
	color: #ef172c;
}

.table-job-positions time {
	display: block;
	white-space: nowrap;
}

@media (max-width: 575.98px) {
	.table-job-positions th,
	.table-job-positions td {
		padding-left: 12px;
		padding-right: 12px;
	}
	.table-job-positions td {
		padding-top: 10px;
		padding-bottom: 10px;
	}
}

.table-responsive + .button-lg {
	margin-top: 30px;
}

@media (min-width: 1200px) {
	.table-responsive + .button-lg {
		margin-top: 40px;
	}
}

@media (min-width: 1600px) {
	.table-responsive + .button-lg {
		margin-top: 55px;
	}
}

/*
*
* Dividers
*/
hr {
	margin-top: 0;
	margin-bottom: 0;
	border-top: 1px solid #e8e9ee;
}

.context-dark hr, .bg-gray-700 hr, .bg-gray-800 hr, .bg-primary hr, .bg-secondary hr, .bg-primary-darker hr {
	border-top-color: #15191f;
}

.divider-small {
	font-size: 0;
	line-height: 0;
}

.divider-small::after {
	content: '';
	display: inline-block;
	width: 70px;
	height: 2px;
	background-color: #ef172c;
}

.divider-small + h3, .divider-small + .heading-3,
.divider-small-outer + h3, .divider-small-outer + .heading-3 {
	margin-top: 20px;
}

/*
*
* Buttons
*/
.button {
	position: relative;
	overflow: hidden;
	display: inline-block;
	padding: 14px 35px;
	font-size: 14px;
	line-height: 1.25;
	border: 1px solid;
	border-radius: 4px;
	font-family: "Averia Libre";
	font-weight: 500;
	letter-spacing: 0.2em;
	text-transform: uppercase;
	white-space: nowrap;
	text-overflow: ellipsis;
	text-align: center;
	cursor: pointer;
	vertical-align: middle;
	user-select: none;
	transition: 0.25s cubic-bezier(0.2, 1, 0.3, 1);
}

.button-block {
	display: block;
	width: 100%;
}

.button-default {
	color: #aeb1be;
	background-color: #29293a;
	border-color: #29293a;
}

.button-default:hover {
	color: #fff;
	background-color: #ef172c;
	border-color: #ef172c;
}

.button.button-primary {
	color: #fff;
	background-color: #353535;
	border-color: #353535;
}

.button.button-primary:hover {
	color: #ef172c;
	background-color: #e1e0dd;
	border-color: #e1e0dd;
}

.button.button-white {
	color: #29293a;
	background-color: #fff;
	border-color: #fff;
}

.button.button-white:hover {
	color: #fff;
	background-color: transparent;
	border-color: #fff;
}

html .button.button-primary-lighten {
	color: #fff;
	background-color: #ef172c;
	border-color: #ef172c;
}

html .button.button-primary-lighten:hover {
	color: #fff;
	background-color: #353535;
	border-color: #353535;
}

.button-primary-outline {
	color: #29293a;
	background-color: transparent;
	border-color: #ef172c;
}

.button-primary-outline:hover {
	color: #fff;
	background-color: #ef172c;
	border-color: #ef172c;
}

.button.button-facebook {
	color: #fff;
	background-color: #2059a0;
	border-color: #2059a0;
}

.button.button-facebook:hover {
	color: #fff;
	background-color: #2465b5;
	border-color: #2465b5;
}

.button.button-twitter {
	color: #fff;
	background-color: #00aae6;
	border-color: #00aae6;
}

.button.button-twitter:hover {
	color: #fff;
	background-color: #01bdff;
	border-color: #01bdff;
}

.button.button-google {
	color: #fff;
	background-color: #ff3807;
	border-color: #ff3807;
}

.button.button-google:hover {
	color: #fff;
	background-color: #ff4c21;
	border-color: #ff4c21;
}

.button-winona {
	position: relative;
	overflow: hidden;
	display: inline-block;
	vertical-align: middle;
	text-align: center;
}

.button-winona .content-original,
.button-winona .content-dubbed {
	vertical-align: middle;
	transition: transform 0.3s cubic-bezier(0.2, 1, 0.3, 1), opacity 0.3s cubic-bezier(0.2, 1, 0.3, 1);
}

.button-winona .content-original {
	display: block;
}

.button-winona .content-dubbed {
	position: absolute;
	width: 100%;
	top: 50%;
	left: 0;
	opacity: 0;
	transform: translate3d(0, 0, 0);
}

.button-winona:hover .content-original {
	opacity: 0;
	transform: translate3d(0, -30%, 0);
}

.button-winona:hover .content-dubbed {
	opacity: 1;
	transform: translate3d(0, 0, 0) translateY(-50%);
}

.button-sm {
	padding: 9px 32px;
	font-size: 12px;
	line-height: 1.5;
}

.button-lg {
	padding: 14px 35px;
	font-size: 15px;
	line-height: 1.5;
}

@media (min-width: 576px) {
	.button-lg {
		font-size: 16px;
		padding-left: 55px;
		padding-right: 55px;
	}
}

.button-lg--smaller {
	padding-left: 35px;
	padding-right: 35px;
}

html .button.button-icon {
	display: inline-flex;
}

.button-icon {
	justify-content: center;
	align-items: center;
	vertical-align: middle;
}

.button-icon .icon {
	position: relative;
	top: -1px;
	display: inline-block;
	vertical-align: middle;
	color: inherit;
	font-size: 1.55em;
	line-height: 1em;
	transition: none;
}

.button-icon:hover .icon {
	color: inherit;
}

.button-icon-left .icon {
	padding-right: 5px;
}

.button-icon-right {
	flex-direction: row-reverse;
}

.button-icon-right .icon {
	padding-left: 8px;
}

.button-icon.button-icon-only {
	padding-left: 20px;
	padding-right: 20px;
}

.button-icon.button-lg .icon {
	padding-right: 8px;
}

.button-icon.button-lg.button-icon-right .icon {
	padding: 0 0 0 8px;
}

.button-icon.button-sm .icon {
	padding-right: 3px;
	font-size: 1.33em;
}

.button-icon.button-sm.button-icon-right .icon {
	padding: 0 0 0 3px;
}

.btn-primary {
	border-radius: 3px;
	font-family: "Averia Libre";
	font-weight: 500;
	letter-spacing: .05em;
	text-transform: uppercase;
	transition: .33s;
}

.btn-primary, .btn-primary:active, .btn-primary:focus {
	color: #fff;
	background: #ef172c;
	border-color: #ef172c;
}

.btn-primary:hover {
	color: #fff;
	background: #000;
	border-color: #000;
}

.button-group {
	display: flex;
}

.button-group .button {
	margin: 0;
	flex-grow: 1;
}

.button-group .button:not(:first-child) {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.button-group .button:not(:last-child) {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.button-video,
.icon-video {
	position: relative;
	display: block;
	border-radius: 50%;
	transition: .33s;
	color: #29293a;
}

.button-video::before, .button-video:after,
.icon-video::before,
.icon-video:after {
	display: block;
	content: '\f4fc';
	font-family: 'Material Design Icons';
	font-size: 64px;
	line-height: 1;
	border-radius: 50%;
}

.button-video::before,
.icon-video::before {
	z-index: -1;
	pointer-events: none;
}

.button-video::after,
.icon-video::after {
	position: absolute;
	width: 100%;
	top: 50%;
	left: 0;
	opacity: 0;
	transform: translate3d(0, -50%, 0);
	transition: opacity 0.3s cubic-bezier(0.2, 1, 0.3, 1);
}

.button-video:hover,
.icon-video:hover {
	color: #ef172c;
}

.button-video:hover::before,
.icon-video:hover::before {
	opacity: 0;
	transition: transform 0.9s cubic-bezier(0.2, 1, 0.3, 1), opacity 0.3s cubic-bezier(0.2, 1, 0.3, 1);
	transform: scale3d(1.5, 1.5, 1.5);
}

.button-video:hover::after,
.icon-video:hover::after {
	opacity: 1;
}

.button-video-lg::before, .button-video-lg:after {
	font-size: 90px;
}

.context-dark .button-video, .bg-gray-700 .button-video, .bg-gray-800 .button-video, .bg-primary .button-video, .bg-secondary .button-video, .bg-primary-darker .button-video,
.context-dark .icon-video,
.bg-gray-700 .icon-video,
.bg-gray-800 .icon-video,
.bg-primary .icon-video,
.bg-secondary .icon-video,
.bg-primary-darker .icon-video {
	color: #fff;
}

.builder-button {
	position: fixed;
	top: 50%;
	right: 0;
	z-index: 1080;
	display: none;
	align-items: center;
	justify-content: center;
	padding: 10px 10px;
	text-transform: uppercase;
	font-weight: 700;
	transform-origin: 100% 100%;
	transform: rotate(-90deg) translateX(50%);
	border-top-left-radius: 10px;
	border-top-right-radius: 10px;
	background-image: linear-gradient(to bottom, #00F3F7 0%, #109DF7 51%, #00F3F7 100%);
	background-size: auto 200%;
	color: #fff;
}

.builder-button > * + * {
	margin-left: 10px;
}

.builder-button img {
	max-width: 30px;
	height: auto;
	transform: rotate(90deg);
}

.builder-button:hover, .builder-button:focus {
	color: #fff;
}

[data-x-mode="true"] .builder-button {
	display: none;
}

@media (min-width: 768px) {
	.builder-button {
		display: inline-flex;
	}
}

/*
*
* Form styles
*/
.rd-form {
	position: relative;
	text-align: left;
}

.rd-form .button {
	min-height: 48px;
}

.rd-form .button-icon-only {
	padding-top: 11px;
	padding-bottom: 11px;
}

* + .rd-form {
	margin-top: 20px;
}

input:-webkit-autofill ~ label,
input:-webkit-autofill ~ .form-validation {
	color: #000 !important;
}

.form-wrap {
	position: relative;
}

.form-wrap.has-error .form-input {
	border-color: #dc0000;
}

.form-wrap.has-focus .form-input {
	border-color: #ef172c;
}

* + .form-wrap {
	margin-top: 24px;
}

.form-input {
	display: block;
	width: 100%;
	min-height: 48px;
	padding: 11px 19px;
	font-size: 16px;
	font-weight: 400;
	line-height: 1.4875;
	color: #29293a;
	background-color: #fff;
	background-image: none;
	border-radius: 4px;
	-webkit-appearance: none;
	transition: .3s ease-in-out;
	border: 1px solid #c5c6cd;
}

.form-input:focus {
	outline: 0;
}

.bg-default .form-input {
	background: rgba(41, 41, 58, 0.1);
}

textarea.form-input {
	height: 150px;
	min-height: 48px;
	max-height: 255px;
	resize: vertical;
}

.form-label,
.form-label-outside {
	margin-bottom: 0;
	font-weight: 400;
}

.form-label {
	position: absolute;
	top: 24px;
	left: 0;
	right: 0;
	padding-left: 19px;
	padding-right: 19px;
	font-size: 16px;
	font-weight: 400;
	line-height: 1.4875;
	color: #29293a;
	pointer-events: none;
	text-align: left;
	z-index: 9;
	transition: .25s;
	will-change: transform;
	transform: translateY(-50%);
}

.form-label.focus {
	opacity: 0;
}

.form-label.auto-fill {
	color: #29293a;
}

.form-label-outside {
	width: 100%;
	padding-right: 150px;
	margin-bottom: 4px;
	font-size: 14px;
	color: #15191f;
	cursor: pointer;
}

.parallax-container .form-label-outside {
	color: #29293a;
}

.form-label-outside ~ .form-validation {
	top: 10px;
}

[data-x-mode='true'] .form-label {
	pointer-events: auto;
}

.form-validation {
	position: absolute;
	right: 15px;
	top: 0;
	z-index: 11;
	margin-top: 17px;
	margin-left: 5px;
	font-size: 10px;
	font-weight: 400;
	line-height: 12px;
	letter-spacing: 0;
	color: #dc0000;
	transition: .3s;
	transform: scale3d(1, 1, 1);
}

.form-validation:empty {
	transform: scale3d(1, 0, 1);
}

.context-dark .form-wrap-outside-label .form-validation, .bg-gray-700 .form-wrap-outside-label .form-validation, .bg-gray-800 .form-wrap-outside-label .form-validation, .bg-primary .form-wrap-outside-label .form-validation, .bg-secondary .form-wrap-outside-label .form-validation, .bg-primary-darker .form-wrap-outside-label .form-validation {
	color: #fff;
}

.form-validation-left .form-validation {
	top: 2px;
	bottom: auto;
	right: auto;
	left: 14px;
}

#form-output-global {
	position: fixed;
	bottom: 30px;
	left: 15px;
	z-index: 2000;
	visibility: hidden;
	transform: translate3d(-500px, 0, 0);
	transition: .3s all ease;
}

#form-output-global.active {
	visibility: visible;
	transform: translate3d(0, 0, 0);
}

@media (min-width: 576px) {
	#form-output-global {
		left: 30px;
	}
}

.form-output {
	position: absolute;
	top: 100%;
	left: 0;
	font-size: 10px;
	font-weight: 400;
	line-height: 1.2;
	margin-top: 2px;
	transition: .3s;
	opacity: 0;
	visibility: hidden;
}

.form-output.active {
	opacity: 1;
	visibility: visible;
}

.form-output.error {
	color: #dc0000;
}

.form-output.success {
	color: #98bf44;
}

.radio .radio-custom,
.radio-inline .radio-custom,
.checkbox .checkbox-custom,
.checkbox-inline .checkbox-custom {
	opacity: 0;
}

.radio .radio-custom, .radio .radio-custom-dummy,
.radio-inline .radio-custom,
.radio-inline .radio-custom-dummy,
.checkbox .checkbox-custom,
.checkbox .checkbox-custom-dummy,
.checkbox-inline .checkbox-custom,
.checkbox-inline .checkbox-custom-dummy {
	position: absolute;
	left: 0;
	width: 14px;
	height: 14px;
	outline: none;
	cursor: pointer;
}

.radio .radio-custom-dummy,
.radio-inline .radio-custom-dummy,
.checkbox .checkbox-custom-dummy,
.checkbox-inline .checkbox-custom-dummy {
	pointer-events: none;
	background: #fff;
}

.radio .radio-custom-dummy::after,
.radio-inline .radio-custom-dummy::after,
.checkbox .checkbox-custom-dummy::after,
.checkbox-inline .checkbox-custom-dummy::after {
	position: absolute;
	opacity: 0;
	transition: .22s;
}

.radio .radio-custom:focus,
.radio-inline .radio-custom:focus,
.checkbox .checkbox-custom:focus,
.checkbox-inline .checkbox-custom:focus {
	outline: none;
}

.radio input,
.radio-inline input,
.checkbox input,
.checkbox-inline input {
	position: absolute;
	width: 1px;
	height: 1px;
	padding: 0;
	overflow: hidden;
	clip: rect(0, 0, 0, 0);
	white-space: nowrap;
	clip-path: inset(50%);
	border: 0;
}

.radio-custom:checked + .radio-custom-dummy:after,
.checkbox-custom:checked + .checkbox-custom-dummy:after {
	opacity: 1;
}

.radio,
.radio-inline {
	padding-left: 28px;
}

.radio .radio-custom-dummy,
.radio-inline .radio-custom-dummy {
	top: 1px;
	left: 0;
	width: 18px;
	height: 18px;
	border-radius: 50%;
	border: 1px solid #15191f;
}

.radio .radio-custom-dummy::after,
.radio-inline .radio-custom-dummy::after {
	content: '';
	top: 3px;
	right: 3px;
	bottom: 3px;
	left: 3px;
	background: #29293a;
	border-radius: inherit;
}

.checkbox,
.checkbox-inline {
	padding-left: 28px;
}

.checkbox .checkbox-custom-dummy,
.checkbox-inline .checkbox-custom-dummy {
	left: 0;
	width: 18px;
	height: 18px;
	margin: 0;
	border: 1px solid #15191f;
}

.checkbox .checkbox-custom-dummy::after,
.checkbox-inline .checkbox-custom-dummy::after {
	content: '\f222';
	font-family: "Material Design Icons";
	position: absolute;
	top: -1px;
	left: -2px;
	font-size: 20px;
	line-height: 18px;
	color: #aeb1be;
}

.toggle-custom {
	padding-left: 60px;
	-webkit-appearance: none;
}

.toggle-custom:checked ~ .checkbox-custom-dummy::after {
	background: #ef172c;
	transform: translate(20px, -50%);
}

.toggle-custom ~ .checkbox-custom-dummy {
	position: relative;
	display: inline-block;
	margin-top: -1px;
	width: 44px;
	height: 20px;
	background: #fff;
	cursor: pointer;
}

.toggle-custom ~ .checkbox-custom-dummy::after {
	content: '';
	position: absolute;
	display: inline-block;
	width: 16px;
	height: 16px;
	left: 0;
	top: 50%;
	background: #15191f;
	transform: translate(4px, -50%);
	opacity: 1;
	transition: .22s;
}

.form-inline {
	display: flex;
	flex-wrap: wrap;
	align-items: stretch;
	text-align: center;
	margin-bottom: -8px;
	margin-left: 6px;
}

.form-inline > * {
	margin-bottom: 8px;
}

.form-inline > * {
	margin-top: 0;
	margin-left: -6px;
}

.form-inline .form-wrap {
	min-width: 220px;
	flex: 20 0;
}

.form-inline .form-wrap-select {
	text-align: left;
}

.form-inline .form-label {
	display: block;
}

.form-inline .form-input {
	border-color: #fff;
}

.form-inline .form-button {
	flex-grow: 1;
	min-height: 48px;
}

.form-inline .form-button .button {
	width: 100%;
	min-height: inherit;
}

@media (min-width: 576px) {
	.form-inline .button {
		display: block;
	}
}

.form-inline.form-inline-centered {
	justify-content: center;
}

.form-sm .form-input,
.form-sm .button {
	padding-top: 9px;
	padding-bottom: 9px;
	min-height: 40px;
}

.form-sm .form-validation {
	top: -16px;
}

.form-sm .form-label {
	top: 20px;
}

.form-sm * + .button {
	margin-top: 10px;
}

.form-lg .form-input,
.form-lg .select2-container--default .select2-selection--single .select2-selection__rendered {
	padding-top: 15px;
	padding-bottom: 15px;
}

.form-lg .form-input,
.form-lg .select2-container--default .select2-selection--single .select2-selection__rendered,
.form-lg .form-wrap-button {
	min-height: 56px;
}

.form-lg .form-label {
	top: 28px;
}

.form-layout-1 {
	margin-bottom: -20px;
	margin-left: -20px;
}

.form-layout-1:empty {
	margin-bottom: 0;
	margin-left: 0;
}

.form-layout-1 > * {
	display: inline-block;
	margin: 0 0 20px 20px;
}

.form-layout-1 > * {
	display: block;
}

.form-layout-1 .select-2-container {
	display: block;
	min-width: 100%;
	max-width: 100%;
	width: auto !important;
}

.form-layout-1 .form-wrap-button {
	display: flex;
}

.form-layout-1 .button {
	display: block;
	width: 100%;
}

* + form.form-layout-1 {
	margin-top: 35px;
}

@media (min-width: 768px) {
	.form-layout-1 {
		display: flex;
	}
	.form-layout-1 > * {
		flex-shrink: 0;
	}
	.form-layout-1 .form-wrap-main {
		flex-grow: 1;
	}
	.form-layout-1 .form-wrap-select {
		width: 100%;
		max-width: 220px;
	}
}

@media (min-width: 992px) {
	* + form.form-layout-1 {
		margin-top: 50px;
	}
}

/*
*
* Posts
*/
.post-inline {
	max-width: 313px;
}

.post-inline-title a {
	color: inherit;
}

.post-inline-meta {
	transform: translate3d(0, -5px, 0);
	margin-bottom: -5px;
	margin-left: -10px;
	margin-right: -10px;
	color: #15191f;
}

.post-inline-meta > * {
	margin-top: 5px;
	padding-left: 10px;
	padding-right: 10px;
}

.post-inline-meta > li {
	position: relative;
	display: inline-block;
}

.post-inline-meta > li:not(:last-child)::after {
	content: '';
	position: absolute;
	right: 0;
	top: 50%;
	width: 1px;
	height: 1px;
	border-radius: 50%;
	background: #29293a;
}

.post-inline-meta a {
	color: inherit;
}

* + .post-inline {
	margin-top: 15px;
}

* + .post-inline-meta {
	margin-top: 5px;
}

@media (min-width: 768px) {
	* + .post-inline {
		margin-top: 32px;
	}
}

.context-dark .post-inline-title, .bg-gray-700 .post-inline-title, .bg-gray-800 .post-inline-title, .bg-primary .post-inline-title, .bg-secondary .post-inline-title, .bg-primary-darker .post-inline-title {
	color: #fff;
}

.context-dark .post-inline-title a:hover, .bg-gray-700 .post-inline-title a:hover, .bg-gray-800 .post-inline-title a:hover, .bg-primary .post-inline-title a:hover, .bg-secondary .post-inline-title a:hover, .bg-primary-darker .post-inline-title a:hover {
	color: #aeb1be;
}

.context-dark .post-inline-meta > li:not(:last-child)::after, .bg-gray-700 .post-inline-meta > li:not(:last-child)::after, .bg-gray-800 .post-inline-meta > li:not(:last-child)::after, .bg-primary .post-inline-meta > li:not(:last-child)::after, .bg-secondary .post-inline-meta > li:not(:last-child)::after, .bg-primary-darker .post-inline-meta > li:not(:last-child)::after {
	background: #aeb1be;
}

.context-dark .post-inline-meta a:hover, .bg-gray-700 .post-inline-meta a:hover, .bg-gray-800 .post-inline-meta a:hover, .bg-primary .post-inline-meta a:hover, .bg-secondary .post-inline-meta a:hover, .bg-primary-darker .post-inline-meta a:hover {
	color: #fff;
}

.post-classic {
	text-align: left;
}

.post-classic-media {
	position: relative;
	display: block;
}

.post-classic-media::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(41, 41, 58, 0.1);
	transition: .4s ease-in-out;
	opacity: 0;
	visibility: hidden;
	pointer-events: none;
}

.post-classic-media img {
	width: 100%;
}

.post-classic-media:hover::before {
	opacity: 1;
	visibility: visible;
}

.post-classic-meta {
	transform: translate3d(0, -3px, 0);
	margin-bottom: -3px;
	margin-left: -14px;
	margin-right: -14px;
	color: #aeb1be;
}

.post-classic-meta > * {
	margin-top: 3px;
	padding-left: 14px;
	padding-right: 14px;
}

.post-classic-meta > li {
	position: relative;
	display: inline-block;
}

.post-classic-meta > li:not(:last-child)::after {
	content: '';
	position: absolute;
	right: 0;
	top: 50%;
	width: 2px;
	height: 2px;
	background: #aeb1be;
	transform: translate3d(0, -50%, 0);
}

.post-classic-meta a:hover {
	color: #37020e;
}

* + .post-classic-meta {
	margin-top: 10px;
}

* + .post-classic-title {
	margin-top: 3px;
}

@media (max-width: 575.98px) {
	.post-classic {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 576px) and (max-width: 767.98px) {
	.post-classic-title {
		font-size: 17px;
	}
}

@media (min-width: 992px) {
	.post-classic-meta {
		transform: translate3d(0, -5px, 0);
		margin-bottom: -5px;
		margin-left: -20px;
		margin-right: -20px;
	}
	.post-classic-meta > * {
		margin-top: 5px;
		padding-left: 20px;
		padding-right: 20px;
	}
	* + .post-classic-meta {
		margin-top: 25px;
	}
	* + .post-classic-title {
		margin-top: 9px;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.post-classic-meta {
		margin-left: -15px;
		margin-right: -15px;
		font-size: 14px;
	}
	.post-classic-meta > * {
		padding-left: 15px;
		padding-right: 15px;
	}
}

.post-modern {
	text-align: left;
}

.post-modern-title {
	color: #ef172c;
}

.post-modern-title a:hover {
	color: #ef172c;
}

.post-modern-media {
	position: relative;
	display: block;
}

.post-modern-media::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(41, 41, 58, 0.1);
	transition: .22s ease-in-out;
	opacity: 0;
	visibility: hidden;
	pointer-events: none;
}

.post-modern-media img {
	width: 100%;
}

.post-modern-media:hover::before {
	opacity: 1;
	visibility: visible;
}

.post-modern-meta {
	transform: translate3d(0, -5px, 0);
	margin-bottom: -5px;
	margin-left: -15px;
	margin-right: -15px;
	color: #29293a;
}

.post-modern-meta > * {
	margin-top: 5px;
	padding-left: 15px;
	padding-right: 15px;
}

.post-modern-meta > li {
	position: relative;
	display: inline-block;
	line-height: 1.55;
}

.post-modern-meta > li:not(:last-child)::after {
	content: '';
	position: absolute;
	right: 0;
	top: 50%;
	width: 1px;
	height: 1.5em;
	background: #e8e9ee;
	transform: translate3d(0, -50%, 0);
}

.post-modern-meta a {
	color: #29293a;
}

.post-modern-meta a:hover {
	color: #ef172c;
}

* + .post-modern-title {
	margin-top: 9px;
}

* + .post-modern-meta {
	margin-top: 10px;
}

* + .post-modern-description {
	margin-top: 10px;
}

@media (max-width: 575.98px) {
	.post-modern {
		max-width: 430px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 768px) {
	.post-modern-meta {
		transform: translate3d(0, -5px, 0);
		margin-bottom: -5px;
		margin-left: -20px;
		margin-right: -20px;
	}
	.post-modern-meta > * {
		margin-top: 5px;
		padding-left: 20px;
		padding-right: 20px;
	}
	* + .post-modern-title {
		margin-top: 15px;
	}
	* + .post-modern-description {
		margin-top: 16px;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.post-modern-meta {
		margin-left: -15px;
		margin-right: -15px;
		font-size: 14px;
	}
	.post-modern-meta > * {
		padding-left: 15px;
		padding-right: 15px;
	}
}

@media (min-width: 1200px) {
	.post-modern p,
	.post-modern .post-modern-title {
		padding-right: 40px;
	}
	* + .post-modern-title {
		margin-top: 25px;
	}
	* + .post-modern-meta {
		margin-top: 15px;
	}
}

.post-block {
	position: relative;
	z-index: 1;
	display: flex;
	overflow: hidden;
	max-width: 640px;
	border-radius: 0px;
	text-align: left;
}

.post-block::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1;
	opacity: .73;
	background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.6) 100%);
	pointer-events: none;
}

.post-block::after {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	pointer-events: none;
	border-radius: inherit;
	background: rgba(0, 0, 0, 0.5);
	z-index: 1;
	opacity: 0;
	visibility: hidden;
	transition: 1s ease-in-out;
}

.post-block:hover::after {
	opacity: 1;
	visibility: visible;
}

.post-block > * {
	width: 100%;
	flex-shrink: 0;
}

.post-block-dummy {
	width: 100%;
}

.post-block-dummy::before {
	content: '';
	display: block;
	visibility: hidden;
	pointer-events: none;
	padding-bottom: 71.58556%;
}

.post-block-image {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.post-block-image {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.post-block-caption {
	position: relative;
	z-index: 2;
	display: flex;
	flex-direction: column;
	justify-content: flex-end;
	padding: 20px;
}

[data-x-mode="true"] .post-block-caption {
	pointer-events: none;
}

[data-x-mode="true"] .post-block-caption > * {
	pointer-events: auto;
}

.post-block-meta {
	transform: translate3d(0, -5px, 0);
	margin-bottom: -5px;
	margin-left: -20px;
	margin-right: -20px;
	color: #29293a;
}

.post-block-meta > * {
	margin-top: 5px;
	padding-left: 20px;
	padding-right: 20px;
}

.post-block-meta > li {
	position: relative;
	display: inline-block;
	line-height: 24px;
}

.post-block-meta > li:not(:last-child)::after {
	content: '';
	position: absolute;
	right: 0;
	top: 50%;
	width: 1px;
	height: 1.5em;
	background: #e8e9ee;
	transform: translate3d(0, -50%, 0);
}

.post-block-meta a {
	color: inherit;
}

.post-block-meta a:hover {
	color: #ef172c;
}

.post-block-meta time {
	display: block;
}

.context-dark .post-block-meta, .bg-gray-700 .post-block-meta, .bg-gray-800 .post-block-meta, .bg-primary .post-block-meta, .bg-secondary .post-block-meta, .bg-primary-darker .post-block-meta {
	color: #fff;
}

.context-dark .post-block-meta a:hover, .bg-gray-700 .post-block-meta a:hover, .bg-gray-800 .post-block-meta a:hover, .bg-primary .post-block-meta a:hover, .bg-secondary .post-block-meta a:hover, .bg-primary-darker .post-block-meta a:hover {
	color: #fff;
}

.context-dark .post-block-meta > li:not(:last-child)::after, .bg-gray-700 .post-block-meta > li:not(:last-child)::after, .bg-gray-800 .post-block-meta > li:not(:last-child)::after, .bg-primary .post-block-meta > li:not(:last-child)::after, .bg-secondary .post-block-meta > li:not(:last-child)::after, .bg-primary-darker .post-block-meta > li:not(:last-child)::after {
	background: #aeb1be;
}

.context-dark .post-block-title a:hover, .bg-gray-700 .post-block-title a:hover, .bg-gray-800 .post-block-title a:hover, .bg-primary .post-block-title a:hover, .bg-secondary .post-block-title a:hover, .bg-primary-darker .post-block-title a:hover {
	color: #aeb1be;
}

@media (max-width: 767.98px) {
	.post-block {
		max-width: 420px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 768px) {
	.post-block-meta {
		margin-left: -25px;
		margin-right: -25px;
	}
	.post-block-meta > * {
		padding-left: 25px;
		padding-right: 25px;
	}
	.post-block-caption {
		padding: 35px 40px;
	}
}

.post-light {
	display: flex;
	align-items: flex-start;
	/* max-width: 450px; */
	margin-left: -20px;
	text-align: left;
}

.post-light > * {
	margin-left: 20px;
}

.post-light:hover .post-light-time {
	background: #ef172c;
}

.post-light-time {
	position: relative;
	overflow: hidden;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	flex-shrink: 0;
	min-width: 100px;
	width: 100px;
	padding: 20px;
	color: #fff;
	background: #aeb1be;
	border-radius: 0px;
	transition: .22s ease-in-out;
}

.post-light-time > * {
	line-height: 1;
}

.post-light-time > * + * {
	margin-top: 3px;
}

.post-light-time-big {
	font-size: 2.25em;
	font-weight: 700;
}

a.post-tiny-media {
	display: block;
}

.post-light-media {
	position: relative;
}

.post-light-media::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(41, 41, 58, 0.1);
	transition: .22s ease-in-out;
	opacity: 0;
	visibility: hidden;
	pointer-events: none;
}

.post-light-media img {
	width: 100%;
}

.post-light-main {
	flex-grow: 1;
}

.post-light-title {
	color: #ef172c;
}

.post-light-title a:hover {
	color: #37020e;
}

.post-light-meta {
	transform: translate3d(0, -5px, 0);
	margin-bottom: -5px;
	margin-left: -20px;
	margin-right: -20px;
	color: #29293a;
}

.post-light-meta > * {
	margin-top: 5px;
	padding-left: 20px;
	padding-right: 20px;
}

.post-light-meta > li {
	position: relative;
	display: inline-block;
	line-height: 24px;
}

.post-light-meta > li:not(:last-child)::after {
	content: '';
	position: absolute;
	right: 0;
	top: 50%;
	width: 1px;
	height: 1.5em;
	background: #e8e9ee;
	transform: translate3d(0, -50%, 0);
}

.post-light-meta a {
	color: inherit;
}

.post-light-meta a:hover {
	color: #ef172c;
}

* + .post-light {
	margin-top: 30px;
}

* + .post-light-meta {
	margin-top: 9px;
}

@media (min-width: 768px) {
	.post-light {
		margin-left: -36px;
	}
	.post-light > * {
		margin-left: 36px;
	}
}

@media (min-width: 992px) {
	* + .post-light {
		margin-top: 38px;
	}
}

[data-x-mode="true"] .post-light {
	margin-left: 0;
}

[data-x-mode="true"] .post-light > *:first-child {
	margin-left: 0;
}

.post-tiny {
	text-align: left;
}

a.post-tiny-media {
	position: relative;
	display: block;
}

a.post-tiny-media::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(21, 25, 31, 0.3);
	transition: .22s ease-in-out;
	opacity: 0;
	visibility: hidden;
	pointer-events: none;
}

a.post-tiny-media img {
	width: 100%;
}

a.post-tiny-media:hover::before {
	opacity: 1;
	visibility: visible;
}

.post-tiny-title {
	color: #ef172c;
}

.post-tiny-title a:hover {
	color: #ef172c;
}

.post-tiny-time {
	display: block;
	color: #aeb1be;
}

* + .post-tiny-time {
	margin-top: 3px;
}

@media (max-width: 575.98px) {
	.post-tiny {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 768px) {
	* + .post-tiny-time {
		margin-top: 10px;
	}
}

.post-creative > img {
	width: 100%;
}

.post-creative > * + img {
	margin-top: 25px;
}

.post-creative > img + * {
	margin-top: 25px;
}

.post-creative * + h4, .post-creative * + .heading-4 {
	margin-top: 15px;
}

.post-creative-title {
	font-weight: 700;
}

.post-creative-meta {
	transform: translate3d(0, -5px, 0);
	margin-bottom: -5px;
	margin-left: -15px;
	margin-right: -15px;
}

.post-creative-meta > * {
	margin-top: 5px;
	padding-left: 15px;
	padding-right: 15px;
}

.post-creative-meta > li,
.post-creative-meta > li > * {
	display: inline-block;
	vertical-align: middle;
}

.post-creative-meta > li > * + * {
	margin-left: 5px;
}

.post-creative-meta a {
	color: inherit;
}

.post-creative-meta a:hover {
	color: #ef172c;
}

.post-creative-meta .icon {
	font-size: 1.5em;
	color: #ef172c;
}

.post-creative-footer {
	transform: translate3d(0, -10px, 0);
	margin-bottom: -10px;
	margin-left: -15px;
	margin-right: -15px;
}

.post-creative-footer > * {
	margin-top: 10px;
	padding-left: 15px;
	padding-right: 15px;
}

.post-creative-footer > * {
	display: inline-block;
	vertical-align: middle;
}

* + .post-creative-meta {
	margin-top: 15px;
}

* + .post-creative-footer {
	margin-top: 25px;
}

@media (min-width: 768px) {
	.post-creative-title {
		max-width: 80%;
	}
}

@media (min-width: 992px) {
	* + .post-creative-meta {
		margin-top: 25px;
	}
	.post-creative + [class*='section'] {
		margin-top: 30px;
	}
}

@media (min-width: 1200px) {
	.post-creative h4,
	.post-creative .heading-4 {
		font-size: 22px;
		line-height: 1.46;
	}
	.post-creative > * + img {
		margin-top: 30px;
	}
	.post-creative > img + * {
		margin-top: 40px;
	}
	.post-creative * + h4, .post-creative * + .heading-4 {
		margin-top: 32px;
	}
	.post-creative > .quote-light + img {
		margin-top: 50px;
	}
	* + .post-creative-meta {
		margin-top: 30px;
	}
	* + .post-creative-footer {
		margin-top: 40px;
	}
}

@media (min-width: 1600px) {
	.post-creative + [class*='section'] {
		margin-top: 55px;
	}
}

/*
*
* Quotes
*/
.quote-icon {
	color: #aeb1be;
	font-size: 44px;
	line-height: 1;
}

@media (min-width: 1200px) {
	.quote-icon {
		font-size: 56px;
	}
}

.quote-icon.mdi-format-quote {
	transform: rotate(-180deg);
	margin-left: -0.2em;
}

.quote-light-cite {
	font-size: 20px;
	color: #ef172c;
}

.quote-light-caption {
	line-height: 1.2;
}

.quote-light-text {
	font-size: 16px;
	line-height: 1.5;
	letter-spacing: 0;
	color: #29293a;
}

html img.quote-light-image {
	display: inline-block;
}

* + .quote-light {
	margin-top: 30px;
}

* + .quote-light-caption {
	margin-top: 3px;
}

* + .quote-icon {
	margin-top: 15px;
}

* + .quote-light-text {
	margin-top: 8px;
}

* + .quote-light-footer {
	margin-top: 20px;
}

@media (min-width: 576px) {
	.quote-light-cite {
		font-size: 20px;
	}
}

@media (min-width: 768px) {
	.quote-light-cite {
		font-size: 24px;
	}
	.quote-light-text {
		font-size: 21px;
		line-height: 1.45;
	}
	* + .quote-light {
		margin-top: 40px;
	}
	* + .quote-icon {
		margin-top: 35px;
	}
	* + .quote-light-footer {
		margin-top: 30px;
	}
}

@media (min-width: 1600px) {
	.quote-light-text {
		font-size: 24px;
		line-height: 1.33333;
	}
	* + .quote-light {
		margin-top: 50px;
	}
	* + .quote-icon {
		margin-top: 50px;
	}
	* + .quote-light-footer {
		margin-top: 45px;
	}
}

.quote-classic {
	text-align: left;
}

.quote-classic-meta {
	display: flex;
	align-items: center;
	flex-wrap: wrap;
	margin-bottom: -20px;
	margin-left: -20px;
}

.quote-classic-meta:empty {
	margin-bottom: 0;
	margin-left: 0;
}

.quote-classic-meta > * {
	display: inline-block;
	margin: 0 0 20px 20px;
}

.quote-classic-avatar {
	position: relative;
	overflow: hidden;
	width: 50px;
	height: 50px;
	border-radius: 50%;
	flex-shrink: 0;
}

.quote-classic-avatar img {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.quote-classic-avatar img {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.quote-classic-cite {
	font-size: 20px;
	line-height: 1.2;
	color: #ef172c;
}

.quote-classic-caption {
	color: #aeb1be;
}

* + .quote-classic-text {
	margin-top: 25px;
}

* + .quote-classic-caption {
	margin-top: 0;
}

@media (max-width: 575.98px) {
	.quote-classic {
		max-width: 340px;
		margin-left: auto;
		margin-right: auto;
	}
}

.quote-modern {
	text-align: left;
}

.quote-modern-meta {
	display: flex;
	align-items: center;
	flex-wrap: wrap;
	margin-bottom: -20px;
	margin-left: -20px;
}

.quote-modern-meta:empty {
	margin-bottom: 0;
	margin-left: 0;
}

.quote-modern-meta > * {
	display: inline-block;
	margin: 0 0 20px 20px;
}

.quote-modern-avatar {
	position: relative;
	overflow: hidden;
	z-index: 2;
	width: 50px;
	height: 50px;
	border-radius: 50%;
	flex-shrink: 0;
}

.quote-modern-avatar img {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.quote-modern-avatar img {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.quote-modern-cite {
	font-size: 20px;
	line-height: 1.2;
	color: #ef172c;
}

.quote-modern-caption {
	color: #aeb1be;
}

.quote-modern-mark {
	color: #aeb1be;
}

* + .quote-modern-meta {
	margin-top: 25px;
}

* + .quote-modern-caption {
	margin-top: 0;
}

* + .quote-modern-text {
	margin-top: 8px;
}

.quote-modern-big .quote-modern-text {
	font-size: 18px;
	line-height: 1.5;
	color: #29293a;
}

@media (min-width: 992px) {
	.quote-modern-big .quote-modern-text {
		font-size: 20px;
	}
}

@media (min-width: 1200px) {
	.quote-modern-big .quote-modern-text {
		font-size: 24px;
		line-height: 1.33333;
	}
	.quote-modern-big * + .quote-modern-text {
		margin-top: 10px;
	}
}

/*
*
* Thumbnails
*/
.video-overlay {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background-position: center center;
	background-size: cover;
	cursor: pointer;
}

.figure-light figcaption {
	padding-top: 15px;
	color: #15191f;
}

* + .figure-light {
	margin-top: 20px;
}

@media (min-width: 1200px) {
	* + .figure-light {
		margin-top: 40px;
	}
}

.figure-card {
	position: relative;
	overflow: hidden;
	display: flex;
}

.figure-card .figure-card-sizer {
	display: block;
	width: 100%;
}

.figure-card .figure-card-sizer::before {
	display: block;
	content: '';
	visibility: hidden;
	padding-bottom: 56.25%;
}

.figure-card img {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.figure-card img {
		height: 100%;
		width: 100%;
		left: 0;
		top: 0;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.thumbnail-video-1 {
	position: relative;
	text-align: center;
}

.thumbnail-video-1 .embed-responsive::before {
	min-height: 250px;
}

.thumbnail-video-1 .video-overlay {
	position: relative;
	height: 320px;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	padding: 20px;
	z-index: 1;
	background-position: 80% center;
}

.thumbnail-video-1 .video-overlay::after {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(0, 0, 0, 0.4);
	z-index: -1;
	pointer-events: none;
}

.thumbnail-video-1 * + .button-video {
	margin-top: 25px;
}

.thumbnail-minimal {
	position: relative;
	overflow: hidden;
	display: block;
}

.thumbnail-minimal::before {
	content: '';
	display: block;
	padding-bottom: 100%;
}

.thumbnail-minimal-image {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.thumbnail-minimal-image {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.thumbnail-minimal-caption {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1;
	background: rgba(195, 7, 52, 0.6);
	display: flex;
	align-items: center;
	justify-content: center;
	opacity: 0;
	visibility: hidden;
	transition: all 0.3s ease-in-out;
	pointer-events: none;
}

.thumbnail-minimal-caption::before {
	content: '\f504';
	font-family: 'Material Design Icons';
	font-size: 30px;
	line-height: 1;
	color: #fff;
}

.thumbnail-minimal:hover .thumbnail-minimal-caption {
	opacity: 1;
	visibility: visible;
}

[data-x-mode="true"] .thumbnail-minimal-caption {
	pointer-events: none;
}

[data-x-mode="true"] .thumbnail-minimal-caption > * {
	pointer-events: auto;
}

.thumbnail-classic {
	position: relative;
	overflow: hidden;
	display: flex;
	text-align: left;
	cursor: pointer;
}

.thumbnail-classic * {
	color: inherit;
}

.thumbnail-classic, .thumbnail-classic:active, .thumbnail-classic:focus, .thumbnail-classic:hover {
	color: #fff;
}

.thumbnail-classic:hover {
	color: #fff;
}

.thumbnail-classic > * {
	width: 100%;
	flex-shrink: 0;
}

.thumbnail-classic-sm .thumbnail-classic-dummy::before {
	padding-bottom: 69.18919%;
}

.thumbnail-classic-dummy {
	width: 100%;
}

.thumbnail-classic-dummy::before {
	content: '';
	display: block;
	visibility: hidden;
	pointer-events: none;
	padding-bottom: 73.84615%;
}

.thumbnail-classic-image {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.thumbnail-classic-image {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.thumbnail-classic-caption {
	position: relative;
	z-index: 1;
	display: flex;
	flex-direction: column;
	justify-content: flex-end;
	width: 100%;
	padding: 5px;
	background: rgba(21, 25, 31, 0.4);
	font-size: 14px;
}

.thumbnail-classic-caption * + p {
	margin-top: 5px;
	text-align: center;
	padding-bottom: 10px;
}

[data-x-mode="true"] .thumbnail-classic-caption {
	pointer-events: none;
}

[data-x-mode="true"] .thumbnail-classic-caption > * {
	pointer-events: auto;
}

.thumbnail-classic-title {
	font-family: "Averia Libre";
	font-size: 40px;
	line-height: 1.3;
	text-align: center;

}

@media (max-width: 575.98px) {
	.thumbnail-classic {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 768px) {
	.thumbnail-classic-caption {
		padding: 0px 20px;
	}
}

@media (min-width: 992px) {
	.thumbnail-classic-lg .thumbnail-classic-dummy::before {
		padding-bottom: 147.69231%;
	}
}

@media (min-width: 1200px) {
	.thumbnail-classic-caption {
		padding: 0px 40px;
		font-size: 16px;
	}
	.thumbnail-classic-caption * + p {
		margin-top: 8px;
		text-align: center;
		padding-bottom: 10px;
	}
	.thumbnail-classic-title {
		font-size: 48px;
                text-align: center;
	}
}

html:not(.tablet):not(.mobile) .thumbnail-classic-caption {
	opacity: 0;
	visibility: hidden;
	transition: .3s all linear;
	background: rgba(21, 25, 31, 0.6);
}

html:not(.tablet):not(.mobile) .thumbnail-classic:hover .thumbnail-classic-caption {
	opacity: 1;
	visibility: visible;
}

html:not(.tablet):not(.mobile) .hoverdir-item .thumbnail-classic-caption {
	opacity: 1;
	visibility: visible;
	transform: translate(-100%, 0);
}

html:not(.tablet):not(.mobile)[data-x-mode='true'] .hoverdir-item .thumbnail-classic-caption {
	opacity: 0;
	visibility: hidden;
	transform: none;
}

html:not(.tablet):not(.mobile)[data-x-mode='true'] .thumbnail-classic:hover .thumbnail-classic-caption {
	opacity: 1;
	visibility: visible;
}

.thumbnail-corporate {
	position: relative;
	overflow: hidden;
	display: flex;
	color: #fff;
	text-align: left;
}

.thumbnail-corporate * {
	color: inherit;
}

.thumbnail-corporate:hover {
	color: #fff;
}

.thumbnail-corporate > * {
	width: 100%;
	flex-shrink: 0;
}

.thumbnail-corporate[data-lightgallery="dynamic"] {
	cursor: pointer;
}

.thumbnail-corporate-light {
	text-align: center;
}

.thumbnail-corporate-light .thumbnail-corporate-caption {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
}

.thumbnail-corporate-light .thumbnail-corporate-caption > * {
	max-width: 180px;
}

.thumbnail-corporate-dummy {
	width: 100%;
	visibility: hidden;
	pointer-events: none;
}

.thumbnail-corporate-dummy::before {
	content: '';
	display: block;
	width: 0;
	padding-bottom: 69.18919%;
}

.thumbnail-corporate-image {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.thumbnail-corporate-image {
		left: 0;
		top: 0;
		transform: none;
		object-fit: cover;
		width: 100%;
		height: 100%;
		object-position: center center;
	}
}

.thumbnail-corporate-caption {
	position: relative;
	z-index: 1;
	display: flex;
	flex-direction: column;
	width: 100%;
	padding: 20px;
	background: rgba(21, 25, 31, 0.4);
}

.thumbnail-corporate-caption * + p {
	margin-top: 10px;
}

.thumbnail-corporate-link {
	position: relative;
	overflow: hidden;
	display: inline-flex;
	align-items: center;
	justify-content: center;
	width: 1.67em;
	height: 1.67em;
	text-align: center;
	border-radius: 50%;
	font-size: 24px;
	line-height: 1;
	background: #ef172c;
}

.thumbnail-corporate-link, .thumbnail-corporate-link:active, .thumbnail-corporate-link:focus, .thumbnail-corporate-link:hover {
	color: #fff;
}

.thumbnail-corporate-link .icon {
	font-size: inherit;
}

.thumbnail-corporate-link .icon:first-child,
.thumbnail-corporate-link .icon:last-child {
	vertical-align: middle;
	transition: transform 0.3s cubic-bezier(0.2, 1, 0.3, 1), opacity 0.3s cubic-bezier(0.2, 1, 0.3, 1);
}

.thumbnail-corporate-link .icon:first-child {
	display: block;
}

.thumbnail-corporate-link:hover {
	background: #353535;
}

.thumbnail-corporate-title {
	font-size: 20px;
	line-height: 1.3;
}

* + .thumbnail-corporate-link {
	margin-top: 15px;
}

@media (max-width: 575.98px) {
	.thumbnail-corporate {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 768px) {
	.thumbnail-corporate-caption {
		padding: 25px 20px;
	}
}

@media (min-width: 992px) {
	.thumbnail-corporate-lg .thumbnail-corporate-dummy::before {
		padding-bottom: 125.40541%;
	}
}

@media (min-width: 1200px) {
	.thumbnail-corporate-caption {
		padding: 30px;
	}
	.thumbnail-corporate-caption * + p {
		margin-top: 8px;
	}
	.thumbnail-corporate-title {
		font-size: 24px;
	}
}

[data-x-mode="true"] .thumbnail-corporate-caption {
	pointer-events: none;
}

[data-x-mode="true"] .thumbnail-corporate-caption > * {
	pointer-events: auto;
}

html:not(.tablet):not(.mobile) .thumbnail-corporate-caption {
	opacity: 0;
	visibility: hidden;
	transition: .3s all linear;
	background: rgba(21, 25, 31, 0.6);
}

html:not(.tablet):not(.mobile) .thumbnail-corporate-caption > * {
	opacity: 0;
	visibility: hidden;
	transition: .25s .11s all linear;
}

html:not(.tablet):not(.mobile) .thumbnail-corporate:hover .thumbnail-corporate-caption,
html:not(.tablet):not(.mobile) .thumbnail-corporate:hover .thumbnail-corporate-caption > * {
	opacity: 1;
	visibility: visible;
}

html:not(.tablet):not(.mobile) .hoverdir-item .thumbnail-corporate-caption {
	opacity: 1;
	visibility: visible;
	transform: translate(-100%, -100%);
}

html:not(.tablet):not(.mobile)[data-x-mode='true'] .hoverdir-item .thumbnail-corporate-caption {
	opacity: 0;
	visibility: hidden;
	transform: none;
}

html:not(.tablet):not(.mobile)[data-x-mode='true'] .thumbnail-corporate:hover .thumbnail-corporate-caption,
html:not(.tablet):not(.mobile)[data-x-mode='true'] .thumbnail-corporate:hover .thumbnail-corporate-caption > * {
	opacity: 1;
	visibility: visible;
}

.thumbnail-light {
	text-align: center;
}

.thumbnail-light-media {
	position: relative;
	overflow: hidden;
	display: block;
	border-radius: 0px;
}

.thumbnail-light-media::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(41, 41, 58, 0.3);
	transition: .22s ease-in-out;
	opacity: 0;
	visibility: hidden;
	pointer-events: none;
}

.thumbnail-light-media:hover::before {
	opacity: 1;
	visibility: visible;
}

.thumbnail-light-image {
	width: 100%;
}

* + .thumbnail-light-title {
	margin-top: 10px;
}

@media (max-width: 575.98px) {
	.thumbnail-light {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 992px) {
	* + .thumbnail-light-title {
		margin-top: 15px;
	}
}

.thumbnail-thin {
	position: relative;
	overflow: hidden;
	padding-bottom: 100%;
}

.thumbnail-thin::before, .thumbnail-thin::after {
	pointer-events: none;
}

.thumbnail-thin::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1;
	background: rgba(41, 41, 58, 0.3);
}

.thumbnail-thin::after {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate3d(-50%, -50%, 0);
	z-index: 2;
	content: '\f504';
	font-family: 'Material Design Icons';
	font-size: 40px;
	line-height: 1;
	color: #fff;
}

a.thumbnail-thin {
	display: block;
}

.thumbnail-thin-image {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.thumbnail-thin-image {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

html:not(.tablet):not(.mobile) .thumbnail-thin::before, html:not(.tablet):not(.mobile) .thumbnail-thin::after {
	opacity: 0;
	transition: .22s ease-in;
}

html:not(.tablet):not(.mobile) .thumbnail-thin::before {
	background: rgba(41, 41, 58, 0.6);
}

html:not(.tablet):not(.mobile) .thumbnail-thin:hover::before, html:not(.tablet):not(.mobile) .thumbnail-thin:hover::after {
	opacity: 1;
}

.thumbnail-modern {
	position: relative;
	overflow: hidden;
	display: flex;
	text-align: left;
}

.thumbnail-modern * {
	color: inherit;
}

.thumbnail-modern, .thumbnail-modern:active, .thumbnail-modern:focus, .thumbnail-modern:hover {
	color: #fff;
}

.thumbnail-modern:hover {
	color: #fff;
}

.thumbnail-modern > * {
	width: 100%;
	flex-shrink: 0;
}

.thumbnail-modern-sm .thumbnail-modern-dummy::before {
	padding-bottom: 69.18919%;
}

.thumbnail-modern-dummy {
	visibility: hidden;
	pointer-events: none;
	width: 100%;
}

.thumbnail-modern-dummy::before {
	content: '';
	display: block;
	padding-bottom: 73.84615%;
}

.thumbnail-modern-image {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
	background-position: center center;
	background-size: cover;
}

@supports (object-fit: cover) {
	.thumbnail-modern-image {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.thumbnail-modern-caption {
	position: relative;
	z-index: 1;
	display: flex;
	align-items: center;
	justify-content: center;
	width: 100%;
	padding: 20px;
	background: rgba(41, 41, 58, 0.4);
}

.thumbnail-modern-caption .icon {
	font-size: 30px;
	line-height: 1;
	color: #fff;
}

@media (max-width: 575.98px) {
	.thumbnail-modern {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 992px) {
	.thumbnail-modern-lg .thumbnail-modern-dummy::before {
		padding-bottom: 147.69231%;
	}
}

html:not(.tablet):not(.mobile) .thumbnail-modern-caption {
	opacity: 0;
	visibility: hidden;
	transition: .3s all linear;
	background: rgba(41, 41, 58, 0.6);
}

html:not(.tablet):not(.mobile) .thumbnail-modern:hover .thumbnail-modern-caption {
	opacity: 1;
	visibility: visible;
}

.thumbnail-creative {
	position: relative;
	display: block;
	max-width: 348px;
	margin-left: auto;
	margin-right: auto;
}

.thumbnail-creative:hover .thumbnail-creative-image {
	transform: translate(0, -5px);
	box-shadow: 0 2px 24px 1px rgba(0, 0, 0, 0.2);
}

.thumbnail-creative-wrap {
	padding: 26px;
	margin: -26px;
}

.thumbnail-creative-image {
	position: relative;
	display: block;
	width: 100%;
	transition: .33s ease-in-out;
	box-shadow: 0 2px 24px 0 rgba(0, 0, 0, 0.15);
}

* + .thumbnail-creative-title {
	margin-top: 16px;
}

@media (min-width: 768px) {
	* + .thumbnail-creative-title {
		margin-top: 24px;
	}
}

.thumbnail-indigo {
	position: relative;
	overflow: hidden;
	display: block;
	background: #29293a;
	box-shadow: -1px 1px 21px 0px rgba(0, 0, 0, 0.08);
	background-position: center top;
	background-size: cover;
}

.thumbnail-indigo::before {
	content: '';
	display: block;
	opacity: 0;
	visibility: hidden;
	padding-bottom: 148.75847%;
}

.thumbnail-indigo-sm::before {
	padding-bottom: 70.65463%;
}

.thumbnail-indigo-sm + .thumbnail-indigo-sm {
	margin-top: 7.4%;
}

.thumbnail-indigo-caption {
	position: absolute;
	top: auto;
	right: 0;
	bottom: 0;
	left: 0;
	display: flex;
	align-items: center;
	justify-content: center;
	padding: 20px;
	background: rgba(255, 255, 255, 0.95);
}

html:not(.tablet):not(.mobile) .thumbnail-indigo-caption {
	top: 0;
	background: rgba(255, 255, 255, 0.9);
}

html:not(.tablet):not(.mobile) .thumbnail-indigo-caption,
html:not(.tablet):not(.mobile) .thumbnail-indigo-caption > * {
	opacity: 0;
	visibility: hidden;
	will-change: opacity;
}

html:not(.tablet):not(.mobile) .thumbnail-indigo-caption {
	transition: .2s all linear;
}

html:not(.tablet):not(.mobile) .thumbnail-indigo-caption > * {
	transition: .2s .1s all ease-in;
}

html:not(.tablet):not(.mobile) .thumbnail-indigo:hover .thumbnail-indigo-caption,
html:not(.tablet):not(.mobile) .thumbnail-indigo:hover .thumbnail-indigo-caption > * {
	opacity: 1;
	visibility: visible;
}

/*
*
* Breadcrumbs
*/
.breadcrumbs-custom {
	position: relative;
	display: flex;
	background-position: 20% 20%;
}

.breadcrumbs-custom .breadcrumbs-custom-subtitle {
	color: #15191f;
}

.breadcrumbs-custom-inner {
	display: flex;
	min-height: inherit;
	width: 100%;
	padding: 50px 0 25px;
}

.breadcrumbs-custom-container {
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.breadcrumbs-custom-container::before {
	content: '';
	display: block;
}

.breadcrumbs-custom-path {
	margin-left: -15px;
	margin-right: -15px;
}

.breadcrumbs-custom-path > * {
	padding-left: 15px;
	padding-right: 15px;
}

.breadcrumbs-custom-path li {
	position: relative;
	display: inline-block;
	vertical-align: middle;
	color: #15191f;
}

.breadcrumbs-custom-path li::after {
	content: "";
	font-family: "FontAwesome";
	position: absolute;
	top: 51%;
	right: -5px;
	display: inline-block;
	font-size: inherit;
	font-style: normal;
	color: inherit;
	transform: translate3d(0, -50%, 0);
}

.breadcrumbs-custom-path li.main {
	color: #fff;
}

.breadcrumbs-custom-title {
	color: #fff;
}

.breadcrumbs-custom-path li.active {
	color: #ef172c;
}

.breadcrumbs-custom-path li:last-child:after {
	display: none;
}

.breadcrumbs-custom-path a {
	display: inline;
	vertical-align: middle;
}

.breadcrumbs-custom-path a, .breadcrumbs-custom-path a:active, .breadcrumbs-custom-path a:focus {
	color: #fff;
}

.breadcrumbs-custom-path a:hover {
	color: #ef172c;
}

* + .breadcrumbs-custom-path {
	margin-top: 25px;
}

.breadcrumbs-custom-subtitle + .breadcrumbs-custom-title {
	margin-top: 15px;
}

@media (min-width: 576px) {
	.breadcrumbs-custom-path {
		margin-left: -30px;
		margin-right: -30px;
	}
	.breadcrumbs-custom-path > * {
		padding-left: 30px;
		padding-right: 30px;
	}
	* + .breadcrumbs-custom-path {
		margin-top: 30px;
	}
}

@media (min-width: 768px) {
	.breadcrumbs-custom {
		/*min-height: 23.75vw;*/
	}
	.breadcrumbs-custom-inner {
		padding: 80px 0 30px;
	}
	.breadcrumbs-custom-subtitle + .breadcrumbs-custom-title {
		margin-top: 5px;
	}
}

@media (min-width: 992px) {
	.breadcrumbs-custom-inner {
		padding-bottom: 40px;
	}
	.breadcrumbs-custom-subtitle + .breadcrumbs-custom-title {
		margin-top: 10px;
	}
}

@media (min-width: 1600px) {
	.breadcrumbs-custom {
		min-height: 220px;
	}
	.breadcrumbs-custom-inner {
		padding: 50px 0 40px;
	}
	.breadcrumbs-custom-subtitle + .breadcrumbs-custom-title {
		margin-top: 20px;
	}
}

.breadcrumbs-minimal {
	padding: 40px 0;
	background-color: #29293a;
}

.breadcrumbs-minimal .breadcrumbs-custom-path li {
	color: #fff;
}

.breadcrumbs-minimal .breadcrumbs-custom-path li.active {
	color: rgba(255, 255, 255, 0.7);
}

.breadcrumbs-minimal .breadcrumbs-custom-path li:last-child:after {
	display: none;
}

.breadcrumbs-minimal .breadcrumbs-custom-path a {
	display: inline;
	vertical-align: middle;
}

.breadcrumbs-minimal .breadcrumbs-custom-path a, .breadcrumbs-minimal .breadcrumbs-custom-path a:active, .breadcrumbs-minimal .breadcrumbs-custom-path a:focus {
	color: #fff;
}

.breadcrumbs-minimal .breadcrumbs-custom-path a:hover {
	color: rgba(255, 255, 255, 0.7);
}

/*
*
* Pagination custom
*/
.pagination {
	font-size: 0;
	line-height: 0;
	margin-bottom: -10px;
	margin-left: -10px;
}

.pagination:empty {
	margin-bottom: 0;
	margin-left: 0;
}

.pagination > * {
	display: inline-block;
	margin: 0 0 10px 10px;
}

.page-item {
	display: inline-block;
	vertical-align: middle;
	text-align: center;
	font-weight: 700;
}

.page-link {
	display: inline-flex;
	align-items: center;
	justify-content: center;
	min-width: 48px;
	min-height: 48px;
	padding: 0 9px;
	border: 1px solid #ef172c;
	border-radius: 0px;
	font-family: "Averia Libre";
	font-size: 14px;
	font-weight: 500;
	line-height: 48px;
	background-color: transparent;
	color: #ef172c;
	transition: all 0.3s ease-in-out;
	outline: none;
}

.page-link:focus {
	outline: none;
	box-shadow: none;
}

.page-link.button-winona * {
	line-height: inherit;
}

.page-link.button-winona .content-dubbed {
	margin-top: -1px;
}

.page-link:hover, .page-link:focus, .page-link:active {
	color: #fff;
	background-color: #ef172c;
	border-color: #ef172c;
}

.page-item.active > .page-link, .page-item.active > .page-link:hover, .page-item.active > .page-link:focus, .page-item.active > .page-link:active {
	color: #fff;
	background-color: #ef172c;
	border-color: #ef172c;
}

.page-item.disabled > .page-link, .page-item.disabled > .page-link:hover, .page-item.disabled > .page-link:focus, .page-item.disabled > .page-link:active {
	color: #15191f;
	background-color: #e8e9ee;
}

.page-item-control .icon::before {
	font-family: 'FontAwesome';
	font-size: 11px;
	line-height: 48px;
}

.page-item-control:first-child .icon::before {
	content: '\f053';
	margin-left: -1px;
}

.page-item-control:last-child .icon::before {
	content: '\f054';
	margin-right: -1px;
}

* + .pagination {
	margin-top: 35px;
}

@media (min-width: 992px) {
	* + .pagination {
		margin-top: 55px;
	}
}

@media (min-width: 1600px) {
	* + .pagination {
		margin-top: 70px;
	}
}

/*
*
* Snackbars
*/
.snackbars {
	padding: 9px 16px;
	margin-left: auto;
	margin-right: auto;
	color: #fff;
	text-align: left;
	background-color: #ef172c;
	box-shadow: 0 1px 4px 0 rgba(0, 0, 0, 0.15);
	border-radius: 0px;
	font-size: 14px;
}

.snackbars .icon-xxs {
	font-size: 18px;
}

.snackbars p span:last-child {
	padding-left: 14px;
}

.snackbars-left {
	display: inline-block;
	margin-bottom: 0;
}

.snackbars-right {
	display: inline-block;
	float: right;
	text-transform: uppercase;
}

.snackbars-right:hover {
	text-decoration: underline;
}

@media (min-width: 576px) {
	.snackbars {
		max-width: 540px;
		padding: 12px 15px;
		font-size: 15px;
	}
}

/*
*
* Footers
*/
.footer-standard h4 + *,
.footer-standard .heading-4 + * {
	margin-top: 14px;
}

.footer-standard-main {
	padding: 35px 0 15px;
}

.footer-standard-aside {
	padding: 30px 0;
}

.footer-standard-aside-inner {
	margin-bottom: -18px;
	text-align: center;
}

.footer-standard-aside-inner > * {
	margin-bottom: 18px;
}

.footer-standard-aside-inner > * {
	margin-top: 0;
}

.footer-standard-aside-inner:after {
	content: '';
	display: table;
	width: 100%;
}

@media (max-width: 575.98px) {
	.footer-standard .box-1 {
		margin-left: 0;
	}
}

@media (min-width: 768px) and (max-width: 991.98px) {
	.footer-standard .box-1 {
		margin-left: 0;
	}
}

@media (min-width: 768px) {
	.footer-standard h4 + *,
	.footer-standard .heading-4 + * {
		margin-top: 25px;
	}
	.footer-standard-main {
		padding: 55px 0 20px;
	}
	.footer-standard-aside-inner {
		display: flex;
		align-items: center;
		flex-wrap: wrap;
		justify-content: space-between;
		text-align: center;
		margin-left: -20px;
	}
	.footer-standard-aside-inner > * {
		margin-left: 20px;
	}
}

@media (min-width: 1200px) {
	.footer-standard-main {
		padding: 80px 0 50px;
	}
}

.footer-minimal {
	padding: 30px 0;
}

.footer-minimal-inner {
	margin-bottom: -18px;
	text-align: center;
}

.footer-minimal-inner > * {
	margin-bottom: 18px;
}

.footer-minimal-inner > * {
	margin-top: 0;
}

.footer-minimal-inner .rights a:hover {
	color: #ef172c;
}

@media (min-width: 768px) {
	.footer-minimal-inner {
		display: flex;
		align-items: center;
		flex-wrap: wrap;
		justify-content: space-between;
		text-align: center;
		margin-left: -20px;
	}
	.footer-minimal-inner > * {
		margin-left: 20px;
	}
}

.footer-advanced.bg-gray-700 h1, .footer-advanced.bg-gray-700 h2, .footer-advanced.bg-gray-700 h3, .footer-advanced.bg-gray-700 h4, .footer-advanced.bg-gray-700 h5, .footer-advanced.bg-gray-700 h6, .footer-advanced.bg-gray-700 [class^='heading-'] {
	color: #aeb1be;
}

.footer-advanced h4 + *,
.footer-advanced .heading-4 + * {
	margin-top: 14px;
}

.footer-advanced-main {
	padding: 35px 0 15px;
}

.footer-advanced-aside {
	padding: 20px 0;
}

.footer-advanced-layout {
	margin-bottom: -18px;
	text-align: center;
}

.footer-advanced-layout > * {
	margin-bottom: 18px;
}

.footer-advanced-layout > * {
	margin-top: 0;
}

@media (min-width: 768px) and (max-width: 991.98px) {
	.footer-advanced .box-1 {
		margin-left: 0;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.footer-advanced-text {
		font-size: 14px;
		line-height: 1.7;
	}
}

@media (min-width: 1200px) {
	.footer-advanced-text {
		max-width: 90%;
	}
}

@media (min-width: 768px) {
	.footer-advanced-main {
		padding: 55px 0 20px;
	}
	.footer-advanced-aside {
		padding: 25px 0;
	}
	.footer-advanced-layout {
		display: flex;
		align-items: center;
		flex-wrap: wrap;
		justify-content: space-between;
		text-align: center;
		margin-left: -20px;
	}
	.footer-advanced-small {
		font-size: small;
	}
	.footer-advanced-layout > * {
		margin-left: 20px;
	}
	.footer-advanced-aside + .container {
		margin-top: 10px;
	}
}

@media (min-width: 1200px) {
	.footer-advanced h4 + *,
	.footer-advanced .heading-4 + * {
		margin-top: 35px;
	}
	.footer-advanced-main {
		padding: 80px 0 60px;
	}
	.footer-advanced-aside + .container {
		margin-top: 20px;
	}
}

.footer-linked.bg-gray-700 h1, .footer-linked.bg-gray-700 h2, .footer-linked.bg-gray-700 h3, .footer-linked.bg-gray-700 h4, .footer-linked.bg-gray-700 h5, .footer-linked.bg-gray-700 h6, .footer-linked.bg-gray-700 [class^='heading-'] {
	color: #aeb1be;
}

.footer-linked.bg-gray-700 .list {
	color: #fff;
}

.footer-linked.bg-gray-700 .list a:hover {
	color: rgba(255, 255, 255, 0.6);
}

.footer-linked h4 + *,
.footer-linked .heading-4 + * {
	margin-top: 14px;
}

.footer-linked h4 + hr,
.footer-linked .heading-4 + hr {
	margin-top: 15px;
}

.footer-linked * + .row {
	margin-top: 25px;
}

.footer-linked-main {
	padding: 35px 0 15px;
}

.footer-linked-aside {
	padding: 30px 0;
}

.footer-linked-layout {
	margin-bottom: -18px;
	text-align: center;
}

.footer-linked-layout > * {
	margin-bottom: 18px;
}

.footer-linked-layout > * {
	margin-top: 0;
}

@media (min-width: 768px) and (max-width: 991.98px) {
	.footer-linked .box-1 {
		margin-left: 0;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.footer-linked-text {
		font-size: 14px;
		line-height: 1.7;
	}
}

@media (min-width: 768px) {
	.footer-linked-main {
		padding: 65px 0 40px;
	}
	.footer-linked-aside {
		padding: 30px 0;
	}
	.footer-linked-layout {
		display: flex;
		align-items: center;
		flex-wrap: wrap;
		justify-content: space-between;
		text-align: center;
		margin-left: -20px;
	}
	.footer-linked-layout > * {
		margin-left: 20px;
	}
	.footer-linked-aside + .container {
		margin-top: 10px;
	}
}

@media (min-width: 1200px) {
	.footer-linked h4 + *,
	.footer-linked .heading-4 + * {
		margin-top: 35px;
	}
	.footer-linked-main {
		padding: 90px 0 60px;
	}
	.footer-linked-aside + .container {
		margin-top: 20px;
	}
}

/*
*
* Pricing tables
*/
.pricing-minimal {
	position: relative;
	z-index: 1;
	padding: 25px 20px;
	border: 1px solid #aeb1be;
	border-radius: 0px;
	text-align: left;
	transition: .22s;
	cursor: default;
}

.pricing-minimal:hover {
	border-color: #ef172c;
}

.pricing-minimal:hover::before {
	visibility: visible;
	transform: translate3d(0, 0, 0);
}

.pricing-minimal-price {
	font-size: 26px;
	line-height: 1;
	font-weight: 700;
	letter-spacing: 0;
	color: #29293a;
}

.pricing-minimal-price span {
	display: inline;
}

.pricing-minimal-price-currency {
	font-size: .65em;
	vertical-align: top;
}

.pricing-minimal-divider {
	border-bottom: 1px solid #aeb1be;
}

* + .pricing-minimal-price {
	margin-top: 10px;
}

* + .pricing-minimal-divider {
	margin-top: 20px;
}

@media (max-width: 575.98px) {
	.pricing-minimal {
		max-width: 350px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 576px) {
	.pricing-minimal {
		padding: 20px;
	}
}

@media (min-width: 768px) {
	.pricing-minimal-price {
		font-size: 36px;
	}
}

@media (min-width: 768px) {
	.pricing-minimal {
		padding: 30px 38px;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.pricing-minimal {
		padding: 25px 20px;
	}
}

@media (min-width: 1200px) {
	.pricing-minimal {
		padding: 38px 40px;
	}
}

.pricing-modern {
	padding: 35px 20px;
	border: 1px solid #aeb1be;
	border-radius: 0px;
	text-align: center;
}

.pricing-modern * + .button {
	margin-top: 20px;
}

.pricing-group-modern {
	border: 1px solid #aeb1be;
	border-radius: 0px;
}

.pricing-group-modern .pricing-modern {
	border: 0;
	border-radius: 0;
}

.pricing-modern-rating {
	color: #ef172c;
}

.pricing-modern-rating > li {
	display: inline-block;
	width: 26px;
	font-size: 30px;
	line-height: .9;
}

.pricing-modern-title {
	font-weight: 700;
}

.pricing-modern-table {
	display: inline-table;
}

.pricing-modern-table td {
	padding: 3px 8px;
	color: #15191f;
}

.pricing-modern-table td:first-child {
	text-align: right;
	color: #29293a;
}

.pricing-modern-table td:last-child {
	text-align: left;
}

.pricing-modern-price {
	font-size: 24px;
	font-weight: 300;
	line-height: 1.2;
}

.pricing-modern-price span {
	display: inline;
}

.pricing-modern-price-currency {
	font-size: .65em;
	vertical-align: top;
}

* + .pricing-group-modern {
	margin-top: 35px;
}

* + .pricing-modern-title {
	margin-top: 5px;
}

* + .pricing-modern-table {
	margin-top: 20px;
}

* + .pricing-modern-price {
	margin-top: 15px;
}

@media (max-width: 575.98px) {
	.pricing-group-modern {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
	.pricing-group-modern .pricing-modern + .pricing-modern {
		border-top: 1px solid #aeb1be;
	}
}

@media (min-width: 576px) and (max-width: 991.98px) {
	.pricing-group-modern .pricing-modern:nth-child(odd) {
		border-right: 1px solid #aeb1be;
	}
	.pricing-group-modern .pricing-modern:nth-child(n + 3) {
		border-top: 1px solid #aeb1be;
	}
}

@media (min-width: 576px) {
	.pricing-group-modern {
		display: flex;
		flex-wrap: wrap;
	}
	.pricing-group-modern .pricing-modern {
		width: 100%;
		max-width: 50%;
	}
	.pricing-modern {
		padding: 55px 20px;
	}
	* + .pricing-group-modern {
		margin-top: 50px;
	}
	* + .pricing-modern-table {
		margin-top: 25px;
	}
	* + .pricing-modern-price {
		margin-top: 30px;
	}
}

@media (min-width: 768px) {
	.pricing-modern-price {
		font-size: 30px;
	}
}

@media (min-width: 992px) {
	.pricing-group-modern .pricing-modern {
		max-width: 25%;
		border-right: 1px solid #aeb1be;
	}
	.pricing-group-modern .pricing-modern:nth-child(4n) {
		border-right: 0;
	}
	.pricing-group-modern .pricing-modern:nth-child(n + 5) {
		border-top: 1px solid #aeb1be;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.pricing-modern .button {
		display: block;
		padding-left: 15px;
		padding-right: 15px;
	}
}

@media (min-width: 1200px) {
	.pricing-modern-price {
		font-size: 36px;
	}
	* + .pricing-modern-table {
		margin-top: 35px;
	}
	* + .pricing-modern-price {
		margin-top: 40px;
	}
}

@media (min-width: 1600px) {
	* + .pricing-group-modern {
		margin-top: 75px;
	}
}

/*
*
* Profiles
*/
.profile-classic {
	text-align: left;
}

.profile-classic-main {
	position: relative;
	overflow: hidden;
	z-index: 1;
	border-radius: 0px;
}

.profile-classic-image {
	min-width: 100%;
}

.profile-classic-caption {
	position: absolute;
	left: 0;
	right: 0;
	bottom: 0;
	padding: 10px;
	background: rgba(195, 7, 52, 0.6);
}

.profile-classic-caption .icon-creative {
	color: #fff;
}

.profile-classic-title {
	color: #ef172c;
}

.profile-classic-title a:hover {
	color: #37020e;
}

.profile-classic-position {
	color: #aeb1be;
}

* + .profile-classic-title {
	margin-top: 15px;
}

* + .profile-classic-position {
	margin-top: 5px;
}

@media (max-width: 575.98px) {
	.profile-classic {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 576px) and (max-width: 767.98px) {
	.profile-classic-caption {
		padding-left: 5px;
		padding-right: 5px;
	}
	.profile-classic-caption .icon-sm {
		font-size: 18px;
	}
	.profile-classic-caption .group {
		margin-left: -3px;
	}
	.profile-classic-caption .group > * {
		margin-left: 3px;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.profile-classic-caption {
		padding-left: 5px;
		padding-right: 5px;
	}
	.profile-classic-caption .icon-sm {
		font-size: 18px;
	}
	.profile-classic-caption .group {
		margin-left: -3px;
	}
	.profile-classic-caption .group > * {
		margin-left: 3px;
	}
}

@media (min-width: 1200px) {
	* + .profile-classic-title {
		margin-top: 20px;
	}
}

html:not(.tablet):not(.mobile) .profile-classic:hover .profile-classic-caption {
	opacity: 1;
	visibility: visible;
}

html:not(.tablet):not(.mobile) .profile-classic-caption {
	top: 0;
	display: flex;
	flex-direction: column;
	justify-content: flex-end;
	opacity: 0;
	visibility: hidden;
	transition: .33s ease-in-out;
}

[data-x-mode="true"] .profile-classic-caption {
	pointer-events: none;
}

[data-x-mode="true"] .profile-classic-caption > * {
	pointer-events: auto;
}

.profile-creative {
	display: flex;
	margin-left: -15px;
	text-align: left;
	color: #15191f;
}

.profile-creative > * {
	margin-left: 15px;
}

.profile-creative-figure {
	position: relative;
	overflow: hidden;
	max-width: 80px;
	flex-shrink: 0;
}

.profile-creative-image {
	width: 100%;
	border-radius: 0px;
}

.profile-creative-main {
	flex-grow: 1;
}

.profile-creative-title {
	color: #ef172c;
}

.profile-creative-title a:hover {
	color: #37020e;
}

.profile-creative-position {
	color: #aeb1be;
}

.profile-creative-contacts {
	color: #aeb1be;
}

.profile-creative-contacts a {
	color: inherit;
}

.profile-creative-contacts a:hover {
	color: #ef172c;
}

* + .profile-creative-position {
	margin-top: 0;
}

* + .profile-creative-contacts {
	margin-top: 15px;
}

@media (min-width: 576px) {
	.profile-creative {
		margin-left: -30px;
	}
	.profile-creative > * {
		margin-left: 30px;
	}
	.profile-creative-figure {
		max-width: 22%;
	}
}

@media (min-width: 768px) {
	.profile-creative-figure {
		max-width: 29%;
	}
	.profile-creative-main {
		padding-right: 30px;
	}
	* + .profile-creative-contacts {
		margin-top: 22px;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.profile-creative {
		margin-left: -20px;
	}
	.profile-creative > * {
		margin-left: 20px;
	}
	.profile-creative-figure {
		max-width: 25%;
	}
	.profile-creative-main {
		padding-right: 10px;
	}
}

.profile-minimal {
	position: relative;
	overflow: hidden;
	border-radius: 0px;
	color: #fff;
	text-align: left;
}

.profile-minimal::before {
	content: '';
	display: block;
	padding-bottom: 100%;
}

.profile-minimal-image {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	max-width: none;
}

@supports (object-fit: cover) {
	.profile-minimal-image {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.profile-minimal-caption {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	display: flex;
	flex-direction: column;
	justify-content: flex-end;
	padding: 25px;
	background: rgba(41, 41, 58, 0.4);
}

.profile-minimal-title {
	color: #fff;
}

* + .profile-minimal-position {
	margin-top: 5px;
}

@media (max-width: 575.98px) {
	.profile-minimal {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 1200px) {
	.profile-minimal-caption {
		padding: 35px;
	}
	* + .profile-minimal-position {
		margin-top: 10px;
	}
}

[data-x-mode="true"] .profile-minimal-caption {
	pointer-events: none;
}

[data-x-mode="true"] .profile-minimal-caption > * {
	pointer-events: auto;
}

html:not(.tablet):not(.mobile) .profile-minimal:hover .profile-minimal-caption {
	opacity: 1;
	visibility: visible;
}

html:not(.tablet):not(.mobile) .profile-minimal-caption {
	opacity: 0;
	visibility: hidden;
	transition: .35s ease-in;
	background: rgba(21, 25, 31, 0.6);
}

.profile-modern {
	text-align: left;
}

.profile-modern > * + * {
	margin-top: 35px;
}

.profile-modern-header {
	display: flex;
	justify-content: space-between;
	flex-wrap: wrap;
	margin-bottom: -10px;
	margin-left: -20px;
}

.profile-modern-header:empty {
	margin-bottom: 0;
	margin-left: 0;
}

.profile-modern-header > * {
	display: inline-block;
	margin: 0 0 10px 20px;
}

.profile-modern-header * + p {
	margin-top: 5px;
}

.profile-modern-figure {
	position: relative;
	overflow: hidden;
	border-radius: 0px;
}

.profile-modern-image {
	display: block;
	width: 100%;
}

.profile-modern-button {
	position: absolute;
	right: 30px;
	bottom: 30px;
	overflow: hidden;
	display: inline-flex;
	align-items: center;
	justify-content: center;
	width: 1.86em;
	height: 1.86em;
	text-align: center;
	border-radius: 50%;
	font-size: 32px;
	line-height: 1;
	background: #ef172c;
}

.profile-modern-button, .profile-modern-button:active, .profile-modern-button:focus, .profile-modern-button:hover {
	color: #fff;
}

.profile-modern-button .icon {
	font-size: inherit;
}

.profile-modern-button .icon:first-child,
.profile-modern-button .icon:last-child {
	vertical-align: middle;
}

.profile-modern-button .icon:first-child {
	display: block;
}

.profile-modern-button:hover {
	color: #fff;
	background: #37020e;
}

@media (max-width: 575.98px) {
	.profile-modern {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
	.profile-modern * + .row {
		margin-top: 15px;
	}
}

@media (max-width: 767.98px) {
	.profile-modern-figure {
		max-width: 330px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 768px) {
	.profile-modern {
		display: flex;
		align-items: flex-start;
		margin-left: -30px;
	}
	.profile-modern > * {
		margin-left: 30px;
	}
	.profile-modern > * + * {
		margin-top: 0;
	}
	.profile-modern-figure {
		max-width: 50%;
		flex-shrink: 0;
	}
	.profile-modern-main {
		flex-grow: 1;
	}
	* + .profile-modern-main {
		margin-top: 0;
	}
}

@media (min-width: 992px) {
	.profile-modern-figure {
		max-width: 28%;
	}
}

@media (min-width: 768px) and (max-width: 1199.98px) {
	.profile-modern {
		font-size: 14px;
	}
	.profile-modern * + .row {
		margin-top: 31px;
	}
}

@media (min-width: 1200px) {
	.profile-modern {
		margin-left: -60px;
	}
	.profile-modern > * {
		margin-left: 60px;
	}
}

.profile-thin {
	position: relative;
	display: block;
	padding: 30px 20px 45px;
	background: #f5f6fa;
	text-align: center;
}

.profile-thin * + p {
	margin-top: 20px;
}

.profile-thin * + .group {
	margin-top: 15px;
}

.profile-thin * + .button-sm {
	margin-top: 15px;
}

.profile-thin .group {
	margin-left: auto;
	margin-right: auto;
}

.profile-thin-aside {
	position: relative;
	display: inline-block;
}

.profile-thin-image {
	border-radius: 50%;
}

.profile-thin-contact-button {
	position: absolute;
	right: 0;
	bottom: 0;
	overflow: hidden;
	display: inline-flex;
	align-items: center;
	justify-content: center;
	width: 2em;
	height: 2em;
	text-align: center;
	border-radius: 50%;
	font-size: 20px;
	line-height: 1;
	background: #ef172c;
}

.profile-thin-contact-button, .profile-thin-contact-button:active, .profile-thin-contact-button:focus, .profile-thin-contact-button:hover {
	color: #fff;
}

.profile-thin-contact-button .icon {
	font-size: inherit;
}

.profile-thin-contact-button .icon:first-child,
.profile-thin-contact-button .icon:last-child {
	vertical-align: middle;
}

.profile-thin-contact-button .icon:first-child {
	display: block;
}

.profile-thin-contact-button:hover {
	color: #fff;
	background: #37020e;
}

.profile-thin-title {
	font-size: 22px;
	line-height: 1.47;
}

* + p.profile-thin-subtitle {
	margin-top: 0;
}

* + .profile-thin-main {
	margin-top: 20px;
}

@media (min-width: 576px) and (max-width: 991.98px) {
	.profile-thin {
		display: flex;
		align-items: flex-start;
		text-align: left;
	}
	.profile-thin .group {
		margin-left: -15px;
	}
	.profile-thin > * + * {
		margin-left: 30px;
	}
	.profile-thin-aside {
		flex-shrink: 0;
		max-width: 30%;
	}
	.profile-thin-main {
		flex-grow: 1;
	}
	* + .profile-thin-main {
		margin-top: 0;
	}
}

@media (min-width: 1200px) {
	.profile-thin {
		padding: 55px 35px;
	}
	.profile-thin * + .group {
		margin-top: 25px;
	}
	.profile-thin * + .button-sm {
		margin-top: 25px;
	}
}

/*
*
* Counters
*/
.counter-minimal {
	position: relative;
	text-align: center;
	color: #fff;
}

.counter-minimal-icon {
	display: block;
	font-size: 24px;
	line-height: 1;
	color: #ef172c;
}

.counter-minimal-main {
	display: inline-flex;
	font-size: 36px;
	font-weight: 500;
	line-height: 1.2;
	letter-spacing: 0;
	font-family: "Averia Libre";
}

.counter-minimal-main > * {
	display: inline;
	font: inherit;
}

.counter-minimal-main span {
	display: inline;
}

* + .counter-minimal-title {
	margin-top: 10px;
}

* + .counter-minimal-main {
	margin-top: 15px;
}

@media (max-width: 575.98px) {
	.counter-minimal-title {
		font-size: 16px;
		line-height: 1.4;
	}
}

@media (min-width: 768px) {
	.counter-minimal-icon {
		font-size: 28px;
	}
}

@media (min-width: 768px) {
	.counter-minimal-main {
		font-size: 48px;
	}
}

@media (min-width: 1200px) {
	* + .counter-minimal-main {
		margin-top: 25px;
	}
	* + .counter-minimal-title {
		margin-top: 22px;
	}
}

/*
*
* Layouts
*/
.layout-bordered {
	text-align: center;
}

.layout-bordered-item {
	border: 0 solid #d3d5db;
}

.layout-bordered-item-inner {
	display: flex;
	flex-direction: column;
	justify-content: center;
	max-width: 290px;
	padding: 0 15px;
	margin-left: auto;
	margin-right: auto;
}

.layout-bordered-item-inner > * + * {
	margin-top: 10px;
}

@media (max-width: 767.98px) {
	.layout-bordered-item {
		padding: 30px 0;
	}
	.layout-bordered-item:first-child {
		padding-top: 0;
	}
	.layout-bordered-item:last-child {
		padding-bottom: 0;
	}
	.layout-bordered-item + .layout-bordered-item {
		border-top-width: 1px;
	}
}

@media (min-width: 768px) {
	.layout-bordered {
		display: flex;
	}
	.layout-bordered-item {
		flex-grow: 1;
	}
	.layout-bordered-item-inner > * + * {
		margin-top: 15px;
	}
}

@media (min-width: 768px) and (max-width: 991.98px) {
	.layout-bordered-item {
		font-size: 15px;
	}
}

@media (min-width: 768px) {
	.layout-bordered-item {
		flex-basis: 33.333%;
		border-right-width: 1px;
	}
	.layout-bordered-item:first-child {
		border-left-width: 1px;
	}
}

.layout-navbar-demo {
	position: relative;
	overflow: hidden;
	min-height: 400px;
	background: #e8e9ee;
}

.layout-navbar-demo.layout-navbar-demo-lg {
	min-height: 650px;
}

.layout-navbar-demo .rd-navbar-fixed .rd-navbar-panel {
	position: relative;
	z-index: 10;
}

.layout-navbar-demo .rd-navbar-fixed .rd-navbar-nav-wrap {
	position: absolute;
	z-index: 9;
}

.layout-navbar-demo .rd-navbar-fixed .rd-navbar-main-outer,
.layout-navbar-demo .rd-navbar-fixed .rd-navbar-main-element {
	position: static;
}

.layout-navbar-demo .rd-navbar-fixed .rd-navbar-search {
	position: static;
}

.layout-navbar-demo .rd-navbar-fixed .rd-navbar-panel .rd-navbar-search-toggle {
	position: static;
	z-index: 10;
}

.layout-navbar-demo .rd-navbar-fixed div.rd-navbar-block {
	top: -1px;
	right: 10px;
	white-space: nowrap;
}

.layout-navbar-demo .rd-navbar-fixed div.rd-navbar-block > * {
	display: inline-block;
	margin-top: 0;
	white-space: normal;
	vertical-align: middle;
}

.layout-navbar-demo .rd-navbar-fixed div.rd-navbar-block > * + * {
	margin-left: 8px;
}

.layout-navbar-demo .rd-navbar-fixed div.rd-navbar-block .rd-navbar-search-toggle {
	margin-top: 6px;
}

.layout-navbar-demo .rd-navbar-fixed div.rd-navbar-popup {
	position: absolute;
}

.layout-navbar-demo .rd-navbar-fixed.rd-navbar [class*='rd-navbar-fixed-element'] {
	position: absolute;
	z-index: 1000;
}

.layout-navbar-demo .rd-navbar-fixed.rd-navbar .rd-search {
	position: absolute;
	z-index: 1;
}

.layout-navbar-demo .rd-navbar-fixed.rd-navbar.rd-navbar-corporate .rd-search {
	position: relative;
}

.layout-navbar-demo .rd-navbar-fixed .rd-navbar-collapse-content {
	position: absolute;
	z-index: 1;
}

@media (min-width: 1200px) {
	.layout-navbar-demo {
		min-height: 550px;
	}
	.layout-navbar-demo.layout-navbar-demo-lg {
		min-height: 650px;
	}
}

.container + .layout-navbar-demo {
	margin-top: 20px;
}

.blog-layout-aside {
	padding: 4px 0;
	background: #f5f6fa;
}

.blog-layout-aside .rd-search .form-input {
	border-color: transparent;
}

.blog-layout-aside-item {
	padding: 25px 30px;
}

.blog-layout-aside-item .blog-layout-aside-title + * {
	margin-top: 15px;
}

.blog-layout-aside-title {
	font-size: 22px;
	line-height: 1.5;
}

* + .blog-layout-aside {
	margin-top: 55px;
}

@media (min-width: 768px) {
	* + .blog-layout-aside {
		margin-top: 70px;
	}
}

@media (min-width: 768px) and (max-width: 991.98px) {
	.blog-layout-aside {
		columns: 2;
		break-inside: avoid;
	}
	.blog-layout-aside-item {
		display: inline-block;
		width: 100%;
	}
}

@media (min-width: 992px) {
	.blog-layout {
		display: flex;
		align-items: flex-start;
		margin-left: -30px;
	}
	.blog-layout > * {
		margin-left: 30px;
	}
	.blog-layout-main {
		flex-grow: 1;
		max-width: 66.66667%;
	}
	.blog-layout-aside {
		flex-shrink: 0;
		max-width: 33.33333%;
	}
	* + .blog-layout-aside {
		margin-top: 0;
	}
}

@media (min-width: 1200px) {
	.blog-layout-aside-item {
		padding: 35px 40px;
	}
}

/*
*
* Timeline
*/
.timeline-classic {
	text-align: left;
}

.timeline-classic-item {
	position: relative;
	overflow: hidden;
	padding: 0 0 70px 35px;
	margin-bottom: -25px;
}

.timeline-classic-item:last-child {
	padding-bottom: 0;
	margin-bottom: 0;
}

.timeline-classic-item-image {
	width: 100%;
}

.timeline-classic-item-title {
	font-family: "Averia Libre";
	font-size: 24px;
	line-height: 1.2;
	font-weight: 300;
	letter-spacing: 0;
	text-transform: uppercase;
}

.thumbnail-classic-item-subtitle {
	font-size: 16px;
	line-height: 1.5;
	color: #29293a;
}

.timeline-classic-item-divider {
	position: absolute;
	top: 0;
	left: 0;
	display: flex;
	flex-grow: 1;
	flex-direction: column;
	align-items: center;
	padding-top: 25px;
}

.timeline-classic-item-divider::before {
	content: '';
	display: block;
	width: 15px;
	height: 15px;
	border: 2px solid #ef172c;
	border-radius: 50%;
}

.timeline-classic-item-divider::after {
	content: '';
	position: absolute;
	top: 40px;
	left: 50%;
	margin-left: -1px;
	width: 2px;
	height: 300vh;
	background: #ef172c;
	min-height: 100px;
}

* + .timeline-classic-item-main {
	margin-top: 20px;
}

.context-dark .timeline-classic-item-divider::before, .bg-gray-700 .timeline-classic-item-divider::before, .bg-gray-800 .timeline-classic-item-divider::before, .bg-primary .timeline-classic-item-divider::before, .bg-secondary .timeline-classic-item-divider::before, .bg-primary-darker .timeline-classic-item-divider::before {
	border-color: #fff;
}

.context-dark .timeline-classic-item-divider::after, .bg-gray-700 .timeline-classic-item-divider::after, .bg-gray-800 .timeline-classic-item-divider::after, .bg-primary .timeline-classic-item-divider::after, .bg-secondary .timeline-classic-item-divider::after, .bg-primary-darker .timeline-classic-item-divider::after {
	background: #fff;
}

.context-dark .thumbnail-classic-item-subtitle, .bg-gray-700 .thumbnail-classic-item-subtitle, .bg-gray-800 .thumbnail-classic-item-subtitle, .bg-primary .thumbnail-classic-item-subtitle, .bg-secondary .thumbnail-classic-item-subtitle, .bg-primary-darker .thumbnail-classic-item-subtitle {
	color: #fff;
}

@media (max-width: 575.98px) {
	.timeline-classic-item {
		max-width: 450px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (max-width: 767.98px) {
	.timeline-classic-item {
		flex-wrap: wrap;
	}
	.timeline-classic-item-main,
	.timeline-classic-item-aside {
		width: 100%;
	}
}

@media (min-width: 768px) {
	.timeline-classic-item {
		display: flex;
		padding-left: 0;
		padding-bottom: 90px;
	}
	.timeline-classic-item-aside {
		max-width: 33.33%;
	}
	.timeline-classic-item-main {
		max-width: 60%;
	}
	.timeline-classic-item-divider {
		position: relative;
		padding: 25px 20px 0;
	}
	.timeline-classic-item-title {
		font-size: 32px;
	}
	.thumbnail-classic-item-subtitle {
		font-size: 18px;
		line-height: 1.4;
	}
	* + .timeline-classic-item-main {
		margin-top: 0;
	}
}

@media (min-width: 992px) {
	.timeline-classic-item * + h4,
	.timeline-classic-item * + .heading-4 {
		margin-top: 20px;
	}
	.timeline-classic-item-title {
		font-size: 36px;
	}
	.thumbnail-classic-item-subtitle {
		font-size: 20px;
		line-height: 1.4;
	}
	.timeline-classic-item-aside {
		max-width: 37%;
	}
	.timeline-classic-item-main {
		max-width: 50%;
	}
}

@media (min-width: 1200px) {
	.timeline-classic-item-aside {
		max-width: 33.33%;
	}
	.timeline-classic-item-title {
		font-size: 48px;
	}
}

@media (min-width: 1600px) {
	.timeline-classic-item {
		padding-bottom: 125px;
	}
	.timeline-classic-item * + h4,
	.timeline-classic-item * + .heading-4 {
		margin-top: 30px;
	}
}

/*
*
* Careers
*/
.career-classic {
	text-align: left;
}

.career-classic-divider {
	border-bottom: 1px solid #aeb1be;
}

.career-classic-list {
	transform: translate3d(0, -10px, 0);
	margin-bottom: -10px;
	margin-left: -20px;
	margin-right: -20px;
}

.career-classic-list > * {
	margin-top: 10px;
	padding-left: 20px;
	padding-right: 20px;
}

.career-classic-list > li {
	display: inline-block;
	vertical-align: middle;
	white-space: nowrap;
}

.career-classic-list > li > * {
	display: inline-block;
	vertical-align: middle;
}

.career-classic-list > li > * + * {
	margin-left: 8px;
}

.career-classic-list .icon {
	font-size: 1.25em;
	color: #ef172c;
}

* + .career-classic-divider {
	margin-top: 10px;
}

* + .career-classic-list {
	margin-top: 15px;
}

@media (max-width: 575.98px) {
	.career-classic {
		max-width: 360px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (min-width: 768px) {
	* + .career-classic-divider {
		margin-top: 20px;
	}
	* + .career-classic-list {
		margin-top: 20px;
	}
}

/*
*
* Comments
*/
.comment-classic {
	display: flex;
	align-items: flex-start;
	text-align: left;
	padding-bottom: 20px;
	border-bottom: 1px solid #e8e9ee;
}

.comment-classic > * + * {
	margin-left: 20px;
}

.comment-classic-figure {
	position: relative;
	flex-shrink: 0;
	width: 48px;
	height: 48px;
}

.comment-classic-image {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	min-height: 100%;
	min-width: 100%;
	width: auto;
	height: auto;
	border-radius: 50%;
	max-width: none;
}

@supports (object-fit: cover) {
	.comment-classic-image {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		transform: none;
		object-fit: cover;
		object-position: center center;
	}
}

.comment-classic-main {
	flex-grow: 1;
}

.comment-classic-name {
	color: #ef172c;
}

.comment-classic-text {
	color: #29293a;
}

.comment-classic-meta {
	display: flex;
	align-items: center;
	justify-content: space-between;
}

.comment-classic-meta time {
	color: #15191f;
}

.comment-classic-reply {
	font-size: 24px;
	line-height: 1;
	color: #aeb1be;
}

.comment-classic-reply::before {
	content: '\f549';
	font-family: 'Material Design Icons';
}

.comment-classic-reply:hover {
	color: #ef172c;
}

* + .comment-classic-text {
	margin-top: 8px;
}

* + .comment-classic-meta {
	margin-top: 5px;
}

@media (min-width: 576px) {
	.comment-classic > * + * {
		margin-left: 25px;
	}
	.comment-classic-reply {
		font-size: 28px;
	}
}

.comment-classic-group .comment-classic-group {
	margin-left: 25px;
}

.comment-classic-group * + .comment-classic-group {
	margin-top: 30px;
}

* + .comment-classic-group {
	margin-top: 50px;
}

.comment-classic-group + .comment-classic-group {
	margin-top: 30px;
}

@media (min-width: 768px) {
	.comment-classic-group .comment-classic-group {
		margin-left: 75px;
	}
}

/*
*
* Jumbotron Classic
*/
.jumbotron-classic.bg-gray-700 h6,
.jumbotron-classic.bg-gray-700 .heading-6 {
	color: #fff;
}

.jumbotron-classic.parallax-container {
	background-position: 60% center;
}

.jumbotron-classic .parallax-content {
	width: 100%;
}

.jumbotron-classic-content {
	max-width: 600px;
	padding: 50px 0;
}

@media (max-width: 1199.98px) {
	.jumbotron-classic.parallax-container::before {
		content: '';
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;

		background: linear-gradient(to right, rgba(41, 41, 58, 0.6), rgba(41, 41, 58, 0.2));
	}
}

@media (min-width: 768px) {
	.jumbotron-classic-inner {
		padding: 120px 0 140px;
	}
}

@media (min-width: 1200px) {
	.jumbotron-classic-inner {
		display: flex;
		align-items: center;
		min-height: 45.41667vw;
	}
}

@media (min-width: 1600px) {
	.jumbotron-classic-content {
		padding: 200px 0 150px;
	}
}

.jumbotron-modern {
	position: relative;
	display: flex;
	text-align: center;
}

.jumbotron-modern-inner {
	position: relative;
	z-index: 1;
	display: flex;
	align-items: center;
	width: 100%;
	padding: 50px 0;
}

.jumbotron-modern-content {
	max-width: 770px;
	margin-left: auto;
	margin-right: auto;
}

@media (max-width: 767.98px) {
	.jumbotron-modern .form-layout-1 {
		display: inline-block;
		max-width: 360px;
	}
}

@media (max-width: 1199.98px) {
	.jumbotron-modern::before {
		content: '';
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		pointer-events: none;
		background: linear-gradient(to bottom, rgba(41, 41, 58, 0.4), rgba(41, 41, 58, 0));
	}
}

@media (min-width: 768px) {
	.jumbotron-modern-inner {
		padding: 100px 0 140px;
	}
}

@media (min-width: 1200px) {
	.jumbotron-modern-inner {
		min-height: 41.66667vw;
	}
}

.jumbotron-indigo-header {
	padding: 40px 0;
}

.jumbotron-indigo-main {
	padding: 10px 0 40px;
}

@media (min-width: 768px) {
	.jumbotron-indigo-header {
		padding: 50px 0;
	}
	.jumbotron-indigo-main {
		padding: 50px 0 185px;
	}
}

/*
*
* Page layout
*/
.page {
	position: relative;
	overflow: hidden;
	min-height: 100vh;
}

.page.fadeIn {
	animation-timing-function: ease-out;
}

.page.fadeOut {
	animation-timing-function: ease-in;
}

[data-x-mode] .page {
	opacity: 1;
}

html.boxed body {
	background: #f5f6fa url(../images/bg-pattern-boxed.png) repeat fixed;
}

@media (min-width: 1630px) {
	html.boxed .page {
		max-width: 1600px;
		margin-left: auto;
		margin-right: auto;
		box-shadow: 0 0 23px 0 rgba(1, 1, 1, 0.1);
	}
	html.boxed .rd-navbar-static {
		max-width: 1600px;
		margin-left: auto;
		margin-right: auto;
	}
	html.boxed .rd-navbar-static.rd-navbar--is-stuck {
		max-width: 1600px;
		width: 100%;
		left: calc(50% - 1600px);
		right: calc(50% - 1600px);
	}
}

.page-header-navbar {
	position: relative;
	z-index: 1080;
}

.page-header-navbar .rd-navbar-wrap {
	position: absolute;
	top: 0;
	left: 0;
	right: 0;
	z-index: 1080;
}

.rd-navbar-static-linked .page-header-absolute {
	position: relative;
}

.rd-navbar-static-linked .page-header-absolute .rd-navbar-wrap {
	position: absolute;
	left: 0;
	top: 0;
	right: 0;
	z-index: 1080;
}

.rd-navbar-static-linked .page-header-absolute .rd-navbar {
	background: transparent;
}

.rd-navbar-static-linked *:not(.layout-navbar-demo) > .page-header-absolute:last-child .rd-navbar-wrap {
	position: static;
}

.rd-navbar-static-linked *:not(.layout-navbar-demo) > .page-header-absolute:last-child .rd-navbar {
	background: #29293a;
}

/*
*
* Text styling
*/
.text-italic {
	font-style: italic;
}

.text-normal {
	font-style: normal;
}

.text-underline {
	text-decoration: underline;
}

.text-strike {
	text-decoration: line-through;
}

.font-weight-thin {
	font-weight: 100;
}

.font-weight-light {
	font-weight: 300;
}

.font-weight-regular {
	font-weight: 400;
}

.font-weight-medium {
	font-weight: 500;
}

.font-weight-sbold {
	font-weight: 600;
}

.font-weight-ubold {
	font-weight: 900;
}

.text-spacing-0 {
	letter-spacing: 0;
}

/*
*
* Offsets
*/
* + p,
* + .list-inline-comma {
	margin-top: 16px;
}

h3 + p, .heading-3 + p,
h3 + .p, .heading-3 + .p {
	margin-top: 18px;
}

h4 + p, .heading-4 + p,
h4 + .p, .heading-4 + .p {
	margin-top: 16px;
}

* + h1,
* + .heading-1 {
	margin-top: 15px;
}

h3 + h1, h3 + .heading-1,
.heading-3 + h1, .heading-3 + .heading-1 {
	margin-top: 5px;
}

h6 + h1,
h6 + .heading-1,
.heading-6 + h1,
.heading-6 + .heading-1 {
	margin-top: 10px;
}

* + h4,
* + .heading-4 {
	margin-top: 15px;
}

* + h5,
* + .heading-5 {
	margin-top: 15px;
}

h6 + p,
.heading-6 + p {
	margin-top: 22px;
}

p + h2,
p + .heading-2 {
	margin-top: 15px;
}

p + p {
	margin-top: 14px;
}

img + p {
	margin-top: 15px;
}

h3 + img {
	margin-top: 42px;
}

p + hr {
	margin-top: 35px;
}

* + .row {
	margin-top: 30px;
}

* + .big {
	margin-top: 20px;
}

* + .text-block {
	margin-top: 25px;
}

* + .button,
* + .button-outer {
	margin-top: 25px;
}

* + .list-sm {
	margin-top: 25px;
}

* + form.form-inline {
	margin-top: 18px;
}

* + form.rd-form-small {
	margin-top: 25px;
}

html * + .offset-top-1 {
	margin-top: 40px;
}

html * + .offset-top-2 {
	margin-top: 25px;
}

html * + .offset-top-3 {
	margin-top: 20px;
}

html * + .offset-top-4 {
	margin-top: 18px;
}

html .page * + .offset-top-5 {
	margin-top: 40px;
}

h3 + .row, .heading-3 + .row,
h3 + .owl-carousel, .heading-3 + .owl-carousel {
	margin-top: 40px;
}

.container + .container {
	margin-top: 35px;
}

.container + .section {
	margin-top: 25px;
}

.row + .row {
	margin-top: 35px;
}

.row + .button-lg {
	margin-top: 30px;
}

.list-sm + .group-xs {
	margin-top: 20px;
}

@media (max-width: 767.98px) {
	* + .button-outer-big {
		margin-top: 35px;
	}
}

@media (min-width: 768px) {
	* + p,
	* + .list-inline-comma {
		margin-top: 20px;
	}
	* + .big {
		margin-top: 25px;
	}
	* + .button,
	* + .button-outer {
		margin-top: 34px;
	}
	* + .row {
		margin-top: 40px;
	}
	* + .text-block {
		margin-top: 30px;
	}
	.container + .section {
		margin-top: 30px;
	}
	.row + .button-lg {
		margin-top: 45px;
	}
	html * + .offset-top-2 {
		margin-top: 60px;
	}
}

@media (min-width: 992px) {
	* + h1,
	* + .heading-1 {
		margin-top: 22px;
	}
	h3 + p, .heading-3 + p,
	h3 + .p, .heading-3 + .p {
		margin-top: 24px;
	}
	h3 + .row, .heading-3 + .row,
	h3 + .owl-carousel, .heading-3 + .owl-carousel {
		margin-top: 55px;
	}
	html * + .offset-top-1 {
		margin-top: 60px;
	}
	html * + .offset-top-3 {
		margin-top: 30px;
	}
	html * + .offset-top-4 {
		margin-top: 24px;
	}
	html .page * + .offset-top-5 {
		margin-top: 60px;
	}
	.progress-linear + .button {
		margin-top: 55px;
	}
	.row + .group {
		margin-top: 45px;
	}
}

@media (min-width: 1200px) {
	* + .button,
	* + .button-outer {
		margin-top: 40px;
	}
	.container + .button,
	.row + .button,
	.container + .button-outer,
	.row + .button-outer {
		margin-top: 70px;
	}
	* + .rd-form {
		margin-top: 40px;
	}
	h3 + p, .heading-3 + p,
	h3 + .p, .heading-3 + .p {
		margin-top: 30px;
	}
	html * + .offset-top-1 {
		margin-top: 70px;
	}
	.container + .container {
		margin-top: 60px;
	}
	.row + .row {
		margin-top: 60px;
	}
	* + .offset-xl-50 {
		margin-top: 50px;
	}
	* + .offset-xl-75 {
		margin-top: 75px;
	}
}

@media (min-width: 1600px) {
	h3 + .row, .heading-3 + .row,
	h3 + .owl-carousel, .heading-3 + .owl-carousel {
		margin-top: 75px;
	}
	html * + .offset-top-1 {
		margin-top: 144px;
	}
	html * + .offset-top-2 {
		margin-top: 75px;
	}
	.row + .button-lg {
		margin-top: 70px;
	}
}

.row-0 {
	margin-bottom: 0px;
}

.row-0:empty {
	margin-bottom: 0;
}

.row-0 > * {
	margin-bottom: 0px;
}

.row-10 {
	margin-bottom: -10px;
}

.row-10:empty {
	margin-bottom: 0;
}

.row-10 > * {
	margin-bottom: 10px;
}

.row-x-10 {
	margin-bottom: -10px;
	margin-left: -5px;
	margin-right: -5px;
}

.row-x-10:empty {
	margin-bottom: 0;
}

.row-x-10 > * {
	margin-bottom: 10px;
}

.row-x-10 > [class*='col'] {
	padding-left: 5px;
	padding-right: 5px;
}

.row-20 {
	margin-bottom: -20px;
}

.row-20:empty {
	margin-bottom: 0;
}

.row-20 > * {
	margin-bottom: 20px;
}

.row-30 {
	margin-bottom: -30px;
}

.row-30:empty {
	margin-bottom: 0;
}

.row-30 > * {
	margin-bottom: 30px;
}

.row-35 {
	margin-bottom: -35px;
}

.row-35:empty {
	margin-bottom: 0;
}

.row-35 > * {
	margin-bottom: 35px;
}

.row-40 {
	margin-bottom: -40px;
}

.row-40:empty {
	margin-bottom: 0;
}

.row-40 > * {
	margin-bottom: 40px;
}

.row-50 {
	margin-bottom: -50px;
}

.row-50:empty {
	margin-bottom: 0;
}

.row-50 > * {
	margin-bottom: 25px;
}

.row-60 {
	margin-bottom: -50px;
}

.row-60:empty {
	margin-bottom: 0;
}

.row-60 > * {
	margin-bottom: 50px;
}

.row-45 {
	margin-bottom: -45px;
}

.row-45:empty {
	margin-bottom: 0;
}

.row-45 > * {
	margin-bottom: 45px;
}

@media (min-width: 768px) {
	.row-md-50 {
		margin-bottom: -50px;
	}
	.row-md-50:empty {
		margin-bottom: 0;
	}
	.row-md-50 > * {
		margin-bottom: 50px;
	}
}

@media (min-width: 992px) {
	.row-md-30 {
		margin-bottom: -30px;
	}
	.row-md-30:empty {
		margin-bottom: 0;
	}
	.row-md-30 > * {
		margin-bottom: 30px;
	}
}

@media (min-width: 1600px) {
	.row-xxl-70 {
		margin-bottom: -70px;
	}
	.row-xxl-70:empty {
		margin-bottom: 0;
	}
	.row-xxl-70 > * {
		margin-bottom: 70px;
	}
}

/*
*
* Sections
*/
.section-xs {
	padding: 30px 0;
}

.section-sm {
	padding: 35px 0;
}

.section-sm.section-first {
	padding-top: 65px;
}

.section-sm.section-last {
	padding-bottom: 80px;
}

.section-md,
.section-lg,
.section-xl {
	padding: 50px 0;
}

.section-1 {
	padding: 35px 0;
}

.section-collapse + .section-collapse {
	padding-top: 0;
}

.section-collapse:last-child {
	padding-bottom: 0;
}

html [class*='section-'].section-bottom-0 {
	padding-bottom: 0;
}

@media (min-width: 576px) {
	.section-xs {
		padding: 40px 0;
	}
}

@media (min-width: 768px) {
	.section-sm {
		padding: 45px 0;
	}
	.section-sm.section-first {
		padding-top: 90px;
	}
	.section-sm.section-last {
		padding-bottom: 90px;
	}
	.section-md {
		padding: 60px 0;
	}
	.section-lg {
		padding: 72px 0;
	}
	.section-lg.section-first {
		padding-top: 100px;
	}
	.section-lg.section-last {
		padding-bottom: 100px;
	}
	.section-xl {
		padding: 80px 0;
	}
	.section-1 {
		padding: 60px 0;
	}
}

@media (min-width: 992px) {
	.section-md {
		padding: 60px 0 70px;
	}
	.section-xl {
		padding: 100px 0;
	}
	.section-1 {
		padding: 80px 0;
	}
}

@media (min-width: 1200px) {
	.section-sm {
		padding: 60px 0;
	}
	.section-sm.section-first {
		padding-top: 80px;
	}
	.section-sm.section-last {
		padding-bottom: 80px;
	}
}

@media (min-width: 1600px) {
	.section-sm.section-first {
		padding-top: 120px;
	}
	.section-sm.section-last {
		padding-bottom: 120px;
	}
	.section-md {
		padding: 85px 0 95px;
	}
	.section-lg {
		padding: 120px 0;
	}
	.section-lg.section-first {
		padding-top: 120px;
	}
	.section-lg.section-last {
		padding-bottom: 120px;
	}
	.section-xl {
		padding: 160px 0;
	}
	.section-1 {
		padding: 90px 0 100px;
	}
}

.section-single {
	display: flex;
}

.section-single.bg-gray-800 {
	color: #fff;
}

.section-single * + .rd-mailform-wrap {
	margin-top: 35px;
}

.section-single * + .countdown-wrap {
	margin-top: 30px;
}

.section-single .countdown-wrap + * {
	margin-top: 35px;
}

.section-single-dummy {
	visibility: hidden;
	pointer-events: none;
}

.section-single-header {
	padding: calc(1em + 3vh) 0 calc(1em + 2vh);
}

.section-single-main {
	padding: calc(1em + 4vh) 0;
}

.section-single-footer {
	padding: calc(1em + 2vh) 0 calc(1em + 3vh);
}

.section-single-inner {
	position: relative;
	z-index: 1;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: space-between;
	width: 100%;
	min-height: 100vh;
	padding-top: 6vh;
}

.section-single-inner > * {
	width: 100%;
}

@media (max-width: 575.98px) {
	.section-single .section-single-main-content {
		max-width: 240px;
		margin-left: auto;
		margin-right: auto;
	}
}

@media (max-width: 767.98px) {
	.section-single .button-lg {
		font-size: 15px;
		padding-left: 25px;
		padding-right: 25px;
	}
}

@media (min-width: 768px) {
	.section-single::before {
		display: none;
	}
	.section-single-inner {
		padding-top: 7vh;
	}
}

@media (min-width: 1200px) {
	.section-single * + .countdown-wrap {
		margin-top: 50px;
	}
	.section-single .countdown-wrap + * {
		margin-top: 50px;
	}
}

.section-overlap {
	position: relative;
	padding: 40px 0;
}

.section-overlap .row {
	flex-wrap: nowrap;
	flex-direction: column;
	align-items: flex-end;
}

.section-overlap [class*='col'] {
	flex-basis: auto;
}

.section-overlap * + [class*='col'] {
	margin-top: 10px;
}

.section-overlap * + .col-offset-1 {
	margin-top: 20px;
}

.section-overlap-image {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background-size: cover;
	background-position: center center;
	background-repeat: no-repeat;
}

.section-overlap-content {
	position: relative;
	z-index: 1;
}

@media (max-width: 767.98px) {
	.section-overlap-content .container {
		padding: 20px 15px;
		background: linear-gradient(to right, rgba(255, 255, 255, 0.9), rgba(255, 255, 255, 0.8));
	}
	.section-overlap-content .container > * {
		max-width: 380px;
	}
}

@media (max-width: 767.98px) and (min-width: 576px) {
	.section-overlap-content .container {
		padding: 40px 50px;
	}
}

@media (min-width: 768px) and (max-width: 991.98px) {
	.section-overlap-image::before {
		content: '';
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		z-index: 1;
		pointer-events: none;
		background: linear-gradient(to left, rgba(245, 246, 250, 0.4), rgba(245, 246, 250, 0));
	}
}

@media (min-width: 768px) {
	.section-overlap {
		padding: 75px 0;
	}
	.section-overlap * + [class*='col'] {
		margin-top: 20px;
	}
	.section-overlap * + .col-offset-1 {
		margin-top: 40px;
	}
	.section-overlap-image {
		background-position: 80% 50%;
		width: calc(50% - 60px + 35px);
	}
}

@media (min-width: 992px) {
	.section-overlap {
		padding: 100px 0;
	}
	.section-overlap-image {
		width: calc(50% - -80px - 45px);
	}
	.ie-10 .section-overlap .col-lg-7,
	.ie-11 .section-overlap .col-lg-7 {
		max-width: 64%;
	}
}

@media (min-width: 1200px) {
	.section-overlap-image {
		width: calc(50% - -100px - 15px);
	}
}

@media (min-width: 1600px) {
	.section-overlap {
		padding: 140px 0;
	}
}

.section-halfscreen {
	position: relative;
}

.section-halfscreen-inner {
	padding: 40px 0;
}

.section-halfscreen-image {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background-size: cover;
	background-position: center center;
	background-repeat: no-repeat;
}

.section-halfscreen-image::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1;
	pointer-events: none;
	background: linear-gradient(to right, rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0.4));
}

.section-halfscreen-content {
	position: relative;
	z-index: 1;
}

@media (max-width: 767.98px) {
	.section-halfscreen-content {
		max-width: 360px;
	}
}

@media (min-width: 576px) and (max-width: 767.98px) {
	.section-halfscreen-image::before {
		opacity: .8;
	}
}

@media (min-width: 768px) {
	.section-halfscreen-inner {
		padding: 75px 0;
	}
	.section-halfscreen-image {
		background-position: 45% 50%;
		left: auto;
		width: calc(50% - 60px + 35px);
	}
	.section-halfscreen-image::before {
		display: none;
	}
}

@media (min-width: 992px) {
	.section-halfscreen-inner {
		padding: 100px 0;
	}
	.section-halfscreen-image {
		width: 50%;
	}
}

@media (min-width: 1200px) {
	.section-halfscreen {
		display: flex;
	}
	.section-halfscreen-inner {
		display: flex;
		align-items: center;
		width: 100%;
		min-height: 35.41667vw;
		padding: 90px 0;
	}
	.section-halfscreen-content {
		width: 100%;
	}
}

/*
*
* Grid modules
*/
.range {
	display: flex;
	flex-wrap: wrap;
}

.cell-inner {
	width: 100%;
	padding-right: 15px;
	padding-left: 15px;
}

.range > [class*='cell'] {
	position: relative;
	width: 100%;
	min-height: 1px;
}

.range > [class*='cell'] > .row {
	margin: 0;
}

.range > [class*='cell'].container {
	padding: 0;
}

.range > [class*='col'] {
	padding: 0;
}

@media (min-width: 576px) {
	.cell-sm-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.cell-sm-6 .cell-inner {
		max-width: 270px;
	}
	.range > [class*='cell-sm']:nth-child(odd) .cell-inner {
		margin-left: auto;
	}
	.range.flex-sm-row-reverse > [class*='cell-sm']:nth-child(odd) .cell-inner {
		margin-left: 0;
	}
	.range.flex-sm-row-reverse > [class*='cell-sm']:nth-child(even) .cell-inner {
		margin-left: auto;
	}
	.range > [class*='cell-sm'].container {
		margin: 0;
	}
}

@media (min-width: 768px) {
	.range > [class*='cell-md']:nth-child(odd) .cell-inner {
		margin-left: auto;
	}
	.range.flex-md-row-reverse > [class*='cell-md']:nth-child(odd) .cell-inner {
		margin-left: 0;
	}
	.range.flex-md-row-reverse > [class*='cell-md']:nth-child(even) .cell-inner {
		margin-left: auto;
	}
	.range > [class*='cell-md'].container {
		margin: 0;
	}
}

@media (min-width: 992px) {
	[class*='cell-lg'] > .row > [class*='col'] {
		flex-basis: 100%;
	}
	.cell-lg-5 {
		flex: 0 0 calc(50% - 80px);
		max-width: calc(50% - 80px);
	}
	.cell-lg-5 .cell-inner {
		max-width: 400px;
	}
	.cell-lg-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.cell-lg-6 .cell-inner {
		max-width: 480px;
	}
	.range > [class*='cell-lg']:nth-child(odd) .cell-inner {
		margin-left: auto;
	}
	.range.flex-lg-row-reverse > [class*='cell-lg']:nth-child(odd) .cell-inner {
		margin-left: 0;
	}
	.range.flex-lg-row-reverse > [class*='cell-lg']:nth-child(even) .cell-inner {
		margin-left: auto;
	}
	.range > [class*='cell-lg'].container {
		margin: 0;
	}
}

@media (min-width: 1200px) {
	.range > [class*='cell-xl'].container {
		margin: 0;
	}
	.range > [class*='cell-xl']:nth-child(odd) .cell-inner {
		margin-left: auto;
	}
	.range .cell-inner {
		flex-basis: 100%;
	}
	.cell-xl-7 {
		flex: 0 0 calc(50% - -100px);
		max-width: calc(50% - -100px);
	}
	.cell-xl-7 .cell-inner {
		max-width: 700px;
	}
	.cell-lg-6,
	.cell-xl-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.cell-lg-6 .cell-inner,
	.cell-xl-6 .cell-inner {
		max-width: 600px;
	}
	.cell-xl-5 {
		flex: 0 0 calc(50% - 100px);
		max-width: calc(50% - 100px);
	}
	.cell-xl-5 .cell-inner {
		max-width: 500px;
	}
	.cell-xl-4 {
		flex: 0 0 calc(50% - 200px);
		max-width: calc(50% - 200px);
	}
	.cell-xl-4 .cell-inner {
		max-width: 400px;
	}
}

@media (min-width: 1600px) {
	.cell-xxl-6 {
		flex: 0 0 50%;
		max-width: 50%;
	}
	.cell-xxl-6 .cell-inner {
		max-width: 600px;
	}
}

/*
*
* Backgrounds
*/
.context-dark, .bg-gray-700, .bg-gray-800, .bg-primary, .bg-secondary, .bg-primary-darker,
.context-dark h1,
.bg-gray-700 h1,
.bg-gray-800 h1,
.bg-primary h1,
.bg-secondary h1,
.bg-primary-darker h1, .context-dark h2, .bg-gray-700 h2, .bg-gray-800 h2, .bg-primary h2, .bg-secondary h2, .bg-primary-darker h2, .context-dark h3, .bg-gray-700 h3, .bg-gray-800 h3, .bg-primary h3, .bg-secondary h3, .bg-primary-darker h3, .context-dark h4, .bg-gray-700 h4, .bg-gray-800 h4, .bg-primary h4, .bg-secondary h4, .bg-primary-darker h4, .context-dark h5, .bg-gray-700 h5, .bg-gray-800 h5, .bg-primary h5, .bg-secondary h5, .bg-primary-darker h5, .context-dark h6, .bg-gray-700 h6, .bg-gray-800 h6, .bg-primary h6, .bg-secondary h6, .bg-primary-darker h6, .context-dark [class^='heading-'], .bg-gray-700 [class^='heading-'], .bg-gray-800 [class^='heading-'], .bg-primary [class^='heading-'], .bg-secondary [class^='heading-'], .bg-primary-darker [class^='heading-'] {
	color: #d83634;
}

.context-dark p a, .bg-gray-700 p a, .bg-gray-800 p a, .bg-primary p a, .bg-secondary p a, .bg-primary-darker p a {
	color: inherit;
}

.context-dark p a:hover, .bg-gray-700 p a:hover, .bg-gray-800 p a:hover, .bg-primary p a:hover, .bg-secondary p a:hover, .bg-primary-darker p a:hover {
	color: #ef172c;
}

.context-dark .big, .bg-gray-700 .big, .bg-gray-800 .big, .bg-primary .big, .bg-secondary .big, .bg-primary-darker .big {
	color: #fff;
}

.context-dark .brand .brand-logo-dark, .bg-gray-700 .brand .brand-logo-dark, .bg-gray-800 .brand .brand-logo-dark, .bg-primary .brand .brand-logo-dark, .bg-secondary .brand .brand-logo-dark, .bg-primary-darker .brand .brand-logo-dark {
	display: none;
}

.context-dark .brand .brand-logo-light, .bg-gray-700 .brand .brand-logo-light, .bg-gray-800 .brand .brand-logo-light, .bg-primary .brand .brand-logo-light, .bg-secondary .brand .brand-logo-light, .bg-primary-darker .brand .brand-logo-light {
	display: block;
}

.context-dark .footer-minimal-inner .rights a:hover, .bg-gray-700 .footer-minimal-inner .rights a:hover, .bg-gray-800 .footer-minimal-inner .rights a:hover, .bg-primary .footer-minimal-inner .rights a:hover, .bg-secondary .footer-minimal-inner .rights a:hover, .bg-primary-darker .footer-minimal-inner .rights a:hover {
	color: #fff;
}

/**
* Light Backgrounds
*/
.bg-default {
	background-color: #fff;
}

.bg-default:not([style*="background-"]) + .bg-default:not([style*="background-"]) {
	padding-top: 0;
}

.bg-gray-100 {
	background-color: #e1e0dd;
}

.bg-gray-101 {
	background-color: #fffef7;
}

.bg-gray-100:not([style*="background-"]) + .bg-gray-100:not([style*="background-"]) {
	padding-top: 0;
}

.bg-gray-200 {
	background-color: #e8e9ee;
}

.bg-gray-200:not([style*="background-"]) + .bg-gray-200:not([style*="background-"]) {
	padding-top: 0;
}

/**
* Dark Backgrounds
*/
.bg-gray-700 {
	color: #000000;
	background-color: #e1e0dd;
}

.bg-gray-700:not([style*="background-"]) + .bg-gray-700:not([style*="background-"]) {
	padding-top: 0;
}

.bg-gray-700 a {
	color: inherit;
}

.bg-gray-700 a:hover {
	color: #fff;
}

.bg-gray-700 p a:hover {
	color: #fff;
}

.bg-gray-800 {
	color: #e1e0dd;
	background-color: #15191f;
}

.bg-gray-800:not([style*="background-"]) + .bg-gray-800:not([style*="background-"]) {
	padding-top: 0;
}

.bg-gray-800 .rights {
	color: #e1e0dd;
}

/** 
* Accent Backgrounds
*/
.bg-primary {
	background-color: #ef172c;
}

.bg-primary:not([style*="background-"]) + .bg-primary:not([style*="background-"]) {
	padding-top: 0;
}

.bg-secondary {
	background-color: #353535;
}

.bg-rip {
	background-color: #151a20;
}


.bg-secondary:not([style*="background-"]) + .bg-secondary:not([style*="background-"]) {
	padding-top: 0;
}

.bg-primary-darker {
	background-color: #3c121c;
}

.bg-primary-darker:not([style*="background-"]) + .bg-primary-darker:not([style*="background-"]) {
	padding-top: 0;
}

/**
* Background Image
*/
[class*='bg-'],
.novi-background {
	background-size: cover;
	background-position: center bottom;
}

@media (max-width: 1199.98px) {
	.bg-image-light {
		position: relative;
	}
	.bg-image-light::before {
		content: '';
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		background: rgba(255, 255, 255, 0.1);
	}
}

.bg-image-1 {
	position: relative;
	background-position: 30% 100%;
}

.bg-image-1::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: #29293a;
	opacity: .6;
}

.bg-image-1 > * {
	position: relative;
	z-index: 1;
}

@media (min-width: 576px) {
	.bg-image-1 {
		background-position: 72% 100%;
	}
	.bg-image-1::before {
		opacity: .2;
	}
}

@media (min-width: 768px) {
	.bg-image-1 {
		background-position: 54% 100%;
	}
	.bg-image-1::before {
		display: none;
	}
}

@media (min-width: 992px) {
	html:not(.tablet):not(.mobile) .bg-fixed {
		background-attachment: fixed;
	}
}

/*
*
* Utilities custom
*/
.height-fill {
	position: relative;
	display: flex;
	flex-direction: column;
	align-items: stretch;
}

.height-fill > * {
	flex-grow: 1;
	flex-shrink: 0;
}

.object-inline {
	white-space: nowrap;
}

.object-inline > * {
	display: inline-block;
	min-width: 20px;
	vertical-align: top;
	white-space: normal;
}

.object-inline.wow span {
	display: inline-block;
}

.object-inline > * + * {
	margin-left: 11px;
}

.wow-outer .object-inline span {
	display: inline-block;
}

.oh {
	position: relative;
	overflow: hidden;
}

.text-decoration-lines {
	position: relative;
	overflow: hidden;
	width: 100%;
	text-align: center;
}

.text-decoration-lines-content {
	position: relative;
	display: inline-block;
	padding: 0 20px;
}

.text-decoration-lines-content::before, .text-decoration-lines-content::after {
	content: '';
	position: absolute;
	height: 1px;
	background: #aeb1be;
	top: 50%;
	width: 100vw;
}

.text-decoration-lines-content::before {
	left: 0;
	transform: translate3d(-100%, 0, 0);
}

.text-decoration-lines-content::after {
	right: 0;
	transform: translate3d(100%, 0, 0);
}

* + .text-decoration-lines {
	margin-top: 30px;
}

.text-block > * {
	margin-left: .125em;
	margin-right: .125em;
}

@media (min-width: 992px) {
	.offset-right-1 {
		margin-right: 40px;
	}
}

.col-inner {
	padding-left: 10px;
	padding-right: 10px;
}

@media (min-width: 768px) {
	.col-inner {
		padding-left: 30px;
	}
}

@media (min-width: 992px) {
	.col-inner {
		padding-left: 0;
	}
}

.banner {
	background-position: center center;
	background-size: cover;
}

.phone-frame {
	max-width: 296px;
	padding: 0 5px;
	margin-left: auto;
	margin-right: auto;
	box-shadow: -46.037px 40.02px 21px 0px rgba(0, 0, 0, 0.02);
}

@media (max-width: 767.98px) {
	.phone-frame {
		display: none;
	}
}

.tip-mark {
	display: inline-flex;
	align-items: center;
	justify-content: center;
	width: 2em;
	height: 2em;
	padding-left: 2px;
	margin-bottom: 5px;
	font-size: 12px;
	line-height: 2em;
	vertical-align: middle;
	text-align: center;
	border-radius: 50%;
	border: 1px solid #e8e9ee;
	color: #ef172c;
}

/*
*
* Insets
*/
@media (min-width: 576px) {
	.inset-left-1 {
		padding-left: 10px;
	}
}

@media (min-width: 768px) {
	.inset-left-1 {
		padding-left: 30px;
	}
}

@media (min-width: 992px) {
	.inset-left-1 {
		padding-left: 0;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.inset-left-2 {
		padding-left: 30px;
	}
}

@media (min-width: 576px) {
	.inset-right-1 {
		padding-right: 20px;
	}
}

@media (min-width: 768px) {
	.inset-right-1 {
		padding-right: 30px;
	}
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.inset-right-1 {
		padding-right: 0;
	}
}

@media (min-width: 992px) {
	.inset-right-2 {
		padding-right: 30px;
	}
}

@media (min-width: 1200px) {
	.inset-right-2 {
		padding-right: 0;
	}
}

@media (min-width: 992px) {
	.inset-right-3 {
		padding-left: 5px;
	}
}

@media (min-width: 1200px) {
	.inset-right-3 {
		padding-right: 0;
	}
}

/*
*
* Animate.css
*/
.animated {
	animation-duration: 1s;
	animation-fill-mode: both;
	opacity: 1;
}

.animated.infinite {
	animation-iteration-count: infinite;
}

.animated.hinge {
	animation-duration: 2s;
}

html:not(.lt-ie10) .not-animated {
	opacity: 0;
}

@keyframes fadeIn {
	0% {
		opacity: 0;
	}
	100% {
		opacity: 1;
	}
}

.fadeIn {
	animation-name: fadeIn;
}

@keyframes fadeInUp {
	0% {
		opacity: 0;
		transform: translate3d(0, 100%, 0);
	}
	100% {
		opacity: 1;
		transform: none;
	}
}

.fadeInUp {
	animation-name: fadeInUp;
}

@keyframes fadeInDown {
	0% {
		opacity: 0;
		transform: translate3d(0, -100%, 0);
	}
	100% {
		opacity: 1;
		transform: none;
	}
}

.fadeInDown {
	animation-name: fadeInDown;
}

@keyframes fadeInLeft {
	0% {
		opacity: 0;
		transform: translate3d(-100%, 0, 0);
	}
	100% {
		opacity: 1;
		transform: none;
	}
}

.fadeInLeft {
	animation-name: fadeInLeft;
}

@keyframes fadeInRight {
	0% {
		opacity: 0;
		transform: translate3d(100%, 0, 0);
	}
	100% {
		opacity: 1;
		transform: none;
	}
}

.fadeInRight {
	animation-name: fadeInRight;
}

@keyframes fadeOut {
	0% {
		opacity: 1;
	}
	100% {
		opacity: 0;
	}
}

.fadeOut {
	animation-name: fadeOut;
}

@keyframes slideInDown {
	0% {
		transform: translate3d(0, -100%, 0);
		visibility: visible;
	}
	100% {
		transform: translate3d(0, 0, 0);
	}
}

.slideInDown {
	animation-name: slideInDown;
}

@keyframes slideInUp {
	0% {
		transform: translate3d(0, 100%, 0);
		visibility: visible;
	}
	100% {
		transform: translate3d(0, 0, 0);
	}
}

.slideInUp {
	animation-name: slideInUp;
}

@keyframes slideInLeft {
	0% {
		transform: translate3d(-100%, 0, 0);
		visibility: visible;
	}
	100% {
		transform: translate3d(0, 0, 0);
	}
}

.slideInLeft {
	animation-name: slideInLeft;
}

@keyframes slideInRight {
	0% {
		transform: translate3d(100%, 0, 0);
		visibility: visible;
	}
	100% {
		transform: translate3d(0, 0, 0);
	}
}

.slideInRight {
	animation-name: slideInRight;
}

@keyframes slideOutDown {
	0% {
		transform: translate3d(0, 0, 0);
	}
	100% {
		visibility: hidden;
		transform: translate3d(0, 100%, 0);
	}
}

.slideOutDown {
	animation-name: slideOutDown;
}

@keyframes scaleInY {
	0% {
		top: 0;
		bottom: 100%;
	}
	50% {
		transform: scale3d(1, 1, 1);
	}
	100% {
		top: 100%;
		bottom: auto;
		transform: scale3d(1, 0, 1);
	}
}

@keyframes scaleFadeIn {
	0% {
		height: 0;
	}
	100% {
		height: 100%;
	}
}

.scaleFadeIn {
	display: flex;
	overflow: hidden;
	animation-name: scaleFadeIn;
	animation-timing-function: cubic-bezier(0.25, 0.46, 0.45, 0.94);
}

.scaleFadeInWrap {
	display: flex;
	align-items: stretch;
}

.wow-outer {
	position: relative;
	overflow: hidden;
}

@keyframes scaleInVertical {
	0% {
		transform: scale3d(1, 0, 1);
	}
	100% {
		transform: scale3d(1, 1, 1);
	}
}

.scaleInVertical {
	animation-name: scaleInVertical;
}

@keyframes fadeInLeftSmall {
	0% {
		opacity: 0;
		transform: translate3d(-20px, 0, 0);
	}
	100% {
		opacity: 1;
		transform: none;
	}
}

.fadeInLeftSmall {
	animation-name: fadeInLeftSmall;
}

@keyframes fadeInUpSmall {
	0% {
		opacity: 0;
		transform: translate3d(0, 20px, 0);
	}
	100% {
		opacity: 1;
		transform: none;
	}
}

.fadeInUpSmall {
	animation-name: fadeInUpSmall;
}

@keyframes fadeSlideInDown {
	0% {
		opacity: 0;
		transform: translate3d(0, -50%, 0);
		visibility: visible;
	}
	10% {
		opacity: 1;
	}
	100% {
		transform: translate3d(0, 0, 0);
	}
}

.fadeSlideInDown {
	animation-name: fadeSlideInDown;
}

@keyframes fadeSlideInUp {
	0% {
		opacity: 0;
		transform: translate3d(0, 50%, 0);
		visibility: visible;
	}
	10% {
		opacity: 1;
	}
	100% {
		transform: translate3d(0, 0, 0);
	}
}

.fadeSlideInUp {
	animation-name: fadeSlideInUp;
}

.wow {
	backface-visibility: hidden;
}

/*
*
* Preloader
*/
.preloader {
	position: fixed;
	left: 0;
	top: 0;
	bottom: 0;
	right: 0;
	z-index: 10000;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	padding: 20px;
	transition: .3s all ease;
	pointer-events: none;
	backface-visibility: hidden;
}

.preloader::before, .preloader::after {
	content: '';
	position: absolute;
	left: 0;
	right: 0;
	transition: .2s linear;
	transform: translateY(0);
	pointer-events: none;
}

.preloader::before {
	top: 0;
	bottom: 50%;
	background: #fff;
}

.preloader::after {
	top: 50%;
	bottom: 0;
	background: #f5f6fa;
}

.preloader.loaded::before, .preloader.loaded::after {
	transition: .4s linear;
}

.preloader.loaded::before {
	transform: translateY(-100%);
}

.preloader.loaded::after {
	transform: translateY(100%);
}

.preloader.loaded .preloader-body {
	opacity: 0;
	visibility: hidden;
	transition: 0s;
}

[data-x-mode="true"] .preloader {
	display: none;
}

.preloader-body {
	position: absolute;
	top: 50%;
	transform: translate3d(0, -50%, 0);
	left: 0;
	right: 0;
	z-index: 10;
	text-align: center;
	transition: 0s .2s;
}

#loadingProgressG {
	width: 100vw;
	height: 5px;
	overflow: hidden;
	background: #e8e9ee;
	border-radius: 0px;
	margin: auto;
}

.loadingProgressG {
	background: #15191f;
	margin-top: 0;
	margin-left: -100vw;
	animation-name: bounce_loadingProgressG;
	animation-duration: 2.5s;
	animation-iteration-count: infinite;
	animation-timing-function: linear;
	width: 100vw;
	height: 5px;
	transition: .5s;
}

@keyframes bounce_loadingProgressG {
	0% {
		margin-left: -100vw;
	}
	100% {
		margin-left: 100vw;
	}
}

/*
*
* ToTop
*/
.ui-to-top {
	position: fixed;
	right: 15px;
	bottom: 15px;
	z-index: 100;
	width: 48px;
	height: 48px;
	border-radius: 4px;
	color: #fff;
	background: #ef172c;
	overflow: hidden;
	text-align: center;
	text-decoration: none;
	transition: transform 0.45s ease-in-out, background 0.3s cubic-bezier(0.2, 1, 0.3, 1);
	transform: translate3d(0, 100px, 0);
}

.ui-to-top::before, .ui-to-top::after {
	content: '\f239';
	font-family: 'Material Design Icons';
	font-size: 20px;
	line-height: 48px;
	vertical-align: middle;
	transition: transform 0.3s cubic-bezier(0.2, 1, 0.3, 1), opacity 0.3s cubic-bezier(0.2, 1, 0.3, 1);
}

.ui-to-top::before {
	display: block;
}

.ui-to-top::after {
	position: absolute;
	width: 100%;
	top: 50%;
	left: 0;
	opacity: 0;
	transform: translate3d(0, 0, 0);
}

.ui-to-top:hover::before {
	opacity: 0;
	transform: translate3d(0, -30%, 0);
}

.ui-to-top:hover::after {
	opacity: 1;
	transform: translate3d(0, 0, 0) translateY(-50%);
}

.ui-to-top:hover {
	color: #fff;
	background: #353535;
	text-decoration: none;
}

.ui-to-top:focus {
	color: #fff;
}

.ui-to-top.active {
	transform: translate3d(0, 0, 0);
}

html.mobile .ui-to-top,
html.tablet .ui-to-top {
	display: none !important;
}

@media (min-width: 576px) {
	.ui-to-top {
		right: 40px;
		bottom: 40px;
	}
}

/*
*
* RD Navbar
*/
@keyframes rd-navbar-slide-down {
	0% {
		transform: translateY(-100%);
	}
	100% {
		transform: translateY(0);
	}
}

@keyframes rd-navbar-slide-up {
	0% {
		transform: translateY(0);
	}
	100% {
		transform: translateY(-100%);
	}
}

.rd-navbar-wrap, .rd-navbar,
.rd-menu,
.rd-navbar-nav,
.rd-navbar-panel, .rd-navbar-static .rd-menu, .rd-navbar-fixed .rd-navbar-nav-wrap, .rd-navbar-fixed .rd-navbar-submenu {
	transition: 0.35s all cubic-bezier(0.65, 0.05, 0.36, 1);
}

.rd-navbar--no-transition, .rd-navbar--no-transition * {
	transition: none !important;
}

.rd-navbar,
.rd-navbar.rd-navbar--is-clone {
	display: none;
}

.rd-navbar.rd-navbar-fixed + .rd-navbar.rd-navbar--is-clone,
.rd-navbar.rd-navbar-sidebar + .rd-navbar.rd-navbar--is-clone {
	display: none;
}

.rd-navbar {
	display: none;
	background: #fff;
}

.rd-navbar-outer {
	position: relative;
	z-index: 1080;
}

.rd-nav-link {
	font: 400 14px/20px "Averia Libre";
	letter-spacing: .08em;
	text-transform: uppercase;
}

.rd-navbar-toggle {
	display: inline-block;
	position: relative;
	width: 40px;
	height: 40px;
	line-height: 40px;
	cursor: pointer;
	color: #29293a;
	padding: 0;
	background-color: transparent;
	border: none;
	display: none;
}

.rd-navbar-toggle span {
	position: relative;
	display: block;
	margin: auto;
	transition: .3s all ease;
}

.rd-navbar-toggle span::after, .rd-navbar-toggle span::before {
	content: "";
	position: absolute;
	left: 0;
	top: -6px;
	transition: .3s all ease;
}

.rd-navbar-toggle span::after {
	top: 6px;
}

.rd-navbar-toggle span::after, .rd-navbar-toggle span::before, .rd-navbar-toggle span {
	width: 24px;
	height: 2px;
	background-color: #29293a;
	backface-visibility: hidden;
	border-radius: 5;
}

.rd-navbar-toggle.active span {
	background: transparent;
	transition: .01s;
}

.rd-navbar-toggle.active span::before, .rd-navbar-toggle.active span::after {
	transform-origin: 50% 50%;
	top: 0;
}

.rd-navbar-toggle.active span::before {
	transform: rotate(45deg);
}

.rd-navbar-toggle.active span::after {
	transform: rotate(-45deg);
}

.rd-navbar-collapse-toggle {
	background: none;
	border: none;
	display: inline-block;
	padding: 0;
	outline: none;
	outline-offset: 0;
	cursor: pointer;
	-webkit-appearance: none;
	display: inline-block;
	position: relative;
	width: 40px;
	height: 40px;
	line-height: 40px;
	cursor: pointer;
	color: #29293a;
	display: none;
}

.rd-navbar-collapse-toggle::-moz-focus-inner {
	border: none;
	padding: 0;
}

.rd-navbar-collapse-toggle span {
	top: 50%;
	margin-top: -2.5px;
}

.rd-navbar-collapse-toggle span, .rd-navbar-collapse-toggle span::before, .rd-navbar-collapse-toggle span::after {
	position: absolute;
	width: 5px;
	height: 5px;
	line-height: 5px;
	text-align: center;
	background: #29293a;
	left: 50%;
	margin-left: -2.5px;
	border-radius: 50%;
	transition: .3s all ease;
}

.rd-navbar-collapse-toggle span::before, .rd-navbar-collapse-toggle span::after {
	content: '';
}

.rd-navbar-collapse-toggle span::before {
	bottom: 100%;
	margin-bottom: 2.5px;
}

.rd-navbar-collapse-toggle span::after {
	top: 100%;
	margin-top: 2.5px;
}

.rd-navbar-collapse-toggle.active span {
	transform: scale(0.7);
}

.rd-navbar-collapse-toggle.active span::before {
	transform: translateY(15px);
}

.rd-navbar-collapse-toggle.active span::after {
	transform: translateY(-15px);
}

.rd-navbar-brand a {
	display: block;
}

.rd-navbar-search {
	position: relative;
	display: inline-flex;
}

.rd-navbar-search .form-input {
	padding-right: 50px;
}

.rd-navbar-search .rd-search-form-submit {
	position: absolute;
	top: 0;
	bottom: 0;
	right: 0;
	width: 50px;
	padding: 0;
	margin: 0;
	border: none;
	cursor: pointer;
	background-color: transparent;
	font-size: 20px;
	color: #aeb1be;
	transition: .33s;
}

.rd-navbar-search .rd-search-form-submit:hover {
	color: #ef172c;
}

.rd-navbar-search .rd-search-results-live {
	pointer-events: none;
}

.rd-navbar-search .rd-search-results-live > * {
	pointer-events: auto;
}

.rd-navbar-search-toggle {
	background: none;
	border: none;
	display: inline-block;
	padding: 0;
	outline: none;
	outline-offset: 0;
	cursor: pointer;
	-webkit-appearance: none;
}

.rd-navbar-search-toggle::-moz-focus-inner {
	border: none;
	padding: 0;
}

.rd-navbar-dropdown {
	display: none;
}

.rd-navbar-popup {
	position: absolute;
	padding: 15px 25px 20px 20px;
	width: calc(100vw - 10px);
	border-radius: 4px;
	opacity: 0;
	visibility: hidden;
	transition: .2s;
	overflow: hidden;
	background-color: #29293a;
}

.rd-navbar-popup::before {
	content: '';
	position: absolute;
	right: 0;
	left: 0;
	top: 0;
	bottom: 0;
	z-index: -1;
	transform: scale3d(1, 0.1, 1);
	transform-origin: 50% 0;
	background: #29293a;
	border-radius: inherit;
	transition: .5s;
}

.rd-navbar-popup > * {
	position: relative;
	z-index: 1;
	opacity: 0;
	visibility: hidden;
	transition: .5s;
	transform-origin: 50% 0;
	transform: scale3d(1, 0.9, 1);
}

.rd-navbar-popup.active {
	opacity: 1;
	visibility: visible;
}

.rd-navbar-popup.active > * {
	opacity: 1;
	visibility: visible;
	transform: scale3d(1, 1, 1);
}

.rd-navbar-popup.active::before {
	transform: scale3d(1, 1, 1);
}

@media (min-width: 400px) {
	.rd-navbar-popup {
		width: 370px;
	}
}

@media (min-width: 768px) {
	.rd-navbar-popup {
		padding: 40px;
	}
}

.context-dark .rd-navbar-toggle, .bg-gray-700 .rd-navbar-toggle, .bg-gray-800 .rd-navbar-toggle, .bg-primary .rd-navbar-toggle, .bg-secondary .rd-navbar-toggle, .bg-primary-darker .rd-navbar-toggle {
	display: inline-block;
	position: relative;
	width: 40px;
	height: 40px;
	line-height: 40px;
	cursor: pointer;
	color: #fff;
	display: none;
}

.context-dark .rd-navbar-toggle span, .bg-gray-700 .rd-navbar-toggle span, .bg-gray-800 .rd-navbar-toggle span, .bg-primary .rd-navbar-toggle span, .bg-secondary .rd-navbar-toggle span, .bg-primary-darker .rd-navbar-toggle span {
	position: relative;
	display: block;
	margin: auto;
	transition: .3s all ease;
}

.context-dark .rd-navbar-toggle span::after, .bg-gray-700 .rd-navbar-toggle span::after, .bg-gray-800 .rd-navbar-toggle span::after, .bg-primary .rd-navbar-toggle span::after, .bg-secondary .rd-navbar-toggle span::after, .bg-primary-darker .rd-navbar-toggle span::after, .context-dark .rd-navbar-toggle span::before, .bg-gray-700 .rd-navbar-toggle span::before, .bg-gray-800 .rd-navbar-toggle span::before, .bg-primary .rd-navbar-toggle span::before, .bg-secondary .rd-navbar-toggle span::before, .bg-primary-darker .rd-navbar-toggle span::before {
	content: "";
	position: absolute;
	left: 0;
	top: -6px;
	transition: .3s all ease;
}

.context-dark .rd-navbar-toggle span::after, .bg-gray-700 .rd-navbar-toggle span::after, .bg-gray-800 .rd-navbar-toggle span::after, .bg-primary .rd-navbar-toggle span::after, .bg-secondary .rd-navbar-toggle span::after, .bg-primary-darker .rd-navbar-toggle span::after {
	top: 6px;
}

.context-dark .rd-navbar-toggle span::after, .bg-gray-700 .rd-navbar-toggle span::after, .bg-gray-800 .rd-navbar-toggle span::after, .bg-primary .rd-navbar-toggle span::after, .bg-secondary .rd-navbar-toggle span::after, .bg-primary-darker .rd-navbar-toggle span::after, .context-dark .rd-navbar-toggle span::before, .bg-gray-700 .rd-navbar-toggle span::before, .bg-gray-800 .rd-navbar-toggle span::before, .bg-primary .rd-navbar-toggle span::before, .bg-secondary .rd-navbar-toggle span::before, .bg-primary-darker .rd-navbar-toggle span::before, .context-dark .rd-navbar-toggle span, .bg-gray-700 .rd-navbar-toggle span, .bg-gray-800 .rd-navbar-toggle span, .bg-primary .rd-navbar-toggle span, .bg-secondary .rd-navbar-toggle span, .bg-primary-darker .rd-navbar-toggle span {
	width: 24px;
	height: 2px;
	background-color: #fff;
	backface-visibility: hidden;
	border-radius: 5;
}

.context-dark .rd-navbar-toggle.active span, .bg-gray-700 .rd-navbar-toggle.active span, .bg-gray-800 .rd-navbar-toggle.active span, .bg-primary .rd-navbar-toggle.active span, .bg-secondary .rd-navbar-toggle.active span, .bg-primary-darker .rd-navbar-toggle.active span {
	background: transparent;
	transition: .01s;
}

.context-dark .rd-navbar-toggle.active span::before, .bg-gray-700 .rd-navbar-toggle.active span::before, .bg-gray-800 .rd-navbar-toggle.active span::before, .bg-primary .rd-navbar-toggle.active span::before, .bg-secondary .rd-navbar-toggle.active span::before, .bg-primary-darker .rd-navbar-toggle.active span::before, .context-dark .rd-navbar-toggle.active span::after, .bg-gray-700 .rd-navbar-toggle.active span::after, .bg-gray-800 .rd-navbar-toggle.active span::after, .bg-primary .rd-navbar-toggle.active span::after, .bg-secondary .rd-navbar-toggle.active span::after, .bg-primary-darker .rd-navbar-toggle.active span::after {
	transform-origin: 50% 50%;
	top: 0;
}

.context-dark .rd-navbar-toggle.active span::before, .bg-gray-700 .rd-navbar-toggle.active span::before, .bg-gray-800 .rd-navbar-toggle.active span::before, .bg-primary .rd-navbar-toggle.active span::before, .bg-secondary .rd-navbar-toggle.active span::before, .bg-primary-darker .rd-navbar-toggle.active span::before {
	transform: rotate(45deg);
}

.context-dark .rd-navbar-toggle.active span::after, .bg-gray-700 .rd-navbar-toggle.active span::after, .bg-gray-800 .rd-navbar-toggle.active span::after, .bg-primary .rd-navbar-toggle.active span::after, .bg-secondary .rd-navbar-toggle.active span::after, .bg-primary-darker .rd-navbar-toggle.active span::after {
	transform: rotate(-45deg);
}

/*
* @subsection  RD Navbar Static
*/
.rd-navbar-static {
	display: block;
}

.rd-navbar-static .rd-nav-item {
	display: inline-block;
}

.rd-navbar-static .rd-nav-item.focus .rd-nav-link, .rd-navbar-static .rd-nav-item.opened .rd-nav-link {
	color: #ef172c;
	background: transparent;
}

.rd-navbar-static .rd-nav-item.focus > .rd-navbar-submenu-toggle, .rd-navbar-static .rd-nav-item.opened > .rd-navbar-submenu-toggle {
	color: #ef172c;
}

.rd-navbar-static .rd-nav-item.active .rd-nav-link {
	color: #ef172c;
	background: transparent;
}

.rd-navbar-static .rd-nav-item.active > .rd-navbar-submenu-toggle {
	color: #ef172c;
}

.rd-navbar-static .rd-nav-item.focus > .rd-navbar-submenu-toggle::before,
.rd-navbar-static .rd-nav-item.opened > .rd-navbar-submenu-toggle::before,
.rd-navbar-static .rd-nav-item .rd-nav-link:hover + .rd-navbar-submenu-toggle::before {
	transform: rotate(180deg);
}

.rd-navbar-static .rd-nav-item > .rd-navbar-submenu-toggle {
	margin-left: 3px;
	font-family: "Material Design Icons";
	font-size: 16px;
	cursor: pointer;
}

.rd-navbar-static .rd-nav-item > .rd-navbar-submenu-toggle::before {
	position: relative;
	display: inline-block;
	transition: .22s;
	content: '\f236';
	color: #ffffff;
}

.rd-navbar-static .rd-nav-item > .rd-navbar-submenu-toggle:hover {
	color: #ef172c;
}

.rd-navbar-static .rd-nav-item > .rd-navbar-submenu {
	margin-top: 20px;
}

.rd-navbar-static .rd-nav-item + .rd-nav-item {
	margin-left: 23px;
}

.rd-navbar-static .rd-nav-link {
	position: relative;
	display: inline-block;
	color: #fff !important;
	transition: .25s;
}

.rd-navbar-static .rd-nav-link:hover {
	/*color:#fff;*/
	color: #ef172c;
}

.rd-navbar-static .rd-menu {
	position: absolute;
	z-index: 15;
	display: block;
	padding: 16px 27px;
	margin-top: 22px;
	visibility: hidden;
	opacity: 0;
	text-align: left;
	box-shadow: 0 5px 10px 1px rgba(0, 0, 1, 0.3);
	margin-left: -10px;
	border-radius: 0px;
	transform: translate3d(0, 30px, 0);
}

@media (min-width: 1600px) {
	.rd-navbar-static .rd-menu {
		margin-left: -27px;
	}
}

.rd-navbar-static .rd-dropdown-item + .rd-dropdown-item,
.rd-navbar-static .rd-megamenu-list-item + .rd-megamenu-list-item {
	margin-top: 7px;
}

.rd-navbar-static .rd-navbar-dropdown {
	position: absolute;
	left: 0;
	width: 290px;
	background: #15191f;
	z-index: 5;
}

.rd-navbar-static .rd-navbar-dropdown .rd-navbar-dropdown {
	top: -1px;
	left: 100%;
	z-index: 2;
	margin-top: -15px;
	margin-left: 15px;
	transform: translate3d(30px, 0, 0);
}

.rd-navbar-static .rd-navbar-dropdown .rd-navbar-dropdown.rd-navbar-open-left {
	left: auto;
	right: 100%;
	margin-left: 0;
	margin-right: 15px;
	transform: translate3d(-30px, 0, 0);
}

.rd-navbar-static .rd-dropdown-item.focus .rd-dropdown-link, .rd-navbar-static .rd-dropdown-item.opened .rd-dropdown-link {
	color: #fff;
}

.rd-navbar-static .rd-dropdown-link {
	color: #aeb1be;
}

.rd-navbar-static .rd-dropdown-link:hover {
	color: #fff;
}

.rd-navbar-static .rd-navbar-dropdown li > a,
.rd-navbar-static .rd-megamenu-list li > a {
	position: relative;
	left: -13px;
	display: flex;
	padding: 4px 18px 4px 0;
	text-align: left;
}

.rd-navbar-static .rd-navbar-dropdown li > a, .rd-navbar-static .rd-navbar-dropdown li > a:focus, .rd-navbar-static .rd-navbar-dropdown li > a:active,
.rd-navbar-static .rd-megamenu-list li > a,
.rd-navbar-static .rd-megamenu-list li > a:focus,
.rd-navbar-static .rd-megamenu-list li > a:active {
	color: #aeb1be;
}

.rd-navbar-static .rd-navbar-dropdown li > a:hover,
.rd-navbar-static .rd-megamenu-list li > a:hover {
	color: #fff;
}

.rd-navbar-static .rd-navbar-dropdown li > a, .rd-navbar-static .rd-navbar-dropdown li > a::before,
.rd-navbar-static .rd-megamenu-list li > a,
.rd-navbar-static .rd-megamenu-list li > a::before {
	transition: all .2s ease-in-out;
}

.rd-navbar-static .rd-navbar-dropdown li > a::before,
.rd-navbar-static .rd-megamenu-list li > a::before {
	position: relative;
	top: -1px;
	left: -6px;
	display: inline-block;
	content: '\f238';
	font-family: 'Material Design Icons';
	font-size: inherit;
	line-height: inherit;
	color: #fff;
	opacity: 0;
	visibility: hidden;
}

.rd-navbar-static .rd-navbar-dropdown li.focus > a,
.rd-navbar-static .rd-navbar-dropdown li.opened > a,
.rd-navbar-static .rd-navbar-dropdown li > a:hover,
.rd-navbar-static .rd-megamenu-list li.focus > a,
.rd-navbar-static .rd-megamenu-list li.opened > a,
.rd-navbar-static .rd-megamenu-list li > a:hover {
	left: -13px;
	padding-left: 18px;
	padding-right: 0;
}

.rd-navbar-static .rd-navbar-dropdown li.focus > a::before,
.rd-navbar-static .rd-navbar-dropdown li.opened > a::before,
.rd-navbar-static .rd-navbar-dropdown li > a:hover::before,
.rd-navbar-static .rd-megamenu-list li.focus > a::before,
.rd-navbar-static .rd-megamenu-list li.opened > a::before,
.rd-navbar-static .rd-megamenu-list li > a:hover::before {
	left: -7px;
	opacity: 1;
	visibility: visible;
}

.rd-navbar-static .rd-navbar-megamenu {
	display: flex;
	right: 0;
	width: 100%;
	overflow: hidden;
	max-width: 1200px;
	background: #15191f;
}

.rd-navbar-static .rd-megamenu-item {
	flex-basis: 50%;
	flex-grow: 1;
}

.rd-navbar-static .rd-megamenu-item + .rd-megamenu-item {
	padding-left: 20px;
}

.rd-navbar-static .rd-megamenu-item {
	display: flex;
}

.rd-navbar-static .rd-megamenu-item .banner {
	position: relative;
	display: flex;
	align-items: flex-end;
	justify-content: center;
	text-align: center;
	min-width: 100%;
	padding: 35px;
}

.rd-navbar-static .rd-megamenu-item .banner::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(0, 0, 0, 0.1);
}

.rd-navbar-static .rd-megamenu-item .banner .button-primary:hover {
	background: #353535;
	border-color: #353535;
}

.rd-navbar-static .rd-megamenu-item .banner > * {
	opacity: 0;
	visibility: hidden;
	transform: translate(0, -20%);
	transition: .22s;
}

.rd-navbar-static .rd-megamenu-item .banner:hover > * {
	opacity: 1;
	visibility: visible;
	transform: translate(0, 0);
}

.rd-navbar-static .rd-megamenu-item:first-child .banner, .rd-navbar-static .rd-megamenu-item:last-child .banner {
	margin-top: -16px;
	margin-right: -27px;
	margin-bottom: -16px;
	margin-left: -27px;
}

.rd-navbar-static .rd-megamenu-title {
	padding-bottom: 10px;
	border-bottom: 1px solid #e8e9ee;
}

.rd-navbar-static .rd-megamenu-list-link {
	color: #aeb1be;
	background: transparent;
}

.rd-navbar-static .rd-megamenu-list-link:hover {
	color: #fff;
	background: transparent;
}

.rd-navbar-static * + .rd-megamenu-list {
	margin-top: 10px;
}

.rd-navbar-static .rd-navbar-submenu.focus > .rd-menu, .rd-navbar-static .rd-navbar-submenu.opened > .rd-menu {
	opacity: 1;
	visibility: visible;
	transform: translate3d(0, 0, 0);
}

.rd-navbar-static .rd-navbar-search.active .rd-search {
	visibility: visible;
	opacity: 1;
}

.rd-navbar-static .rd-navbar-search.active .not-empty ~ .form-input {
	border-bottom-left-radius: 0;
	border-bottom-right-radius: 0;
}

.rd-navbar-static .rd-navbar-search .rd-search {
	margin-top: 40px;
}

.rd-navbar-static .rd-navbar-search .form-input {
	padding-right: 19px;
}

.rd-navbar-static .rd-navbar-search .rd-search-form-submit {
	display: none;
}

.rd-navbar-static .rd-search {
	position: absolute;
	top: 100%;
	right: 0;
	width: 370px;
	opacity: 0;
	visibility: hidden;
	transition: .3s;
	margin-top: 20px;
	z-index: 2;
}

.rd-navbar-static * + .rd-navbar-search {
	margin-left: 38px;
}

.rd-navbar-static .rd-navbar-search-toggle {
	display: inline-flex;
	color: #29293a;
}

.rd-navbar-static .rd-navbar-search-toggle span {
	display: inline-block;
	position: relative;
	width: 32px;
	height: 32px;
	font-size: 26px;
	line-height: 32px;
	text-align: center;
	cursor: pointer;
	background: none;
	border: none;
	outline: none;
	padding: 0;
}

.rd-navbar-static .rd-navbar-search-toggle span, .rd-navbar-static .rd-navbar-search-toggle span::before, .rd-navbar-static .rd-navbar-search-toggle span::after {
	transition: .3s all ease-in-out;
}

.rd-navbar-static .rd-navbar-search-toggle span::before, .rd-navbar-static .rd-navbar-search-toggle span::after {
	position: absolute;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
}

.rd-navbar-static .rd-navbar-search-toggle span::before {
	content: "";
	transform: rotate(0deg) scale(1);
	opacity: 1;
	visibility: visible;
	font-family: "Material Design Icons";
}

.rd-navbar-static .rd-navbar-search-toggle span::after {
	content: "";
	transform: rotate(-90deg) scale(0.4);
	opacity: 0;
	visibility: hidden;
	font-family: "Material Design Icons";
}

.rd-navbar-static .rd-navbar-search-toggle.active span::before {
	opacity: 0;
	visibility: hidden;
	transform: rotate(90deg) scale(0.4);
}

.rd-navbar-static .rd-navbar-search-toggle.active span::after {
	transform: rotate(0deg) scale(1);
	opacity: 1;
	visibility: visible;
}

.rd-navbar-static .rd-navbar-search-toggle:hover {
	color: #ef172c;
}

.rd-navbar-static.rd-navbar--is-clone {
	display: block;
	transform: translate3d(0, -100%, 0);
}

.rd-navbar-static.rd-navbar--is-clone.rd-navbar--is-stuck {
	transform: translate3d(0, 0, 0);
}

.rd-navbar-static.rd-navbar--is-stuck, .rd-navbar-static.rd-navbar--is-clone {
	position: fixed;
	left: 0;
	top: 0;
	right: 0;
	z-index: 1080;
	background: #fff;
	will-change: transform;
}

.rd-navbar-static .rd-navbar--has-dropdown {
	position: relative;
}

/*
*
* RD Navbar Fixed
*/
.rd-navbar-fixed {
	display: block;
	width: 100%;
}

.rd-navbar-fixed .rd-navbar-toggle {
	display: inline-block;
}

.rd-navbar-fixed .rd-navbar-brand {
	position: relative;
	top: -2px;
	margin-left: 6px;
	font-size: 0;
	line-height: 0;
	text-align: left;
}

.rd-navbar-fixed .rd-navbar-brand img {
	max-width: 90%;
	max-height: 45px;
	width: auto;
	height: auto;
}

.rd-navbar-fixed .rd-navbar-panel {
	position: fixed;
	left: 0;
	top: 0;
	right: 0;
	z-index: 1080;
	display: flex;
	align-items: center;
	height: 56px;
	padding: 8px;
}

.rd-navbar-fixed .rd-navbar-nav-wrap {
	position: fixed;
	left: 0;
	top: -56px;
	bottom: -56px;
	z-index: 1079;
	width: 270px;
	padding: 112px 0 81px;
	overflow-y: auto;
	overflow-x: hidden;
	-webkit-overflow-scrolling: touch;
	font-size: 14px;
	line-height: 34px;
	transform: translateX(-110%);
}

.rd-navbar-fixed .rd-navbar-nav-wrap::-webkit-scrollbar {
	width: 4px;
}

.rd-navbar-fixed .rd-navbar-nav-wrap::-webkit-scrollbar-thumb {
	background: #f83866;
	border: none;
	border-radius: 0;
	opacity: .2;
}

.rd-navbar-fixed .rd-navbar-nav-wrap::-webkit-scrollbar-track {
	background: #ef172c;
	border: none;
	border-radius: 0;
}

.rd-navbar-fixed .rd-navbar-nav-wrap.active {
	transform: translateX(0);
}

.rd-navbar-fixed .rd-navbar-nav {
	display: block;
	margin: 15px 0;
	height: auto;
	text-align: left;
}

.rd-navbar-fixed .rd-nav-item {
	text-align: left;
}

.rd-navbar-fixed .rd-nav-item + .rd-nav-item {
	margin-top: 4px;
}

.rd-navbar-fixed .rd-nav-link {
	display: block;
	padding: 14px 56px 14px 18px;
}

.rd-navbar-fixed li.opened > .rd-navbar-dropdown {
	padding: 4px 0 0;
}

.rd-navbar-fixed li.opened > .rd-navbar-megamenu {
	padding-top: 15px;
	padding-bottom: 15px;
}

.rd-navbar-fixed li.opened > .rd-menu {
	opacity: 1;
	height: auto;
}

.rd-navbar-fixed li.opened > .rd-navbar-submenu-toggle::after {
	transform: rotate(180deg);
}

.rd-navbar-fixed .rd-menu {
	display: none;
	transition: opacity 0.3s, height 0.4s ease;
	opacity: 0;
	height: 0;
	overflow: hidden;
}

.rd-navbar-fixed .rd-navbar-submenu {
	position: relative;
}

.rd-navbar-fixed .rd-navbar-submenu .rd-navbar-dropdown .rd-navbar-submenu-toggle:after {
	height: 34px;
	line-height: 34px;
}

.rd-navbar-fixed .rd-navbar-submenu .rd-navbar-dropdown > li > a {
	padding-left: 30px;
}

.rd-navbar-fixed .rd-navbar-submenu .rd-navbar-dropdown li li > a,
.rd-navbar-fixed .rd-navbar-submenu .rd-navbar-megamenu ul li li > a {
	padding-left: 46px;
}

.rd-navbar-fixed .rd-navbar-submenu.opened > .rd-navbar-dropdown,
.rd-navbar-fixed .rd-navbar-submenu.opened > .rd-navbar-megamenu {
	display: block;
}

.rd-navbar-fixed .rd-megamenu-list > li > a,
.rd-navbar-fixed .rd-navbar-dropdown > li > a {
	display: block;
	padding: 9px 56px 9px 16px;
	font-size: 14px;
	line-height: 1.5;
}

.rd-navbar-fixed .rd-megamenu-list > li + li,
.rd-navbar-fixed .rd-navbar-dropdown > li + li {
	margin-top: 3px;
}

.rd-navbar-fixed .rd-megamenu-list > li > a {
	padding-left: 30px;
}

.rd-navbar-fixed .rd-navbar-megamenu .rd-megamenu-title {
	position: relative;
	display: block;
	padding: 0 18px 7px;
	font-size: 16px;
	line-height: 1.5;
}

.rd-navbar-fixed .rd-navbar-megamenu .rd-megamenu-title::after {
	content: '';
	position: absolute;
	left: 20px;
	right: 20px;
	bottom: 0;
	border-bottom: 1px solid;
}

.rd-navbar-fixed .rd-navbar-megamenu * + .rd-megamenu-list {
	margin-top: 11px;
}

.rd-navbar-fixed .rd-navbar-megamenu * + .rd-megamenu-title {
	margin-top: 20px;
}

.rd-navbar-fixed .rd-navbar-megamenu > li + li {
	margin-top: 20px;
}

.rd-navbar-fixed .rd-navbar-submenu-toggle {
	cursor: pointer;
}

.rd-navbar-fixed .rd-navbar-submenu-toggle::after {
	content: '\f107';
	position: absolute;
	top: 0;
	right: 0;
	width: 56px;
	height: 48px;
	font: 400 14px "FontAwesome";
	line-height: 48px;
	text-align: center;
	transition: 0.4s all ease;
	z-index: 2;
	cursor: pointer;
}

.rd-navbar-fixed .rd-navbar-collapse-toggle {
	display: block;
	top: 8px;
	z-index: 1081;
}

.rd-navbar-fixed .rd-navbar-collapse-content {
	position: fixed;
	right: 0;
	top: 56px;
	z-index: 1079;
	transform: translate3d(0, -10px, 0);
	padding: 30px;
	width: auto;
	border-radius: 0 0 0 6px;
	text-align: left;
	font-size: 14px;
	opacity: 0;
	visibility: hidden;
	transition: .3s;
}

.rd-navbar-fixed .rd-navbar-collapse-content.active {
	transform: translate3d(0, 0, 0);
	opacity: 1;
	visibility: visible;
}

.rd-navbar-fixed .rd-navbar-collapse-content > * + * {
	margin-top: 25px;
}

.rd-navbar-fixed .rd-navbar-main-outer,
.rd-navbar-fixed .rd-navbar-main-element {
	position: absolute;
	float: left;
	width: 100%;
}

.rd-navbar-fixed .rd-navbar-search .rd-search {
	position: fixed;
	right: 0;
	left: 0;
	top: 56px;
	z-index: 1079;
	width: 100%;
	opacity: 0;
	visibility: hidden;
	transition: .3s;
	transform: translate3d(0, -100%, 0);
}

.rd-navbar-fixed .rd-navbar-search .rd-search-results-live {
	display: none;
}

.rd-navbar-fixed .rd-navbar-search .form-input {
	padding-right: 60px;
}

.rd-navbar-fixed .rd-navbar-search .rd-search-form-submit {
	position: absolute;
	top: 0;
	bottom: 0;
	right: 7px;
	width: 50px;
	padding: 0;
	margin: 0;
	border: none;
	background-color: transparent;
}

.rd-navbar-fixed .rd-navbar-search.active .rd-search {
	opacity: 1;
	visibility: visible;
	transform: none;
}

.rd-navbar-fixed .rd-navbar-search-toggle {
	display: inline-flex;
}

.rd-navbar-fixed .rd-navbar-search-toggle span {
	display: inline-block;
	position: relative;
	width: 48px;
	height: 48px;
	font-size: 26px;
	line-height: 48px;
	text-align: center;
	cursor: pointer;
	background: none;
	border: none;
	outline: none;
	padding: 0;
}

.rd-navbar-fixed .rd-navbar-search-toggle span, .rd-navbar-fixed .rd-navbar-search-toggle span::before, .rd-navbar-fixed .rd-navbar-search-toggle span::after {
	transition: .3s all ease-in-out;
}

.rd-navbar-fixed .rd-navbar-search-toggle span::before, .rd-navbar-fixed .rd-navbar-search-toggle span::after {
	position: absolute;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
}

.rd-navbar-fixed .rd-navbar-search-toggle span::before {
	content: "";
	transform: rotate(0deg) scale(1);
	opacity: 1;
	visibility: visible;
	font-family: "Material Design Icons";
}

.rd-navbar-fixed .rd-navbar-search-toggle span::after {
	content: "";
	transform: rotate(-90deg) scale(0.4);
	opacity: 0;
	visibility: hidden;
	font-family: "Material Design Icons";
}

.rd-navbar-fixed .rd-navbar-search-toggle.active span::before {
	opacity: 0;
	visibility: hidden;
	transform: rotate(90deg) scale(0.4);
}

.rd-navbar-fixed .rd-navbar-search-toggle.active span::after {
	transform: rotate(0deg) scale(1);
	opacity: 1;
	visibility: visible;
}

.rd-navbar-fixed [class*='rd-navbar-fixed-element'] {
	position: fixed;
	top: 8px;
	z-index: 1082;
}

.rd-navbar-fixed .rd-navbar-fixed-element-1 {
	right: 0;
}

.rd-navbar-fixed .rd-navbar-fixed-element-2 {
	right: 46px;
}

.rd-navbar-fixed.rd-navbar--is-clone {
	display: none;
}

.rd-navbar-fixed .rd-navbar-fixed--visible {
	display: block;
}

.rd-navbar-fixed .rd-navbar-fixed--hidden {
	display: none;
}

.rd-navbar-fixed .rd-navbar-panel {
	color: #29293a;
	box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.05);
	background: #fff;
}

.rd-navbar-fixed .rd-navbar-nav-wrap {
	color: #fff;
	background: #fff;
	border-right: 1px solid #e8e9ee;
	box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.05);
}

.rd-navbar-fixed .rd-nav-item:hover .rd-nav-link, .rd-navbar-fixed .rd-nav-item.focus .rd-nav-link, .rd-navbar-fixed .rd-nav-item.active .rd-nav-link, .rd-navbar-fixed .rd-nav-item.opened .rd-nav-link {
	color: #fff;
	background: #ef172c;
}

.rd-navbar-fixed .rd-nav-item:hover > .rd-navbar-submenu-toggle, .rd-navbar-fixed .rd-nav-item.focus > .rd-navbar-submenu-toggle, .rd-navbar-fixed .rd-nav-item.active > .rd-navbar-submenu-toggle, .rd-navbar-fixed .rd-nav-item.opened > .rd-navbar-submenu-toggle {
	color: #fff;
}

.rd-navbar-fixed .rd-nav-link {
	color: #29293a !important;
}

.rd-navbar-fixed .rd-megamenu-list > li > a,
.rd-navbar-fixed .rd-navbar-dropdown > li > a {
	color: #29293a;
}

.rd-navbar-fixed .rd-megamenu-list > li:hover > a,
.rd-navbar-fixed .rd-megamenu-list > li.focus > a,
.rd-navbar-fixed .rd-megamenu-list > li.active > a,
.rd-navbar-fixed .rd-megamenu-list > li.opened > a,
.rd-navbar-fixed .rd-navbar-dropdown > li:hover > a,
.rd-navbar-fixed .rd-navbar-dropdown > li.focus > a,
.rd-navbar-fixed .rd-navbar-dropdown > li.active > a,
.rd-navbar-fixed .rd-navbar-dropdown > li.opened > a {
	color: #fff;
	background: #ef172c;
}

.rd-navbar-fixed .rd-navbar-megamenu .rd-megamenu-title {
	color: #aeb1be;
}

.rd-navbar-fixed .rd-navbar-megamenu .rd-megamenu-title::after {
	border-bottom: 1px solid #e8e9ee;
}

.rd-navbar-fixed .rd-navbar-megamenu .rd-megamenu-title a, .rd-navbar-fixed .rd-navbar-megamenu .rd-megamenu-title a:focus, .rd-navbar-fixed .rd-navbar-megamenu .rd-megamenu-title a:active {
	color: #fff;
}

.rd-navbar-fixed .rd-navbar-megamenu .rd-megamenu-title a:hover {
	color: #ef172c;
}

.rd-navbar-fixed .rd-navbar-submenu-toggle {
	color: #29293a;
}

.rd-navbar-fixed .rd-navbar-search .rd-search-form-submit {
	color: #aeb1be;
}

.rd-navbar-fixed .rd-navbar-search .rd-search-form-submit:hover {
	color: #ef172c;
}

.rd-navbar-fixed .rd-navbar-search-toggle {
	color: #29293a;
}

.rd-navbar-fixed .rd-navbar-search-toggle:hover {
	color: #ef172c;
}

.page-header-absolute .rd-navbar-fixed .rd-navbar-search-toggle {
	color: #fff;
}

.page-header-absolute .rd-navbar-fixed .rd-navbar-search-toggle:hover {
	color: #ef172c;
}

.rd-navbar-fixed .rd-navbar-collapse-content {
	background-color: #fff;
	box-shadow: 0 0 22px -4px rgba(0, 0, 0, 0.17);
}

.rd-navbar-fixed .banner {
	position: relative;
	overflow: hidden;
	padding: 20px;
	margin: 10px;
	border-radius: 0px;
	text-align: center;
}

.rd-navbar-fixed .banner::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(41, 41, 58, 0.4);
	border-radius: inherit;
}

html.rd-navbar-fixed-linked .page {
	padding-top: 56px;
}

.context-dark .rd-navbar-fixed .rd-navbar-panel, .bg-gray-700 .rd-navbar-fixed .rd-navbar-panel, .bg-gray-800 .rd-navbar-fixed .rd-navbar-panel, .bg-primary .rd-navbar-fixed .rd-navbar-panel, .bg-secondary .rd-navbar-fixed .rd-navbar-panel, .bg-primary-darker .rd-navbar-fixed .rd-navbar-panel {
	background: #29293a;
}

.context-dark .rd-navbar-fixed .rd-navbar-nav-wrap, .bg-gray-700 .rd-navbar-fixed .rd-navbar-nav-wrap, .bg-gray-800 .rd-navbar-fixed .rd-navbar-nav-wrap, .bg-primary .rd-navbar-fixed .rd-navbar-nav-wrap, .bg-secondary .rd-navbar-fixed .rd-navbar-nav-wrap, .bg-primary-darker .rd-navbar-fixed .rd-navbar-nav-wrap {
	border-right-color: #29293a;
	background: #252534;
}

.context-dark .rd-navbar-fixed .rd-nav-link, .bg-gray-700 .rd-navbar-fixed .rd-nav-link, .bg-gray-800 .rd-navbar-fixed .rd-nav-link, .bg-primary .rd-navbar-fixed .rd-nav-link, .bg-secondary .rd-navbar-fixed .rd-nav-link, .bg-primary-darker .rd-navbar-fixed .rd-nav-link,
.context-dark .rd-navbar-fixed .rd-navbar-submenu-toggle,
.bg-gray-700 .rd-navbar-fixed .rd-navbar-submenu-toggle,
.bg-gray-800 .rd-navbar-fixed .rd-navbar-submenu-toggle,
.bg-primary .rd-navbar-fixed .rd-navbar-submenu-toggle,
.bg-secondary .rd-navbar-fixed .rd-navbar-submenu-toggle,
.bg-primary-darker .rd-navbar-fixed .rd-navbar-submenu-toggle {
	color: #fff;
}

.context-dark .rd-navbar-fixed .rd-navbar-dropdown > li > a, .bg-gray-700 .rd-navbar-fixed .rd-navbar-dropdown > li > a, .bg-gray-800 .rd-navbar-fixed .rd-navbar-dropdown > li > a, .bg-primary .rd-navbar-fixed .rd-navbar-dropdown > li > a, .bg-secondary .rd-navbar-fixed .rd-navbar-dropdown > li > a, .bg-primary-darker .rd-navbar-fixed .rd-navbar-dropdown > li > a,
.context-dark .rd-navbar-fixed .rd-megamenu-list-link,
.bg-gray-700 .rd-navbar-fixed .rd-megamenu-list-link,
.bg-gray-800 .rd-navbar-fixed .rd-megamenu-list-link,
.bg-primary .rd-navbar-fixed .rd-megamenu-list-link,
.bg-secondary .rd-navbar-fixed .rd-megamenu-list-link,
.bg-primary-darker .rd-navbar-fixed .rd-megamenu-list-link {
	color: #e8e9ee;
}

/*
*
* RD Navbar Sidebar
*/
.rd-navbar-sidebar {
	display: block;
	background: #fff;
}

.rd-navbar-sidebar .rd-navbar-main-outer {
	padding-left: 15px;
	padding-right: 15px;
}

.rd-navbar-sidebar .rd-navbar-main {
	position: relative;
	display: flex;
	align-items: center;
	justify-content: space-between;
	padding: 22px 60px 22px 0;
	max-width: 1200px;
	margin-left: auto;
	margin-right: auto;
	transition: 0.5s cubic-bezier(0.4, 0, 0.2, 1);
}

.rd-navbar-sidebar .rd-navbar-main-element {
	display: flex;
	align-items: center;
}

.rd-navbar-sidebar .rd-navbar-main-element > * + * {
	margin-left: 20px;
}

.rd-navbar-sidebar .rd-navbar-toggle {
	position: absolute;
	right: 0;
	top: 50%;
	transform: translateY(-50%);
	display: block;
	z-index: 1102;
}

.rd-navbar-sidebar .rd-navbar-panel {
	min-width: 200px;
	text-align: center;
}

.rd-navbar-sidebar .rd-navbar-brand img {
	width: auto;
	height: auto;
	max-width: 216px;
	max-height: 216px;
}

.rd-navbar-sidebar .rd-navbar-nav-wrap {
	position: fixed;
	top: 0;
	bottom: 0;
	right: 0;
	z-index: 1101;
	width: 450px;
	padding: 94px 0 0 0;
	background: #fff;
	transition: 0.5s cubic-bezier(0.4, 0, 0.2, 1);
	transform: translateX(100%);
	box-shadow: 0 0 13px 0 rgba(174, 177, 190, 0.16);
}

.rd-navbar-sidebar .rd-navbar-nav-wrap.active {
	transition-delay: .1s;
	transform: translateX(0);
}

.rd-navbar-sidebar .rd-navbar-nav {
	height: calc(100vh - 100px);
	overflow-x: hidden;
	overflow-y: auto;
	-webkit-overflow-scrolling: touch;
	border-top: 1px solid #e8e9ee;
}

.rd-navbar-sidebar .rd-nav-item {
	position: relative;
	display: block;
	padding: 19px 30px 19px 40px;
}

.rd-navbar-sidebar .rd-nav-item.active .rd-nav-link {
	color: #ef172c;
}

.rd-navbar-sidebar .rd-nav-item .rd-nav-link,
.rd-navbar-sidebar .rd-nav-item > .rd-navbar-submenu-toggle {
	font-size: 18px;
}

.rd-navbar-sidebar .rd-nav-item + .rd-nav-item {
	border-top: 1px solid #e8e9ee;
}

.rd-navbar-sidebar .rd-nav-item:last-child {
	border-bottom: 1px solid #e8e9ee;
	margin-bottom: 30px;
}

.rd-navbar-sidebar .rd-nav-link {
	max-width: calc(100% - 30px);
	word-break: break-all;
	font-size: 18px;
	line-height: 1.4;
	text-transform: none;
	color: #aeb1be;
}

.rd-navbar-sidebar .rd-nav-link:hover {
	color: #ef172c;
}

.rd-navbar-sidebar .rd-navbar-submenu .opened > .rd-navbar-submenu-toggle::after {
	transform: rotate(180deg);
}

.rd-navbar-sidebar .rd-navbar-submenu > .rd-navbar-dropdown,
.rd-navbar-sidebar .rd-navbar-submenu > .rd-navbar-megamenu {
	display: none;
	opacity: 0;
	visibility: hidden;
	will-change: opacity, visibility;
	transition: opacity .2s;
}

.rd-navbar-sidebar .rd-navbar-submenu.opened > .rd-navbar-dropdown,
.rd-navbar-sidebar .rd-navbar-submenu.opened > .rd-navbar-megamenu {
	display: block;
	opacity: 1;
	visibility: visible;
}

.rd-navbar-sidebar .rd-navbar-submenu > .rd-navbar-submenu > .rd-navbar-dropdown,
.rd-navbar-sidebar .rd-navbar-submenu > .rd-navbar-submenu > .rd-navbar-megamenu {
	transform: translateY(30px);
}

.rd-navbar-sidebar .rd-navbar-submenu > .rd-navbar-submenu.opened > .rd-navbar-dropdown,
.rd-navbar-sidebar .rd-navbar-submenu > .rd-navbar-submenu.opened > .rd-navbar-megamenu {
	transform: translateY(0);
}

.rd-navbar-sidebar .rd-navbar-submenu > .rd-navbar-submenu .rd-navbar-submenu > .rd-navbar-dropdown {
	transform: translateX(-20px);
}

.rd-navbar-sidebar .rd-navbar-submenu > .rd-navbar-submenu .rd-navbar-submenu.opened > .rd-navbar-dropdown {
	transform: translateX(0);
}

.rd-navbar-sidebar .rd-nav-item > .rd-navbar-submenu-toggle,
.rd-navbar-sidebar .rd-nav-item .rd-navbar--has-dropdown > .rd-navbar-submenu-toggle {
	position: absolute;
	top: 0;
	right: 0;
	padding-top: inherit;
	padding-right: inherit;
	padding-left: 10px;
	margin-bottom: inherit;
	display: inline-block;
	width: 30px;
	margin-left: 5px;
	text-align: center;
	cursor: pointer;
	color: #29293a;
}

.rd-navbar-sidebar .rd-nav-item > .rd-navbar-submenu-toggle:hover,
.rd-navbar-sidebar .rd-nav-item .rd-navbar--has-dropdown > .rd-navbar-submenu-toggle:hover {
	color: #ef172c;
}

.rd-navbar-sidebar .rd-nav-item > .rd-navbar-submenu-toggle::after,
.rd-navbar-sidebar .rd-nav-item .rd-navbar--has-dropdown > .rd-navbar-submenu-toggle::after {
	content: '\f107';
	position: relative;
	display: inline-block;
	font-family: "FontAwesome";
	font-size: inherit;
	line-height: inherit;
	text-align: center;
	vertical-align: middle;
	transition: 0.4s all ease;
	z-index: 2;
	will-change: transform;
}

.rd-navbar-sidebar .rd-nav-item .rd-navbar--has-dropdown > .rd-navbar-submenu-toggle {
	font-size: 14px;
	color: #aeb1be;
	margin-left: 7px;
}

.rd-navbar-sidebar .rd-menu {
	margin-top: 31px;
}

.rd-navbar-sidebar .rd-navbar-dropdown,
.rd-navbar-sidebar .rd-megamenu-list {
	font-size: 14px;
}

.rd-navbar-sidebar .rd-navbar-dropdown li > a,
.rd-navbar-sidebar .rd-megamenu-list li > a {
	position: relative;
	left: -13px;
	display: flex;
	padding: 4px 18px 4px 0;
	text-align: left;
}

.rd-navbar-sidebar .rd-navbar-dropdown li > a, .rd-navbar-sidebar .rd-navbar-dropdown li > a:focus, .rd-navbar-sidebar .rd-navbar-dropdown li > a:active,
.rd-navbar-sidebar .rd-megamenu-list li > a,
.rd-navbar-sidebar .rd-megamenu-list li > a:focus,
.rd-navbar-sidebar .rd-megamenu-list li > a:active {
	color: #aeb1be;
}

.rd-navbar-sidebar .rd-navbar-dropdown li > a:hover,
.rd-navbar-sidebar .rd-megamenu-list li > a:hover {
	color: #fff;
}

.rd-navbar-sidebar .rd-navbar-dropdown li > a, .rd-navbar-sidebar .rd-navbar-dropdown li > a::before,
.rd-navbar-sidebar .rd-megamenu-list li > a,
.rd-navbar-sidebar .rd-megamenu-list li > a::before {
	transition: all .2s ease-in-out;
}

.rd-navbar-sidebar .rd-navbar-dropdown li > a::before,
.rd-navbar-sidebar .rd-megamenu-list li > a::before {
	position: relative;
	top: -1px;
	left: -6px;
	display: inline-block;
	content: '\f238';
	font-family: 'Material Design Icons';
	font-size: inherit;
	line-height: inherit;
	color: #fff;
	opacity: 0;
	visibility: hidden;
}

.rd-navbar-sidebar .rd-navbar-dropdown li.focus > a,
.rd-navbar-sidebar .rd-navbar-dropdown li.opened > a,
.rd-navbar-sidebar .rd-navbar-dropdown li > a:hover,
.rd-navbar-sidebar .rd-megamenu-list li.focus > a,
.rd-navbar-sidebar .rd-megamenu-list li.opened > a,
.rd-navbar-sidebar .rd-megamenu-list li > a:hover {
	left: -13px;
	padding-left: 18px;
	padding-right: 0;
}

.rd-navbar-sidebar .rd-navbar-dropdown li.focus > a::before,
.rd-navbar-sidebar .rd-navbar-dropdown li.opened > a::before,
.rd-navbar-sidebar .rd-navbar-dropdown li > a:hover::before,
.rd-navbar-sidebar .rd-megamenu-list li.focus > a::before,
.rd-navbar-sidebar .rd-megamenu-list li.opened > a::before,
.rd-navbar-sidebar .rd-megamenu-list li > a:hover::before {
	left: -7px;
	opacity: 1;
	visibility: visible;
}

.rd-navbar-sidebar .rd-navbar-megamenu {
	max-width: 450px;
	margin-bottom: -30px;
}

.rd-navbar-sidebar .rd-navbar-megamenu > * {
	margin-bottom: 30px;
}

.rd-navbar-sidebar .rd-navbar-megamenu > li {
	display: inline-block;
	vertical-align: top;
	width: 45%;
}

.rd-navbar-sidebar .rd-megamenu-title {
	display: none;
}

.rd-navbar-sidebar .rd-megamenu-list {
	margin-top: 0;
}

.rd-navbar-sidebar .rd-megamenu-list > li + li {
	margin-top: 10px;
}

.rd-navbar-sidebar .rd-navbar-dropdown .rd-navbar--has-dropdown > a {
	padding-right: 0;
}

.rd-navbar-sidebar .rd-navbar-dropdown .rd-navbar--has-dropdown > a::before {
	display: none;
}

.rd-navbar-sidebar .rd-navbar-dropdown .rd-navbar--has-dropdown > a:hover {
	padding-left: 0;
}

.rd-navbar-sidebar .rd-navbar-dropdown .rd-navbar--has-dropdown.focus > a {
	padding-left: 0;
}

.rd-navbar-sidebar .rd-navbar-dropdown .rd-navbar--has-dropdown.opened > .rd-navbar-submenu-toggle {
	color:#fff;
	/*color: #ef172c;*/
}

.rd-navbar-sidebar .rd-navbar-dropdown .rd-navbar--has-dropdown.opened > .rd-navbar-submenu-toggle::after {
	top: 1px;
}

.rd-navbar-sidebar .rd-navbar-dropdown > li + li {
	margin-top: 10px;
}

.rd-navbar-sidebar .rd-nav-item > .rd-navbar-dropdown {
	margin-top: 25px;
}

.rd-navbar-sidebar .rd-nav-item > .rd-navbar-dropdown .rd-navbar-dropdown {
	margin-top: 10px;
	padding-left: 15px;
}

.rd-navbar-sidebar .rd-nav-item > .rd-navbar-dropdown .rd-navbar-dropdown > li > a {
	font-size: 12px;
}

@media (min-width: 1200px) {
	.rd-navbar-sidebar .rd-navbar-megamenu {
		margin-bottom: -30px;
	}
	.rd-navbar-sidebar .rd-navbar-megamenu > * {
		margin-bottom: 30px;
	}
	.rd-navbar-sidebar .rd-navbar-dropdown > li + li,
	.rd-navbar-sidebar .rd-megamenu-list > li + li {
		margin-top: 18px;
	}
}

@media (min-width: 1200px) {
	.rd-navbar-sidebar .rd-navbar-nav-wrap {
		width: auto;
		left: calc(50% + 600px - 80px);
	}
}

.rd-navbar-sidebar.rd-navbar--is-clone {
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	z-index: 1000;
	transform: translateY(-101%);
}

.rd-navbar-sidebar.rd-navbar--is-clone.rd-navbar--is-stuck {
	transform: translateY(0);
}

.rd-navbar-sidebar.rd-navbar--is-stuck {
	position: fixed;
	left: 0;
	right: 0;
	top: 0;
	z-index: 1000;
	box-shadow: 0 2px 10px 1px rgba(0, 0, 0, 0.1);
}

.rd-navbar-sidebar.rd-navbar--is-stuck .rd-navbar-main {
	padding-top: 11px;
	padding-bottom: 11px;
}

/**
*
* RD Navbar Minimal
* 
*/
.rd-navbar-minimal.rd-navbar-static {
	border-bottom: 1px solid transparent;
}

.rd-navbar-minimal.rd-navbar-static .rd-navbar-main-outer {
	padding-left: 15px;
	padding-right: 15px;
}

.rd-navbar-minimal.rd-navbar-static .rd-navbar-main {
	position: relative;
	display: flex;
	align-items: center;
	justify-content: space-between;
	max-width: 1170px;
	padding: 20px 0;
	margin-left: auto;
	margin-right: auto;
}

.rd-navbar-minimal.rd-navbar-static .rd-navbar-main-element {
	position: relative;
	display: flex;
	align-items: center;
	justify-content: space-between;
	min-width: 690px;
}

.rd-navbar-minimal.rd-navbar-static .rd-navbar-brand img {
	width: auto;
	height: auto;
	max-width: 216px;
	max-height: 216px;
}

.rd-navbar-minimal.rd-navbar-static .rd-navbar-megamenu {
	margin-top: 24px;
	width: calc(100% + 27px + 15px);
}

.rd-navbar-minimal.rd-navbar-static .rd-navbar-search-toggle span {
	font-size: 20px;
}

@media (min-width: 1200px) {
	.rd-navbar-minimal.rd-navbar-static .rd-navbar-main {
		padding: 30px 0;
	}
	.rd-navbar-minimal.rd-navbar-static .rd-menu {
		margin-top: 34px;
	}
}

.rd-navbar-minimal.rd-navbar-static.rd-navbar--is-stuck, .rd-navbar-minimal.rd-navbar-static.rd-navbar--is-clone {
	border-bottom-color: #e8e9ee;
}

.rd-navbar-minimal.rd-navbar-static.rd-navbar--is-stuck .rd-navbar-main, .rd-navbar-minimal.rd-navbar-static.rd-navbar--is-clone .rd-navbar-main {
	padding: 20px 0;
}

.rd-navbar-minimal.rd-navbar-static.rd-navbar--is-stuck .rd-menu, .rd-navbar-minimal.rd-navbar-static.rd-navbar--is-clone .rd-menu {
	margin-top: 24px;
}

.rd-navbar-minimal.rd-navbar-static.rd-navbar--is-stuck .rd-navbar-nav-item > .rd-navbar-submenu, .rd-navbar-minimal.rd-navbar-static.rd-navbar--is-clone .rd-navbar-nav-item > .rd-navbar-submenu {
	margin-top: 17px;
}

.rd-navbar-minimal.rd-navbar-fixed .rd-navbar-search-toggle {
	position: fixed;
	right: 10px;
	top: 5px;
}

.rd-navbar-minimal.rd-navbar-fixed .rd-navbar-search .form-input {
	border-width: 1px 0 1px 0;
	border-radius: 0;
}

.rd-navbar-minimal-wide.rd-navbar-static .rd-navbar-main {
	padding: 54px 0;
}

.rd-navbar-minimal-wide.rd-navbar-static.rd-navbar--is-stuck .rd-navbar-main {
	padding: 21px 0;
}

.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal .rd-nav-link,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal .rd-navbar-submenu-toggle,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal .rd-navbar-search-toggle {
	color: #fff;
}

.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static {
	background-color: transparent;
}

.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-nav-item.opened .rd-nav-link,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-nav-item.focus .rd-nav-link,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-nav-item.active .rd-nav-link,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-nav-item.opened .rd-navbar-submenu-toggle,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-nav-item.focus .rd-navbar-submenu-toggle,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-nav-item.active .rd-navbar-submenu-toggle,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-nav-link:hover,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-nav-link:hover ~ .rd-navbar-submenu-toggle,
.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static .rd-navbar-search-toggle:hover {
	color: #f83866;
}

.rd-navbar-static-linked .page-header-absolute .rd-navbar-minimal.rd-navbar-static.rd-navbar--is-stuck {
	background: #29293a;
	border-bottom-color: #15191f;
}

/**
*
* RD Navbar Corporate
* 
*/
.rd-navbar-corporate.rd-navbar-static {
	border-bottom: 0 solid #e8e9ee;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-aside-outer,
.rd-navbar-corporate.rd-navbar-static .rd-navbar-main-outer {
	padding-left: 15px;
	padding-right: 15px;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-aside,
.rd-navbar-corporate.rd-navbar-static .rd-navbar-main {
	max-width: 1170px;
	margin-left: auto;
	margin-right: auto;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-aside {
	display: flex;
	align-items: center;
	justify-content: space-between;
	padding: 15px 0;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-brand img {
	width: auto;
	height: auto;
	max-width: 716px;
	max-height: 216px;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-main-outer {
	background: #353535;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-main {
	position: relative;
	padding: 16px 0;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-nav-wrap {
	position: relative;
	display: flex;
	flex-direction: row-reverse;
	align-items: center;
	justify-content: center;
	min-width: 690px;
}

.ie-10 .rd-navbar-corporate.rd-navbar-static .rd-navbar-collapse,
.ie-11 .rd-navbar-corporate.rd-navbar-static .rd-navbar-collapse {
	width: 100%;
	max-width: 870px;
}

.ie-10 .rd-navbar-corporate.rd-navbar-static .unit,
.ie-11 .rd-navbar-corporate.rd-navbar-static .unit {
	flex: auto;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-panel + .rd-navbar-collapse {
	margin-left: 30px;
}

@media (min-width: 768px) {
	.rd-navbar-corporate.rd-navbar-static .rd-navbar-panel + .rd-navbar-collapse {
	margin-left: 10px;
}
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-collapse-content {
	display: flex;
	align-items: center;
	justify-content: center;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-collapse-content .button {
	flex-shrink: 0;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-collapse-content > * {
	margin-top: 0;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-collapse-content > * + * {
	margin-left: 15px;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-info .unit {
	margin-bottom: -30px;
	margin-left: -10px;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-info .unit > * {
	margin-bottom: 30px;
	margin-left: 10px;
}

.rd-navbar-corporate.rd-navbar-static .rd-menu {
	margin-top: 21px;
}

.rd-navbar-corporate.rd-navbar-static .rd-navbar-megamenu {
	margin-top: 24px;
	max-width: 750px;
}

@media (min-width: 1200px) {
	.rd-navbar-corporate.rd-navbar-static .rd-navbar-panel + .rd-navbar-collapse {
		margin-left: 25px;
	}
	.rd-navbar-corporate.rd-navbar-static .rd-navbar-collapse-content > * + * {
		margin-left: 30px;
	}
	.rd-navbar-corporate.rd-navbar-static .rd-navbar-info .unit {
		margin-bottom: -30px;
		margin-left: -20px;
	}
	.rd-navbar-corporate.rd-navbar-static .rd-navbar-info .unit > * {
		margin-bottom: 30px;
		margin-left: 20px;
	}
	.rd-navbar-corporate.rd-navbar-static .rd-nav-item + .rd-nav-item {
		margin-left: 55px;
	}
}

.rd-navbar-corporate.rd-navbar-static.rd-navbar--is-stuck, .rd-navbar-corporate.rd-navbar-static.rd-navbar--is-clone {
	border-bottom-width: 1px;
}

.rd-navbar-corporate.rd-navbar-static.rd-navbar--is-stuck .rd-navbar-aside-outer, .rd-navbar-corporate.rd-navbar-static.rd-navbar--is-clone .rd-navbar-aside-outer {
	display: none;
}

.rd-navbar-corporate.rd-navbar-static.rd-navbar--is-stuck .rd-navbar-nav-item > .rd-navbar-submenu, .rd-navbar-corporate.rd-navbar-static.rd-navbar--is-clone .rd-navbar-nav-item > .rd-navbar-submenu {
	margin-top: 17px;
}

.rd-navbar-corporate.rd-navbar-fixed .rd-navbar-search {
	margin: 20px 5px;
}

.rd-navbar-corporate.rd-navbar-fixed .rd-navbar-search-toggle {
	display: none;
}

.rd-navbar-corporate.rd-navbar-fixed .rd-search {
	position: relative;
	top: 0;
	left: 0;
	transform: none;
	opacity: 1;
	visibility: visible;
	z-index: 1;
}

.rd-navbar-corporate.rd-navbar-fixed .rd-navbar-nav {
	margin: 0;
}

/**
*
* RD Navbar Thin
* 
*/
.rd-navbar-thin.rd-navbar-static {
	background-color: #29293a;
	border-bottom: 1px solid transparent;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-main-outer {
	padding-left: 15px;
	padding-right: 15px;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-main {
	position: relative;
	display: flex;
	align-items: center;
	justify-content: space-between;
	max-width: 1170px;
	padding: 23px 0;
	margin-left: auto;
	margin-right: auto;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-nav-wrap {
	position: absolute;
	top: 0;
	bottom: 0;
	left: 200px;
	right: 80px;
	z-index: 102;
	display: flex;
	align-items: center;
	justify-content: flex-end;
	min-width: 690px;
	background: #29293a;
	opacity: 0;
	visibility: hidden;
	transition: .44s ease-in-out;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-nav-wrap .rd-navbar-brand {
	display: none;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-nav-wrap.active {
	opacity: 1;
	visibility: visible;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-panel {
	display: flex;
	align-items: center;
	justify-content: space-between;
	width: 100%;
	padding-right: 50px;
}

.ie-10 .rd-navbar-thin.rd-navbar-static .rd-navbar-panel,
.ie-11 .rd-navbar-thin.rd-navbar-static .rd-navbar-panel {
	justify-content: flex-start;
}

.ie-10 .rd-navbar-thin.rd-navbar-static .rd-navbar-block,
.ie-11 .rd-navbar-thin.rd-navbar-static .rd-navbar-block {
	width: 100%;
	justify-content: flex-end;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-toggle {
	position: absolute;
	right: 0;
	top: 50%;
	display: block;
	transform: translate3d(0, -50%, 0);
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-block {
	display: flex;
	align-items: center;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-brand {
	max-width: 300px;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-brand img {
	width: auto;
	height: auto;
	max-width: 216px;
	max-height: 216px;
}

.rd-navbar-thin.rd-navbar-static .rd-nav-link,
.rd-navbar-thin.rd-navbar-static .rd-navbar-submenu-toggle,
.rd-navbar-thin.rd-navbar-static .rd-navbar-search-toggle {
	color: #fff;
}

.rd-navbar-thin.rd-navbar-static .rd-nav-item.opened .rd-nav-link,
.rd-navbar-thin.rd-navbar-static .rd-nav-item.focus .rd-nav-link,
.rd-navbar-thin.rd-navbar-static .rd-nav-item.active .rd-nav-link,
.rd-navbar-thin.rd-navbar-static .rd-nav-item.opened .rd-navbar-submenu-toggle,
.rd-navbar-thin.rd-navbar-static .rd-nav-item.focus .rd-navbar-submenu-toggle,
.rd-navbar-thin.rd-navbar-static .rd-nav-item.active .rd-navbar-submenu-toggle,
.rd-navbar-thin.rd-navbar-static .rd-nav-link:hover,
.rd-navbar-thin.rd-navbar-static .rd-nav-link:hover ~ .rd-navbar-submenu-toggle,
.rd-navbar-thin.rd-navbar-static .rd-navbar-search-toggle:hover {
	color: #f83866;
}

.rd-navbar-thin.rd-navbar-static .rd-menu {
	margin-top: 27px;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-megamenu {
	margin-top: 24px;
	width: calc(100% + 27px + 15px);
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-search {
	position: static;
}

.rd-navbar-thin.rd-navbar-static * + .rd-navbar-search-toggle {
	margin-left: 60px;
}

.rd-navbar-thin.rd-navbar-static .rd-search {
	position: absolute;
	top: 0;
	bottom: 0;
	left: 0;
	right: 0;
	display: flex;
	width: calc(100% - 70px);
	margin: 0;
}

.rd-navbar-thin.rd-navbar-static .rd-search .form-wrap {
	display: flex;
	width: 100%;
	background: #29293a;
}

.rd-navbar-thin.rd-navbar-static .rd-search .form-wrap::before {
	content: '\f43b';
	position: absolute;
	top: 50%;
	transform: translate3d(0, -50%, 0);
	font-family: 'Material Design Icons';
	font-size: 30px;
	line-height: 1;
	color: #fff;
}

.rd-navbar-thin.rd-navbar-static .rd-search .form-input,
.rd-navbar-thin.rd-navbar-static .rd-search .form-label {
	padding-left: 40px;
	font-size: 30px;
	color: #fff;
}

.rd-navbar-thin.rd-navbar-static .rd-search .form-input {
	background-color: transparent;
	border: 0;
	border-radius: 0;
}

.rd-navbar-thin.rd-navbar-static .rd-search .form-label {
	top: 50%;
	transform: translate3d(0, -50%, 0);
}

.rd-navbar-thin.rd-navbar-static .rd-search-results-live {
	height: 100vh;
	margin: 1px 0 0 0;
}

.rd-navbar-thin.rd-navbar-static .search-list {
	display: flex;
	flex-wrap: wrap;
	margin-bottom: -20px;
}

.rd-navbar-thin.rd-navbar-static .search-list-item {
	width: 25%;
	padding-left: 15px;
	padding-right: 15px;
	margin-bottom: 20px;
}

.rd-navbar-thin.rd-navbar-static .search-list-item + .search-list-item {
	margin-top: 0;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-search-toggle {
	position: relative;
	z-index: 12;
}

.rd-navbar-thin.rd-navbar-static .rd-navbar-popup {
	left: 50%;
	z-index: 110;
	transform: translateX(-50%);
	margin-top: 30px;
}

.rd-navbar-thin.rd-navbar-static .list-inline-bordered {
	position: relative;
}

@media (min-width: 992px) and (max-width: 1199.98px) {
	.rd-navbar-thin.rd-navbar-static .rd-nav-item + .rd-nav-item {
		margin-left: 30px;
	}
}

@media (min-width: 1200px) {
	.rd-navbar-thin.rd-navbar-static .rd-navbar-panel {
		padding-right: 70px;
	}
	.rd-navbar-thin.rd-navbar-static .rd-navbar-nav-wrap {
		left: 300px;
		right: 70px;
	}
}

@media (min-width: 1600px) {
	.rd-navbar-thin.rd-navbar-static .rd-navbar-popup {
		right: auto;
	}
}

.rd-navbar-thin.rd-navbar-static.rd-navbar--is-stuck, .rd-navbar-thin.rd-navbar-static.rd-navbar--is-clone {
	border-bottom-color: #15191f;
}

.rd-navbar-thin.rd-navbar-static.rd-navbar--is-stuck .rd-menu, .rd-navbar-thin.rd-navbar-static.rd-navbar--is-clone .rd-menu {
	margin-top: 27px;
}

.rd-navbar-thin.rd-navbar-fixed .rd-navbar-search .form-input {
	border-width: 0 0 1px 0;
	border-radius: 0;
}

.rd-navbar-thin.rd-navbar-fixed .rd-navbar-search-toggle {
	position: fixed;
	top: 5px;
	right: 8px;
	color: #fff;
}

.rd-navbar-thin.rd-navbar-fixed .rd-navbar-search-toggle span {
	font-size: 20px;
}

.rd-navbar-thin.rd-navbar-fixed .rd-navbar-block {
	position: absolute;
	top: 14px;
	right: 65px;
}

.rd-navbar-thin.rd-navbar-fixed .rd-navbar-popup {
	position: fixed;
	right: 5px;
	margin-top: 20px;
	overflow-y: auto;
	max-height: calc(100vh - 56px - 10px);
}

.rd-navbar-thin.rd-navbar-fixed .rd-navbar-brand {
	display: none;
}

.rd-navbar-thin.rd-navbar-fixed .rd-navbar-nav-wrap .rd-navbar-brand {
	display: inline-block;
	line-height: 0;
	font-size: 0;
	margin: 30px 20px 20px;
}

@media (min-width: 480px) {
	.rd-navbar-thin.rd-navbar-fixed .rd-navbar-brand {
		display: block;
	}
	.rd-navbar-thin.rd-navbar-fixed .rd-navbar-nav-wrap .rd-navbar-brand {
		display: none;
	}
}

/*
*
* Swiper
*/
.swiper-container {
	position: relative;
	display: flex;
	margin: 0 auto;
	overflow: hidden;
	list-style: none;
	padding: 0;
	/* Fix of Webkit flickering */
	z-index: 1;
	pointer-events: none;
}

.swiper-container, .swiper-container * {
	backface-visibility: hidden;
}

.swiper-container-no-flexbox .swiper-slide {
	float: left;
}

.swiper-container-vertical > .swiper-wrapper {
	flex-direction: column;
}

.swiper-wrapper {
	position: relative;
	z-index: 1;
	display: flex;
	align-self: stretch;
	align-items: stretch;
	width: 100%;
	height: auto;
	min-height: inherit;
	transition-property: transform;
	box-sizing: content-box;
}

.swiper-container-android .swiper-slide,
.swiper-wrapper {
	transform: translate3d(0px, 0, 0);
}

.swiper-container-multirow > .swiper-wrapper {
	flex-wrap: wrap;
}

.swiper-container-free-mode > .swiper-wrapper {
	transition-timing-function: ease-out;
	margin: 0 auto;
}

.swiper-slide {
	flex-shrink: 0;
	width: 100%;
	height: 100%;
	position: relative;
	background-size: cover;
	transition-property: transform, transform;
	pointer-events: auto;
	contain: paint;
}

.swiper-invisible-blank-slide {
	visibility: hidden;
}

/* Auto Height */
.swiper-container-autoheight, .swiper-container-autoheight .swiper-slide {
	height: auto;
}

.swiper-container-autoheight .swiper-wrapper {
	align-items: flex-start;
	transition-property: transform, height;
}

/* 3D Effects */
.swiper-container-3d {
	perspective: 1200px;
}

.swiper-container-3d .swiper-wrapper,
.swiper-container-3d .swiper-slide,
.swiper-container-3d .swiper-slide-shadow-left,
.swiper-container-3d .swiper-slide-shadow-right,
.swiper-container-3d .swiper-slide-shadow-top,
.swiper-container-3d .swiper-slide-shadow-bottom,
.swiper-container-3d .swiper-cube-shadow {
	transform-style: preserve-3d;
}

.swiper-container-3d .swiper-slide-shadow-left,
.swiper-container-3d .swiper-slide-shadow-right,
.swiper-container-3d .swiper-slide-shadow-top,
.swiper-container-3d .swiper-slide-shadow-bottom {
	position: absolute;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	pointer-events: none;
	z-index: 10;
}

.swiper-container-3d .swiper-slide-shadow-left {
	background-image: linear-gradient(to left, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0));
}

.swiper-container-3d .swiper-slide-shadow-right {
	background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0));
}

.swiper-container-3d .swiper-slide-shadow-top {
	background-image: linear-gradient(to top, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0));
}

.swiper-container-3d .swiper-slide-shadow-bottom {
	background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0));
}

/* IE10 Windows Phone 8 Fixes */
.swiper-container-wp8-horizontal,
.swiper-container-wp8-horizontal > .swiper-wrapper {
	touch-action: pan-y;
}

.swiper-container-wp8-vertical,
.swiper-container-wp8-vertical > .swiper-wrapper {
	touch-action: pan-x;
}

.swiper-button-prev,
.swiper-button-next {
	position: absolute;
	top: 50%;
	width: 27px;
	height: 44px;
	margin-top: -22px;
	z-index: 10;
	cursor: pointer;
	background-size: 27px 44px;
	background-position: center;
	background-repeat: no-repeat;
}

.swiper-button-prev.swiper-button-disabled,
.swiper-button-next.swiper-button-disabled {
	opacity: 0.35;
	cursor: auto;
	pointer-events: none;
}

.swiper-button-lock {
	display: none;
}

.swiper-pagination {
	position: absolute;
	text-align: center;
	transition: 300ms opacity;
	transform: translate3d(0, 0, 0);
	z-index: 10;
}

.swiper-pagination.swiper-pagination-hidden {
	opacity: 0;
}

/* Common Styles */
.swiper-pagination-fraction,
.swiper-pagination-custom,
.swiper-container-horizontal > .swiper-pagination-bullets {
	bottom: 10px;
	left: 0;
	width: 100%;
}

/* Bullets */
.swiper-pagination-bullets-dynamic {
	overflow: hidden;
	font-size: 0;
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet {
	transform: scale(0.33);
	position: relative;
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active {
	transform: scale(1);
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-prev {
	transform: scale(0.66);
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-prev-prev {
	transform: scale(0.33);
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-next {
	transform: scale(0.66);
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-next-next {
	transform: scale(0.33);
}

.swiper-pagination-bullet {
	width: 8px;
	height: 8px;
	display: inline-block;
	border-radius: 100%;
	background: #000;
}

button.swiper-pagination-bullet {
	border: none;
	margin: 0;
	padding: 0;
	box-shadow: none;
	-webkit-appearance: none;
	-moz-appearance: none;
	appearance: none;
}

.swiper-pagination-clickable .swiper-pagination-bullet {
	cursor: pointer;
}

.swiper-pagination-bullet-active {
	opacity: 1;
	background: #007aff;
}

.swiper-container-vertical > .swiper-pagination-bullets {
	right: 10px;
	top: 50%;
	transform: translate3d(0px, -50%, 0);
}

.swiper-container-vertical > .swiper-pagination-bullets .swiper-pagination-bullet {
	margin: 6px 0;
	display: block;
}

.swiper-container-vertical > .swiper-pagination-bullets.swiper-pagination-bullets-dynamic {
	top: 50%;
	transform: translateY(-50%);
	width: 8px;
}

.swiper-container-vertical > .swiper-pagination-bullets.swiper-pagination-bullets-dynamic .swiper-pagination-bullet {
	display: inline-block;
	transition: 200ms transform, 200ms top;
}

.swiper-container-horizontal > .swiper-pagination-bullets .swiper-pagination-bullet {
	margin: 0 4px;
}

.swiper-container-horizontal > .swiper-pagination-bullets.swiper-pagination-bullets-dynamic {
	left: 50%;
	transform: translateX(-50%);
	white-space: nowrap;
}

.swiper-container-horizontal > .swiper-pagination-bullets.swiper-pagination-bullets-dynamic .swiper-pagination-bullet {
	transition: 200ms transform, 200ms left;
}

.swiper-container-horizontal.swiper-container-rtl > .swiper-pagination-bullets-dynamic .swiper-pagination-bullet {
	transition: 200ms transform, 200ms right;
}

/* Progress */
.swiper-pagination-progressbar {
	background: rgba(0, 0, 0, 0.25);
	position: absolute;
}

.swiper-pagination-progressbar .swiper-pagination-progressbar-fill {
	background: #007aff;
	position: absolute;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	transform: scale(0);
	transform-origin: left top;
}

.swiper-container-rtl .swiper-pagination-progressbar .swiper-pagination-progressbar-fill {
	transform-origin: right top;
}

.swiper-container-horizontal > .swiper-pagination-progressbar {
	width: 100%;
	height: 4px;
	left: 0;
	top: 0;
}

.swiper-container-vertical > .swiper-pagination-progressbar {
	width: 4px;
	height: 100%;
	left: 0;
	top: 0;
}

.swiper-pagination-white .swiper-pagination-bullet-active {
	background: #fff;
}

.swiper-pagination-progressbar.swiper-pagination-white {
	background: rgba(255, 255, 255, 0.25);
}

.swiper-pagination-progressbar.swiper-pagination-white .swiper-pagination-progressbar-fill {
	background: #fff;
}

.swiper-pagination-black .swiper-pagination-bullet-active {
	background: #000;
}

.swiper-pagination-progressbar.swiper-pagination-black {
	background: rgba(0, 0, 0, 0.25);
}

.swiper-pagination-progressbar.swiper-pagination-black .swiper-pagination-progressbar-fill {
	background: #000;
}

.swiper-pagination-lock {
	display: none;
}

/* Scrollbar */
.swiper-scrollbar {
	border-radius: 10px;
	position: relative;
	-ms-touch-action: none;
	background: rgba(0, 0, 0, 0.1);
}

.swiper-container-horizontal > .swiper-scrollbar {
	position: absolute;
	left: 1%;
	bottom: 3px;
	z-index: 50;
	height: 5px;
	width: 98%;
}

.swiper-container-vertical > .swiper-scrollbar {
	position: absolute;
	right: 3px;
	top: 1%;
	z-index: 50;
	width: 5px;
	height: 98%;
}

.swiper-scrollbar-drag {
	height: 100%;
	width: 100%;
	position: relative;
	background: rgba(0, 0, 0, 0.5);
	border-radius: 10px;
	left: 0;
	top: 0;
}

.swiper-scrollbar-cursor-drag {
	cursor: move;
}

.swiper-scrollbar-lock {
	display: none;
}

.swiper-zoom-container {
	display: flex;
	justify-content: center;
	align-items: center;
	width: 100%;
	height: 100%;
	text-align: center;
}

.swiper-zoom-container > img,
.swiper-zoom-container > svg,
.swiper-zoom-container > canvas {
	max-width: 100%;
	max-height: 100%;
	-o-object-fit: contain;
	object-fit: contain;
}

.swiper-slide-zoomed {
	cursor: move;
}

/* Preloader */
.swiper-lazy-preloader {
	width: 42px;
	height: 42px;
	position: absolute;
	left: 50%;
	top: 50%;
	margin-left: -21px;
	margin-top: -21px;
	z-index: 10;
	transform-origin: 50%;
	animation: swiper-preloader-spin 1s steps(12, end) infinite;
}

.swiper-lazy-preloader:after {
	display: block;
	content: '';
	width: 100%;
	height: 100%;
	background-image: url("data:image/svg+xml;charset=utf-8,%3Csvg%20viewBox%3D'0%200%20120%20120'%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20xmlns%3Axlink%3D'http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink'%3E%3Cdefs%3E%3Cline%20id%3D'l'%20x1%3D'60'%20x2%3D'60'%20y1%3D'7'%20y2%3D'27'%20stroke%3D'%236c6c6c'%20stroke-width%3D'11'%20stroke-linecap%3D'round'%2F%3E%3C%2Fdefs%3E%3Cg%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(30%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(60%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(90%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(120%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(150%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.37'%20transform%3D'rotate(180%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.46'%20transform%3D'rotate(210%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.56'%20transform%3D'rotate(240%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.66'%20transform%3D'rotate(270%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.75'%20transform%3D'rotate(300%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.85'%20transform%3D'rotate(330%2060%2C60)'%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E");
	background-position: 50%;
	background-size: 100%;
	background-repeat: no-repeat;
}

.swiper-lazy-preloader-white:after {
	background-image: url("data:image/svg+xml;charset=utf-8,%3Csvg%20viewBox%3D'0%200%20120%20120'%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20xmlns%3Axlink%3D'http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink'%3E%3Cdefs%3E%3Cline%20id%3D'l'%20x1%3D'60'%20x2%3D'60'%20y1%3D'7'%20y2%3D'27'%20stroke%3D'%23fff'%20stroke-width%3D'11'%20stroke-linecap%3D'round'%2F%3E%3C%2Fdefs%3E%3Cg%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(30%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(60%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(90%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(120%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.27'%20transform%3D'rotate(150%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.37'%20transform%3D'rotate(180%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.46'%20transform%3D'rotate(210%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.56'%20transform%3D'rotate(240%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.66'%20transform%3D'rotate(270%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.75'%20transform%3D'rotate(300%2060%2C60)'%2F%3E%3Cuse%20xlink%3Ahref%3D'%23l'%20opacity%3D'.85'%20transform%3D'rotate(330%2060%2C60)'%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E");
}

@keyframes swiper-preloader-spin {
	100% {
		transform: rotate(360deg);
	}
}

/* a11y */
.swiper-container .swiper-notification {
	position: absolute;
	left: 0;
	top: 0;
	pointer-events: none;
	opacity: 0;
	z-index: -1000;
}

.swiper-container-fade .swiper-container-free-mode .swiper-slide {
	transition-timing-function: ease-out;
}

.swiper-container-fade .swiper-slide {
	pointer-events: none;
	transition-property: opacity;
}

.swiper-container-fade .swiper-slide .swiper-slide {
	pointer-events: none;
}

.swiper-container-fade .swiper-slide-active,
.swiper-container-fade .swiper-slide-active .swiper-slide-active {
	pointer-events: auto;
}

.swiper-container-cube {
	overflow: visible;
}

.swiper-container-cube .swiper-slide {
	pointer-events: none;
	backface-visibility: hidden;
	z-index: 1;
	visibility: hidden;
	transform-origin: 0 0;
	width: 100%;
	height: 100%;
}

.swiper-container-cube .swiper-slide .swiper-slide {
	pointer-events: none;
}

.swiper-container-cube.swiper-container-rtl .swiper-slide {
	transform-origin: 100% 0;
}

.swiper-container-cube .swiper-slide-active,
.swiper-container-cube .swiper-slide-active .swiper-slide-active {
	pointer-events: auto;
}

.swiper-container-cube .swiper-slide-active,
.swiper-container-cube .swiper-slide-next,
.swiper-container-cube .swiper-slide-prev,
.swiper-container-cube .swiper-slide-next + .swiper-slide {
	pointer-events: auto;
	visibility: visible;
}

.swiper-container-cube .swiper-slide-shadow-top,
.swiper-container-cube .swiper-slide-shadow-bottom,
.swiper-container-cube .swiper-slide-shadow-left,
.swiper-container-cube .swiper-slide-shadow-right {
	z-index: 0;
	backface-visibility: hidden;
}

.swiper-container-cube .swiper-cube-shadow {
	position: absolute;
	left: 0;
	bottom: 0px;
	width: 100%;
	height: 100%;
	background: #000;
	opacity: 0.6;
	filter: blur(50px);
	z-index: 0;
}

.swiper-container-flip {
	overflow: visible;
}

.swiper-container-flip .swiper-slide {
	pointer-events: none;
	backface-visibility: hidden;
	z-index: 1;
}

.swiper-container-flip .swiper-slide .swiper-slide {
	pointer-events: none;
}

.swiper-container-flip .swiper-slide-active,
.swiper-container-flip .swiper-slide-active .swiper-slide-active {
	pointer-events: auto;
}

.swiper-container-flip .swiper-slide-shadow-top,
.swiper-container-flip .swiper-slide-shadow-bottom,
.swiper-container-flip .swiper-slide-shadow-left,
.swiper-container-flip .swiper-slide-shadow-right {
	z-index: 0;
	backface-visibility: hidden;
}

.swiper-container-coverflow .swiper-wrapper {
	/* Windows 8 IE 10 fix */
	-ms-perspective: 1200px;
}

.swiper-button-prev,
.swiper-button-next {
	position: absolute;
	top: 50%;
	transform: translateY(-50%);
	display: none;
	font-size: 38px;
	line-height: 1;
	color: #fff;
	text-align: center;
	cursor: pointer;
	transition: .2s ease-in;
	will-change: transform;
	z-index: 10;
}

.swiper-button-prev:hover,
.swiper-button-next:hover {
	color: #ef172c;
}

.swiper-button-prev::before,
.swiper-button-next::before {
	font-family: 'Material Design Icons';
}

@media (min-width: 768px) {
	.swiper-button-prev,
	.swiper-button-next {
		display: block;
	}
}

.swiper-button-prev.swiper-button-disabled,
.swiper-button-next.swiper-button-disabled {
	opacity: 0.35;
	cursor: auto;
	pointer-events: none;
}

.swiper-button-prev {
	left: 30px;
}

.swiper-button-prev::before {
	content: "\f14a";
}

.swiper-button-next {
	right: 30px;
}

.swiper-button-next::before {
	content: "\f14f";
}

.swiper-slider.swiper-container-rtl .swiper-button-prev::before {
	content: "\f061";
}

.swiper-slider.swiper-container-rtl .swiper-button-next::before {
	content: "\f060";
}

.swiper-pagination {
	position: absolute;
	display: block;
	text-align: center;
	transition: .3s;
	transform: translate3d(0, 0, 0);
	z-index: 10;
}

.swiper-pagination.swiper-pagination-hidden {
	opacity: 0;
}

.swiper-pagination.swiper-pagination-clickable .swiper-pagination-bullet {
	cursor: pointer;
}

.swiper-pagination-bullet {
	width: 10px;
	height: 10px;
	display: inline-block;
	border-radius: 100%;
	background: rgba(255, 255, 255, 0.6);
	transition: .2s;
}

.swiper-pagination-bullet.swiper-pagination-bullet-active, .swiper-pagination-bullet:hover {
	background: white;
}

.swiper-container-vertical > .swiper-pagination {
	right: 10px;
	top: 50%;
	transform: translate3d(0px, -50%, 0);
}

.swiper-container-vertical > .swiper-pagination .swiper-pagination-bullet {
	margin: 5px 0;
	display: block;
}

.swiper-container-horizontal > .swiper-pagination {
	bottom: 20px;
	left: 0;
	width: 100%;
}

.swiper-container-horizontal > .swiper-pagination .swiper-pagination-bullet {
	margin: 0 5px;
}

.swiper-pagination-outer {
	position: absolute;
	left: 50%;
	transform: translate3d(-50%, 0, 0);
	z-index: 20;
	bottom: 30px;
	pointer-events: none;
}

.swiper-pagination-outer .swiper-pagination {
	pointer-events: auto;
}

.swiper-pagination.swiper-pagination-modern {
	position: relative;
	display: inline-block;
	width: auto;
	right: auto;
	left: auto;
	margin-left: -10px;
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet,
.swiper-pagination.swiper-pagination-modern .swiper-pagination-mark {
	width: 32px;
	height: 32px;
	border-radius: 50%;
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet {
	display: inline-block;
	background: transparent;
	font-weight: 400;
	color: #29293a;
	text-align: center;
	transition: .33s;
	line-height: 32px;
	margin: 0 10px;
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-mark {
	position: absolute;
	top: 0;
	bottom: 0;
	z-index: -1;
	left: -10px;
	display: block;
	background: #ef172c;
	transition: .4s ease-in-out;
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet:not(.swiper-pagination-bullet-active):hover {
	font-weight: 700;
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active {
	color: #fff;
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(1) ~ .swiper-pagination-mark {
	transform: translateX(20px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(2) ~ .swiper-pagination-mark {
	transform: translateX(72px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(3) ~ .swiper-pagination-mark {
	transform: translateX(124px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(4) ~ .swiper-pagination-mark {
	transform: translateX(176px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(5) ~ .swiper-pagination-mark {
	transform: translateX(228px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(6) ~ .swiper-pagination-mark {
	transform: translateX(280px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(7) ~ .swiper-pagination-mark {
	transform: translateX(332px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(8) ~ .swiper-pagination-mark {
	transform: translateX(384px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(9) ~ .swiper-pagination-mark {
	transform: translateX(436px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(10) ~ .swiper-pagination-mark {
	transform: translateX(488px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(11) ~ .swiper-pagination-mark {
	transform: translateX(540px);
}

.swiper-pagination.swiper-pagination-modern .swiper-pagination-bullet-active:nth-child(12) ~ .swiper-pagination-mark {
	transform: translateX(592px);
}

.context-dark .swiper-pagination .swiper-pagination-bullet, .bg-gray-700 .swiper-pagination .swiper-pagination-bullet, .bg-gray-800 .swiper-pagination .swiper-pagination-bullet, .bg-primary .swiper-pagination .swiper-pagination-bullet, .bg-secondary .swiper-pagination .swiper-pagination-bullet, .bg-primary-darker .swiper-pagination .swiper-pagination-bullet {
	color: #fff;
}

.swiper-slide {
	position: relative;
	display: flex;
	align-items: center;
	flex-shrink: 0;
	width: 100%;
	height: 100%;
	white-space: nowrap;
	background-position: 55% center;
}

.swiper-slide > * {
	width: 100%;
	white-space: normal;
}

.swiper-slide .container {
	width: 100%;
}

.swiper-slider-light {
	min-height: 40.41667vw;
}

.swiper-slider-light .swiper-slide::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: linear-gradient(to right, rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 0.3));
	pointer-events: none;
}

.swiper-slider-light[data-custom-slide-effect='inter-leave-effect'] .slide-inner {
	background: inherit;
}

.swiper-slider-light .swiper-slide-caption {
	position: relative;
	z-index: 1;
	max-width: 800px;
	padding: 40px 0 80px;
}

.swiper-slider-light h1 span, .swiper-slider-light h2 span, .swiper-slider-light h3 span, .swiper-slider-light h4 span, .swiper-slider-light h5 span, .swiper-slider-light h6 span, .swiper-slider-light [class^='heading-'] span {
	display: block;
}

.container + .swiper-slider-light {
	margin-top: 20px;
}

@media (min-width: 576px) {
	.swiper-slider-light .swiper-slide::before {
		background: linear-gradient(to right, rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 0));
	}
	.swiper-slider-light .slider-slide-caption {
		padding: 45px 0 95px;
	}
}

@media (min-width: 768px) {
	.swiper-slider-light .swiper-slide {
		background-position: center center;
	}
	.swiper-slider-light .swiper-slide::before {
		display: none;
	}
	.swiper-slider-light .swiper-slide-caption {
		padding: 80px 0 165px;
	}
	.swiper-slider-light .swiper-pagination-outer {
		bottom: 50px;
	}
}

@media (min-width: 1200px) {
	.swiper-slider-light .swiper-pagination-outer {
		bottom: 72px;
	}
}

.swiper-slider-business {
	min-height: 41.66667vw;
}

.swiper-slider-business .swiper-slide {
	background-position: 60% 50%;
}

.swiper-slider-business .swiper-slide::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: linear-gradient(to right, rgba(220, 220, 226, 0.7), rgba(149, 149, 153, 0.4));
	pointer-events: none;
}


.parallax-container {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: linear-gradient(to right, rgba(41, 41, 58, 0.7), rgba(41, 41, 58, 0.4));

}



.swiper-slider-business .swiper-slide > * {
	position: relative;
	z-index: 1;
}

.swiper-slider-business .swiper-slide-caption {
	padding: 50px 0 100px;
}

.swiper-slider-business .swiper-caption-text {
	position: relative;
	overflow: hidden;
	max-width: 520px;
	padding-left: 35px;
}

.swiper-slider-business .swiper-caption-text p {
	width: 100%;
}

.swiper-slider-business .swiper-caption-text-inner {
	position: relative;
	overflow: hidden;
}

.swiper-slider-business .swiper-caption-text-sm {
	max-width: 420px;
}

.swiper-slider-business .swiper-caption-text-decoration {
	position: absolute;
	top: 0;
	bottom: 0;
	left: 0;
	width: 2px;
	background: #ef172c;
}

.swiper-slider-business .swiper-slider-nav {
	position: absolute;
	left: 50%;
	bottom: 20px;
	z-index: 20;
	width: 100%;
	transform: translate3d(-50%, 0, 0);
	pointer-events: none;
	text-align: left;
}

.swiper-slider-business .swiper-slider-nav > * + * {
	margin-left: 10px;
}

.swiper-slider-business .wow-outer {
	white-space: normal;
}

.swiper-slider-business .wow-outer span {
	display: inline-block;
}

.swiper-slider-business .swiper-button-prev,
.swiper-slider-business .swiper-button-next {
	position: relative;
	transform: none;
	left: auto;
	top: auto;
	right: auto;
	display: inline-block;
	pointer-events: auto;
}

.swiper-slider-business * + .swiper-caption-text {
	margin-top: 20px;
}

@media (min-width: 768px) {
	.swiper-slider-business .swiper-slide-caption {
		padding: 130px 0 180px;
	}
}

@media (min-width: 992px) {
	.swiper-slider-business .swiper-slider-nav {
		bottom: 40px;
	}
}

@media (min-width: 1200px) {
	.swiper-slider-business .swiper-slide::before {
		display: none;
	}
}

@media (min-width: 1600px) {
	.swiper-slider-business * + .swiper-caption-text {
		margin-top: 45px;
	}
}

.swiper-slider-minimal {
	min-height: 41.66667vw;
	text-align: center;
}

.swiper-slider-minimal .swiper-slide {
	background-position: 50% 50%;
	justify-content: center;
}

.swiper-slider-minimal .swiper-slide::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: #000;
	opacity: .4;
}

.swiper-slider-minimal .swiper-slide > * {
	position: relative;
	z-index: 1;
}

.swiper-slider-minimal .swiper-slide_video {
	display: flex;
	align-items: stretch;
}

.swiper-slider-minimal .vide_bg {
	position: relative;
	display: flex;
	flex-direction: column;
	justify-content: center;
}

.swiper-slider-minimal .vide_bg::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: #000;
	opacity: .4;
}

.swiper-slider-minimal .swiper-slide-caption {
	position: relative;
	z-index: 2;
	padding: 80px 0 120px;
}

.swiper-slider-minimal .swiper-slide-text {
	position: relative;
	overflow: hidden;
	width: auto;
}

.swiper-slider-minimal .swiper-slide-text > * {
	position: relative;
	transform: translateY(100%);
}

.swiper-slider-minimal .swiper-slide-active .swiper-slide-text > * {
	transform: translateY(0);
	transition: .5s .3s;
}

@media (min-width: 768px) {
	.swiper-slider-minimal .swiper-slide-caption {
		padding: 170px 0 220px;
	}
	.swiper-slider-minimal .swiper-pagination-outer {
		bottom: 50px;
	}
}

@media (min-width: 1600px) {
	.swiper-slider-minimal .swiper-pagination-outer {
		bottom: 90px;
	}
}

[data-custom-slide-effect='inter-leave-effect'] .swiper-slide {
	display: flex;
	will-change: transform;
	overflow: hidden;
	align-items: stretch;
	min-height: inherit;
}

[data-custom-slide-effect='inter-leave-effect'] .slide-inner {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	background-size: cover;
}

[data-custom-slide-effect='inter-leave-effect'] .slide-inner > * {
	width: 100%;
}

.swiper-slider-tiny {
	min-height: 400px;
}

.swiper-slider-tiny .swiper-slide {
	position: relative;
}

.swiper-slider-tiny .swiper-slide::before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	pointer-events: none;
	background: linear-gradient(to top, rgba(255, 255, 255, 0.3) 0%, rgba(255, 255, 255, 0) 40%);
}

.swiper-slider-tiny .swiper-slide > * {
	position: relative;
	z-index: 1;
}

@media (min-width: 768px) {
	.swiper-slider-tiny {
		min-height: 39.58333vw;
	}
}

@media (min-width: 992px) {
	.swiper-slider-tiny .swiper-pagination-outer {
		bottom: 65px;
	}
}

/*
*
* Google Map
*/
.google-map-markers {
	display: none;
}

.google-map-container {
	width: 100%;
}

.google-map {
	color: #000;
	height: 200px;
}

@media (min-width: 576px) {
	.google-map {
		height: 250px;
	}
}

@media (min-width: 768px) {
	.google-map {
		height: 300px;
	}
}

@media (min-width: 992px) {
	.google-map {
		height: 350px;
	}
}

@media (min-width: 1200px) {
	.google-map {
		height: 440px;
	}
}

.google-map-align {
	display: flex;
	min-height: 330px;
	height: auto;
}

.google-map-align .google-map {
	width: 100%;
	height: auto;
}

/*.google-map-1 {

	// Extra large ≥1200px
	@include media-breakpoint-up(xl) {
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		height: auto;
	}
}*/
.map_locations {
	display: none;
}

.gm-style-pbt {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	background: #111111;
	color: #fff;
	padding: 5px 14px;
	font-size: 16px;
	border-radius: 3px;
	box-shadow: 1px 1px 10px 0 rgba(0, 0, 0, 0.2);
	width: 100%;
	text-align: center;
	max-width: 300px;
}

/*
*
* Search Results
*/
.rd-search-results-live {
	position: absolute;
	left: 0;
	right: 0;
	top: 100%;
	max-height: 600px;
	overflow-y: auto;
	margin: -3px 0 0;
	text-align: left;
	z-index: 998;
}

.rd-search-results-live #search-results {
	position: relative;
	padding: 10px 0 0;
	border-bottom-left-radius: 6px;
	border-bottom-right-radius: 6px;
	color: #29293a;
	background: #fff;
	border: 1px solid #c5c6cd;
	border-top: 0;
	opacity: 0;
	visibility: hidden;
	transform-origin: 50% 0;
	transform: scale(1, 0.9);
	transition: .3s all ease;
}

.rd-search-results-live #search-results.active {
	opacity: 1;
	visibility: visible;
	transform: scale(1, 1);
}

.rd-search-results-live #search-results.active .form-input {
	border-bottom-left-radius: 0;
}

.rd-search-results-live .search-quick-result {
	padding-left: 15px;
	padding-right: 15px;
	font-family: "Averia Libre";
	font-size: 14px;
	font-weight: 500;
	letter-spacing: .08em;
	line-height: 30px;
	text-transform: uppercase;
	color: #29293a;
}

.rd-search-results-live .search-list {
	margin-top: 11px;
}

.rd-search-results-live .search-list li:only-child {
	padding: 0 15px 15px;
}

.rd-search-results-live .search-link {
	color: #aeb1be;
}

.rd-search-results-live .search-link:hover {
	color: #ef172c;
}

.rd-search-results-live .search-error {
	padding: 0 0 20px;
	font-size: 14px;
	line-height: 1.6;
}

.rd-search-results-live .search-title {
	position: relative;
	font-size: 16px;
	font-weight: 400;
	color: #29293a;
}

.rd-search-results-live .search-title a:hover {
	color: #ef172c;
}

.rd-search-results-live .search-link {
	display: block;
}

.rd-search-results-live .search-list-item-all {
	margin-top: 18px;
	width: 100%;
}

.rd-search-results-live .search-submit {
	position: relative;
	overflow: hidden;
	z-index: 0;
	display: block;
	padding: 10px 20px;
	margin: 0 -1px;
	border-bottom-left-radius: 6px;
	border-bottom-right-radius: 6px;
	font-family: "Averia Libre";
	font-size: 12px;
	font-weight: 500;
	letter-spacing: 0.2em;
	text-transform: uppercase;
	text-align: center;
	color: #fff;
	background: #ef172c;
}

.rd-search-results-live .search-submit:hover {
	color: #fff;
	background: #353535;
}

.rd-search-results-live .match {
	display: none;
}

.not-empty ~ .rd-search-results-live {
	visibility: visible;
	opacity: 1;
}

.rd-search-results-live p {
	font-size: 14px;
}

.rd-search-results-live .search-list-item {
	padding: 0 15px;
}

.rd-search-results-live * + p {
	margin-top: 3px;
}

.rd-search-results-live .search-list-item + .search-list-item {
	margin-top: 17px;
}

.rd-search-results .search-list {
	counter-reset: li;
	text-align: left;
	padding-left: 0;
	font-size: 18px;
	list-style-type: none;
	overflow: hidden;
}

.rd-search-results .search-list li div {
	overflow: hidden;
	text-overflow: ellipsis;
	max-width: 100%;
	white-space: nowrap;
}

.rd-search-results .search-list li:only-child::before {
	display: none;
}

.rd-search-results .search-list-item {
	position: relative;
	padding-left: 40px;
	font-size: 16px;
	color: #9b9b9b;
}

.rd-search-results .search-list-item::before {
	content: counter(li, decimal) ".";
	counter-increment: li;
	position: absolute;
	left: 0;
	top: -0.1em;
	line-height: inherit;
}

.rd-search-results .search-title {
	position: relative;
	color: #ef172c;
}

.rd-search-results .search-title a {
	color: inherit;
}

.rd-search-results .search-title a:hover {
	color: #37020e;
}

.rd-search-results .search {
	color: #fff;
	padding: 0 .25em;
	background: #ef172c;
}

.rd-search-results .match {
	padding: 5px;
	font-size: 12px;
	line-height: 1.7;
	letter-spacing: .1em;
	text-transform: uppercase;
	color: #000;
}

.rd-search-results .match em {
	margin: 0;
	font-style: normal;
}

.rd-search-results * + .match {
	margin-top: 10px;
}

.rd-search-results .search-list-item + .search-list-item {
	margin-top: 40px;
}

* + .rd-search-results {
	margin-top: 40px;
}

@media (min-width: 768px) {
	.rd-search-results .search-list-item::before {
		top: 4px;
	}
	.rd-search-results * + p {
		margin-top: 12px;
	}
	* + .rd-search-results {
		margin-top: 55px;
	}
}

@media (min-width: 992px) {
	.rd-search-results .search-list-item {
		padding-left: 50px;
	}
	.rd-search-results * + p {
		margin-top: 17px;
	}
	.rd-search-results .search-list-item + .search-list-item {
		margin-top: 50px;
	}
}

@media (min-width: 1200px) {
	* + .rd-search-results {
		margin-top: 70px;
	}
}

@media (min-width: 1600px) {
	.rd-search-results .search-list-item + .search-list-item {
		margin-top: 70px;
	}
}

.rd-search-classic {
	position: relative;
}

.rd-search-classic .form-wrap-inner {
	position: relative;
}

.rd-search-classic .form-input {
	padding-right: 50px;
}

.rd-search-classic .form-input,
.rd-search-classic .form-label {
	letter-spacing: 0;
}

.rd-search-classic .rd-search-submit {
	background: none;
	border: none;
	display: inline-block;
	padding: 0;
	outline: none;
	outline-offset: 0;
	cursor: pointer;
	-webkit-appearance: none;
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	width: 50px;
	padding-top: 2px;
	padding-right: 3px;
	margin: 0;
	text-align: center;
	color: #aeb1be;
	font-size: 0;
	line-height: 0;
}

.rd-search-classic .rd-search-submit::-moz-focus-inner {
	border: none;
	padding: 0;
}

.rd-search-classic .rd-search-submit:before {
	position: relative;
	top: -1px;
	content: '\f43b';
	font: 400 20px 'Material Design Icons';
	line-height: 1;
	transition: .33s all ease;
}

.rd-search-classic .rd-search-submit:hover {
	color: #ef172c;
}

.rd-search.rd-search-inline {
	position: relative;
}

.rd-search.rd-search-inline .form-input {
	padding-right: 48px;
}

.rd-search.rd-search-inline .button-link {
	position: absolute;
	top: 50%;
	transform: translateY(-50%);
	width: 48px;
	right: 0;
	margin: 0;
	font-size: 21px;
	color: #aeb1be;
	transition: .33s;
}

.rd-search.rd-search-inline .button-link::before {
	display: block;
	margin: auto;
}

.rd-search.rd-search-inline .button-link:hover {
	color: #ef172c;
}

.rd-search.rd-search-inline.form-sm .form-input {
	padding-right: 40px;
}

.rd-search.rd-search-inline.form-sm .button-link {
	width: 40px;
	font-size: 18px;
}

.rd-search.rd-search-inline.form-lg .form-input {
	padding-right: 56px;
}

.rd-search.rd-search-inline.form-lg .button-link {
	width: 56px;
}

/*
*
* Isotope
*/
@keyframes sprite-animation {
	from {
		background-position: 0 0;
	}
}

[data-isotope-layout] {
	z-index: 0;
	display: block;
	overflow: hidden;
	min-height: 160px;
	margin-left: -15px;
	margin-right: -15px;
	transition: .4s all ease;
}

[data-isotope-layout]:after {
	content: '';
	position: absolute;
	top: 50%;
	left: 50%;
	width: 64px;
	height: 64px;
	margin-top: 15px;
	background-image: url("../images/isotope-loader.png");
	background-position: -1152px 0;
	animation: 0.7s sprite-animation steps(18) infinite;
	transition: .4s all ease;
	transform: translate3d(-50%, -50%, 0);
}

[data-isotope-layout] [class*="col-"] {
	display: block;
	opacity: 0;
	will-change: transform;
	backface-visibility: hidden;
	transition: .1s opacity ease-in;
}

[data-isotope-layout].isotope--loaded [class*="col-"] {
	opacity: 1;
}

[data-isotope-layout].isotope--loaded:after {
	opacity: 0;
	visibility: hidden;
}

.isotope.isotope-condensed {
	margin-left: 0;
	margin-right: 0;
	overflow: hidden;
}

.isotope.isotope-condensed [class*='col'] {
	padding: 0;
	margin: 0 0 30px 0;
}

@media (min-width: 576px) {
	.isotope.isotope-condensed [class*='col'] {
		margin: 0 -1px -1px 0;
	}
}

.isotope-filters-list {
	position: relative;
	font-size: 16px;
	margin-left: -20px;
	margin-bottom: -10px;
}

.isotope-filters-list > * {
	margin-left: 20px;
}

.isotope-filters-list::after {
	content: '';
	position: absolute;
	left: 20px;
	right: 0;
	bottom: 10px;
	border-bottom: 1px solid #e8e9ee;
}

.isotope-filters-list li {
	display: inline-block;
	margin-bottom: 10px;
}

.isotope-filters-list a {
	position: relative;
	display: block;
	z-index: 1;
	padding-bottom: 10px;
	color: #15191f;
}

.isotope-filters-list a::after {
	content: '';
	position: absolute;
	right: 0;
	bottom: 0;
	width: 0;
	height: 1px;
	transition: .4s;
	background: #ef172c;
}

.isotope-filters-list a:hover {
	color: #29293a;
}

.isotope-filters-list a.active {
	color: #29293a;
}

.isotope-filters-list a.active::after {
	right: auto;
	left: 0;
	width: 100%;
}

@media (min-width: 992px) {
	.isotope-filters-list {
		font-size: 18px;
		margin-left: -48px;
	}
	.isotope-filters-list > * {
		margin-left: 48px;
	}
	.isotope-filters-list::after {
		left: 45px;
	}
}

@media (min-width: 1200px) {
	.isotope-filters-list {
		font-size: 20px;
	}
}

@media (max-width: 767.98px) {
	.isotope-responsive {
		margin-left: -7px;
		margin-right: -7px;
		margin-bottom: -14px;
	}
	.isotope-responsive:empty {
		margin-bottom: 0;
	}
	.isotope-responsive > * {
		margin-bottom: 14px;
	}
	.isotope-responsive [class*='col'] {
		padding-left: 7px;
		padding-right: 7px;
	}
}

@media (min-width: 768px) {
	.isotope-responsive {
		margin-bottom: -30px;
	}
	.isotope-responsive:empty {
		margin-bottom: 0;
	}
	.isotope-responsive > * {
		margin-bottom: 30px;
	}
}

@media (max-width: 767.98px) {
	.isotope-filters-modern {
		position: relative;
		z-index: 10;
	}
	.isotope-filters-toggle {
		display: block;
		padding: 10px 20px;
		color: #fff;
		background: #ef172c;
		box-shadow: none;
		border: 0;
	}
	.isotope-filters-toggle .caret {
		position: relative;
		display: inline-block;
		margin-left: 5px;
		font-family: "FontAwesome";
		font-size: 14px;
		transition: .22s;
		will-change: transform;
	}
	.isotope-filters-toggle .caret::before {
		content: '\f107';
	}
	.isotope-filters-toggle.active .caret {
		transform: scale(1, -1);
	}
	.isotope-filters-list {
		position: absolute;
		top: 100%;
		left: 0;
		z-index: 10;
		min-width: 240px;
		margin: 5px 0 0 0;
		padding: 20px;
		border: 1px solid #e8e9ee;
		opacity: 0;
		visibility: hidden;
		background: #fff;
		transition: .3s ease-in;
	}
	.isotope-filters-list::after {
		display: none;
	}
	.isotope-filters-list.active {
		opacity: 1;
		visibility: visible;
	}
	.isotope-filters-list li {
		display: block;
		width: 100%;
		margin-left: 0;
	}
	.isotope-filters-list a {
		padding: 0;
	}
	.isotope-filters-list a::after {
		display: none;
	}
}

@media (min-width: 768px) {
	.isotope-filters-modern .isotope-filters-toggle {
		display: none;
	}
}

* + .isotope {
	margin-top: 30px;
}

@media (min-width: 768px) {
	* + .isotope {
		margin-top: 47px;
	}
}

.nav {
	display: block;
}

.tabs-custom {
	text-align: left;
}

.tabs-custom .nav-tabs {
	font-size: 0;
	line-height: 0;
	word-spacing: 0;
	border: 0;
}

.tabs-custom .nav-tabs:before, .tabs-custom .nav-tabs:after {
	display: none;
}

.tabs-custom .nav-item {
	float: none;
	border: 0;
	cursor: pointer;
	transition: .33s all ease;
}

.tabs-custom .nav-link {
	margin: 0;
	border-radius: 0;
	border: 0;
}

.tabs-custom .nav-link.active {
	cursor: default;
	border: 0;
}

.tab-content > .tab-pane {
	display: block;
	visibility: hidden;
	height: 0;
	overflow: hidden;
}

.tab-content > .active {
	visibility: visible;
	height: auto;
	overflow: visible;
}

.tabs-line .nav-tabs {
	position: relative;
}

.tabs-line .nav-link {
	font-size: 16px;
	line-height: 1.4;
	text-align: center;
	vertical-align: middle;
}

.tabs-line * + .tab-content {
	margin-top: 20px;
}

@media (max-width: 767.98px) {
	.tabs-line .nav-tabs {
		max-width: 100%;
		border: 1px solid #e8e9ee;
	}
	.tabs-line .nav-item {
		margin: -1px;
	}
	.tabs-line .nav-link {
		padding: 7px 10px;
		color: #15191f;
		background: transparent;
	}
	.tabs-line .nav-item + .nav-item .nav-link {
		border-top: 1px solid #e8e9ee;
	}
	.tabs-line .nav-link:hover,
	.tabs-line .nav-link.active {
		color: #fff;
		background: #ef172c;
		border-color: #ef172c;
	}
}

* + .tabs-line {
	margin-top: 30px;
}

.tabs-corporate .nav-tabs {
	position: relative;
	border: 1px solid #e5e7e9;
}

.tabs-corporate .nav-item {
	margin: -1px;
}

.tabs-corporate .nav-link {
	padding: 10px 10px;
	text-transform: uppercase;
	font-size: 12px;
	font-weight: 700;
	line-height: 1.4;
	color: #15191f;
	background: transparent;
	border-bottom: 1px solid #e5e7e9;
	text-align: center;
	vertical-align: middle;
}

.tabs-corporate .nav-link:first-child {
	border-top: 1px solid #e5e7e9;
}

.tabs-corporate .nav-link:hover,
.tabs-corporate .nav-link.active {
	color: #fff;
	background: #ef172c;
	border-color: #ef172c;
}

.tabs-corporate .tab-content {
	padding: 30px 0 0;
}

@media (min-width: 768px) {
	* + .tabs-line {
		margin-top: 40px;
	}
	.tabs-horizontal.tabs-corporate .nav-tabs {
		position: relative;
		width: 100%;
		display: block;
		transform: translate3d(0, -10px, 0);
		margin-bottom: -10px;
		margin-left: -5px;
		margin-right: -5px;
		text-align: center;
		border: 0;
		will-change: transform;
	}
	.tabs-horizontal.tabs-corporate .nav-tabs > * {
		margin-top: 10px;
		padding-left: 5px;
		padding-right: 5px;
	}
	.tabs-horizontal.tabs-corporate .nav-item {
		display: inline-block;
		will-change: transform;
	}
	.tabs-horizontal.tabs-corporate .nav-link {
		display: block;
		position: relative;
		z-index: 1;
		min-width: 130px;
		letter-spacing: .1em;
		padding: 13px 20px;
		border: 2px solid #e5e7e9;
	}
	.tabs-horizontal.tabs-corporate .nav-link, .tabs-horizontal.tabs-corporate .nav-link::before {
		transition-timing-function: cubic-bezier(0.2, 1, 0.3, 1);
	}
	.tabs-horizontal.tabs-corporate .nav-link::before {
		content: '';
		position: absolute;
		top: -1px;
		left: -1px;
		width: calc(100% + 2px);
		height: calc(100% + 2px);
		z-index: -1;
		opacity: 0;
		transform: scale3d(0.7, 1, 1);
		transition: transform 0.4s, opacity 0.4s;
		transition-timing-function: cubic-bezier(0.2, 1, 0.3, 1);
		background: #ef172c;
	}
	.tabs-horizontal.tabs-corporate .nav-link.active,
	.tabs-horizontal.tabs-corporate .nav-link:hover {
		color: #fff;
		border-color: #ef172c;
		background-color: transparent;
	}
	.tabs-horizontal.tabs-corporate .nav-link.active::before,
	.tabs-horizontal.tabs-corporate .nav-link:hover::before {
		opacity: 1;
		transform: translate3d(0, 0, 0) scale3d(1, 1, 1);
	}
	.tabs-horizontal.tabs-line .nav-tabs {
		transform: translateY(-20px);
		margin-bottom: -20px;
		border: 0;
		border-bottom: 1px solid #e8e9ee;
	}
	.tabs-horizontal.tabs-line .nav-item {
		display: inline-block;
		margin-top: 20px;
	}
	.tabs-horizontal.tabs-line .nav-item:not(:last-child) {
		margin-right: 52px;
	}
	.tabs-horizontal.tabs-line .nav-link {
		position: relative;
		padding: 0 0 13px 0;
		font-size: 20px;
		background-color: transparent;
		color: #9b9b9b;
		border: 0;
	}
	.tabs-horizontal.tabs-line .nav-link::after {
		content: '';
		position: absolute;
		bottom: 0;
		right: 0;
		height: 1px;
		width: 0;
		background: #ef172c;
		transition: .22s ease;
	}
	.tabs-horizontal.tabs-line .nav-link.active,
	.tabs-horizontal.tabs-line .nav-link:hover {
		color: #29293a;
	}
	.tabs-horizontal.tabs-line .nav-link.active::after {
		right: auto;
		left: 0;
		width: 100%;
	}
	.tabs-horizontal.tabs-line * + .tab-content {
		margin-top: 25px;
	}
	.tabs-vertical {
		display: flex;
		align-items: flex-start;
	}
	.tabs-vertical .nav-tabs {
		display: flex;
		flex-direction: column;
		align-items: stretch;
		flex-shrink: 0;
		max-width: 50%;
	}
	.tabs-vertical .nav-item {
		border: 0;
		width: 100%;
		text-align: left;
	}
	.tabs-vertical .nav-link.active,
	.tabs-vertical .nav-link:hover {
		box-shadow: 0 9px 21px 0 rgba(30, 30, 30, 0.13);
	}
	.tabs-vertical .tab-content {
		flex-grow: 1;
	}
	.tabs-vertical.tabs-corporate .nav-tabs {
		width: auto;
		min-width: 260px;
		border: 0;
	}
	.tabs-vertical.tabs-corporate .nav-item {
		margin: 0;
	}
	.tabs-vertical.tabs-corporate .nav-link {
		position: relative;
		padding: 17px 30px;
		border: 0;
		overflow: hidden;
		text-align: left;
	}
	.tabs-vertical.tabs-corporate .nav-item + .nav-item {
		margin-top: 2px;
	}
	.tabs-vertical.tabs-corporate .tab-content {
		padding: 0 0 0 30px;
	}
}

@media (min-width: 992px) {
	.tabs-horizontal.tabs-corporate .tab-content {
		padding: 60px 30px 0;
	}
	.tabs-vertical.tabs-corporate .tab-content {
		padding: 0 0 0 45px;
	}
}

.card-group-custom {
	margin-bottom: 0;
}

.card-group-custom .card-header + .collapse > .card-body,
.card-group-custom .card-header + .collapse > .list-group {
	border-top: 0;
}

.card-group-custom .card + .card {
	margin-top: 0;
}

.card-title {
	margin-bottom: 0;
}

.card-header {
	background-color: transparent;
}

.card-custom {
	display: block;
	margin: 0;
	background: inherit;
	border: 0;
	border-radius: 0;
	box-shadow: none;
	text-align: left;
}

.card-custom a {
	display: block;
}

.card-custom .card-header {
	padding: 0;
	border-bottom: 0;
	border-top-left-radius: 0;
	border-top-right-radius: 0;
}

.card-custom .card-body {
	padding: 0;
	border: 0;
}

* + .card-group-custom {
	margin-top: 30px;
}

@media (min-width: 768px) {
	* + .card-group-custom {
		margin-top: 40px;
	}
}

/* 
* Card corporate
*/
.card-corporate {
	border-top: 1px solid #f5f6fa;
	text-align: left;
}

.card-corporate:last-child {
	border-bottom: 1px solid #f5f6fa;
}

.card-corporate .card-collapse {
	background: #fff;
}

.card-corporate .card-title a {
	position: relative;
	z-index: 1;
	padding: 15px 40px 15px 70px;
	font-size: 17px;
	line-height: 1.5;
	letter-spacing: 0;
	color: #29293a;
	transition: 1.3s all ease;
}

.card-corporate .card-title a[aria-expanded='true'], .card-corporate .card-title a:hover {
	color: #ef172c;
}

.card-corporate .card-title a .card-arrow {
	transition: .33s;
}

.card-corporate .card-title a.collapsed {
	color: #29293a;
	border-bottom-width: 0;
}

.card-corporate .card-title a.collapsed .card-arrow::before {
	opacity: 1;
}

.card-corporate .card-title a.collapsed .card-arrow::after {
	opacity: 0;
}

.card-corporate .card-arrow {
	position: absolute;
	top: 16px;
	left: 13px;
	z-index: 2;
	width: 20px;
	height: 20px;
	color: #ef172c;
	transition: .33s all ease;
	text-align: center;
}

.card-corporate .card-arrow::before, .card-corporate .card-arrow::after {
	position: absolute;
	z-index: 4;
	font-family: 'Material Design Icons';
	font-size: 24px;
	line-height: 1;
	transition: .22s;
}

.card-corporate .card-arrow::before {
	content: '\f505';
	opacity: 0;
}

.card-corporate .card-arrow::after {
	content: '\f466';
	opacity: 1;
}

.card-corporate .card-collapse {
	position: relative;
	z-index: 1;
	color: #15191f;
}

.card-corporate .card-body {
	padding: 2px 44px 25px 70px;
}

@media (max-width: 767.98px) {
	.card-corporate .card-arrow {
		left: 0;
	}
	.card-corporate .card-title a,
	.card-corporate .card-body {
		padding-left: 50px;
	}
}

@media (min-width: 768px) {
	.card-corporate .card-title a {
		font-size: 20px;
		line-height: 1.4;
	}
	.card-corporate .card-arrow {
		top: 18px;
	}
}

/*
*
* Tooltop Custom
*/
.tooltip {
	font-size: 16px;
	line-height: 1.2;
}

.tooltip-inner {
	background-color: #ef172c;
}

.bs-tooltip-top .arrow::before {
	border-top-color: #ef172c;
}

.bs-tooltip-right .arrow::before {
	border-right-color: #ef172c;
}

.bs-tooltip-bottom .arrow::before {
	border-bottom-color: #ef172c;
}

.bs-tooltip-left .arrow::before {
	border-left-color: #ef172c;
}

@media (min-width: 1200px) {
	.tooltip-inner {
		padding: 9px 18px;
	}
}

/*
*
* Modal Custom
*/
.modal {
	display: flex !important;
	padding: 30px 15px 7vh;
	visibility: hidden;
}

.modal .close {
	cursor: pointer;
	color: #15191f;
	transition: .22s;
}

.modal .close span::before {
	content: '\f24c';
	font-family: 'Material Design Icons';
}

.modal .close:hover {
	color: #29293a;
}

.modal.show {
	visibility: visible;
}

.modal.fade .modal-dialog {
	transform: translate3d(0, -30px, 0);
}

.modal.show .modal-dialog {
	transform: translate3d(0, 0, 0);
}

.modal-dialog {
	display: flex;
	align-items: flex-start;
	justify-content: center;
	margin: 0 auto;
}

.modal-content {
	/*height: 100%;*/
	border-radius: 0px;
}

.modal-body {
	height: 100%;
	overflow-y: auto;
}

@media (min-width: 768px) {
	.modal-header,
	.modal-body {
		padding-left: 30px;
		padding-right: 30px;
	}
	.modal-header {
		padding-top: 20px;
		padding-bottom: 20px;
	}
	.modal-body {
		padding-top: 30px;
		padding-bottom: 30px;
	}
	.modal-dialog {
		max-width: 800px;
	}
}

/*
*
* Progress Bars
*/
.progress-linear {
	position: relative;
	text-align: left;
}

html .progress-linear-header {
	display: flex;
	align-items: center;
	justify-content: space-between;
	transform: translate3d(0, -10px, 0);
	margin-bottom: -10px;
	margin-left: -5px;
	margin-right: -5px;
}

html .progress-linear-header > * {
	margin-top: 10px;
	padding-left: 5px;
	padding-right: 5px;
}

html .progress-linear-header > * {
	margin-bottom: 0;
}

.progress-linear-body {
	height: 2px;
	background: #f5f6fa;
}

.progress-linear-bar {
	width: 0;
	height: inherit;
	background: #ef172c;
	border-radius: inherit;
	transition: 1s all ease-in-out;
}

.progress-linear-counter::after {
	content: "%";
}

* + .progress-linear-body {
	margin-top: 6px;
}

.progress-linear + .progress-linear {
	margin-top: 15px;
}

* + .progress-linear-wrap {
	margin-top: 10px;
}

@media (min-width: 992px) {
	.progress-linear + .progress-linear {
		margin-top: 35px;
	}
	* + .progress-linear-wrap {
		margin-top: 30px;
	}
}

/*
*
* Time Circles
*/
.time_circles {
	position: relative;
	width: 100%;
}

.time_circles > div {
	position: absolute;
	top: 0 !important;
	bottom: 0;
	display: flex;
	align-items: center;
	flex-wrap: wrap;
	justify-content: center;
	margin-top: -10px;
	text-align: center;
}

@media (min-width: 1200px) {
	#DateCountdown {
		width: 100%;
	}
}

.time_circles > div > h4 {
	position: absolute;
	left: 0;
	top: calc(100% + 14px);
	right: 0;
	transform: translateY(-100%);
	margin: 0;
	padding: 0;
	text-align: center;
	font-family: "Averia Libre";
	font-size: 14px !important;
	line-height: 1.2 !important;
	color: #29293a;
}

.time_circles > div > h4 + * {
	margin-top: 0;
}

@media (min-width: 576px) {
	.time_circles > div > h4 {
		font-size: 16px !important;
	}
}

.time_circles > div > span {
	display: block;
	text-align: center;
	letter-spacing: 0;
	font-size: 24px !important;
	font-weight: 700;
	line-height: 1 !important;
	color: #111111;
}

.context-dark .time_circles > div > span, .bg-gray-700 .time_circles > div > span, .bg-gray-800 .time_circles > div > span, .bg-primary .time_circles > div > span, .bg-secondary .time_circles > div > span, .bg-primary-darker .time_circles > div > span {
	color: #fff;
}

.context-dark .time_circles > div > h4, .bg-gray-700 .time_circles > div > h4, .bg-gray-800 .time_circles > div > h4, .bg-primary .time_circles > div > h4, .bg-secondary .time_circles > div > h4, .bg-primary-darker .time_circles > div > h4 {
	color: #fff;
}

.countdown-wrap {
	max-width: 530px;
	padding-bottom: 20px;
}

* + .countdown-wrap {
	margin-top: 35px;
}

.countdown-wrap + .button {
	margin-top: 40px;
}

/*
* jQuery mousewheel plugin
*/
/*
------------------------------------------------------------------------------------------------------------------------
1. BASIC STYLE
------------------------------------------------------------------------------------------------------------------------
*/
.mCustomScrollbar {
	-ms-touch-action: pinch-zoom;
	touch-action: pinch-zoom;
	/* direct pointer events to js */
}

.mCustomScrollbar.mCS_no_scrollbar, .mCustomScrollbar.mCS_touch_action {
	-ms-touch-action: auto;
	touch-action: auto;
}

.mCustomScrollBox {
	/* contains plugin's markup */
	position: relative;
	overflow: hidden;
	height: 100%;
	max-width: 100%;
	outline: none;
	direction: ltr;
}

.mCSB_container {
	/* contains the original content */
	overflow: hidden;
	width: auto;
	height: auto;
}

/*
------------------------------------------------------------------------------------------------------------------------
2. VERTICAL SCROLLBAR
y-axis
------------------------------------------------------------------------------------------------------------------------
*/
.mCSB_inside > .mCSB_container {
	margin-right: 30px;
}

.mCSB_container.mCS_no_scrollbar_y.mCS_y_hidden {
	margin-right: 0;
}

/* non-visible scrollbar */
.mCS-dir-rtl-custom > .mCSB_inside > .mCSB_container {
	/* RTL direction/left-side scrollbar */
	margin-right: 0;
	margin-left: 30px;
}

.mCS-dir-rtl-custom > .mCSB_inside > .mCSB_container.mCS_no_scrollbar_y.mCS_y_hidden {
	margin-left: 0;
}

/* RTL direction/left-side scrollbar */
.mCSB_scrollTools {
	/* contains scrollbar markup (draggable element, dragger rail, buttons etc.) */
	position: absolute;
	width: 16px;
	height: auto;
	left: auto;
	top: 0;
	right: 0;
	bottom: 0;
}

.mCSB_outside + .mCSB_scrollTools {
	right: -26px;
}

/* scrollbar position: outside */
.mCS-dir-rtl-custom > .mCSB_inside > .mCSB_scrollTools,
.mCS-dir-rtl-custom > .mCSB_outside + .mCSB_scrollTools {
	/* RTL direction/left-side scrollbar */
	right: auto;
	left: 0;
}

.mCS-dir-rtl-custom > .mCSB_outside + .mCSB_scrollTools {
	left: -26px;
}

/* RTL direction/left-side scrollbar (scrollbar position: outside) */
.mCSB_scrollTools .mCSB_draggerContainer {
	/* contains the draggable element and dragger rail markup */
	position: absolute;
	top: 0;
	left: 0;
	bottom: 0;
	right: 0;
	height: auto;
}

.mCSB_scrollTools a + .mCSB_draggerContainer {
	margin: 20px 0;
}

.mCSB_scrollTools .mCSB_draggerRail {
	width: 16px;
	height: 100%;
	margin: 0 auto;
	border-radius: 0;
}

.mCSB_scrollTools .mCSB_dragger {
	/* the draggable element */
	cursor: pointer;
	width: 100%;
	height: 30px;
	/* minimum dragger height */
	z-index: 1;
}

.mCSB_scrollTools .mCSB_dragger .mCSB_dragger_bar {
	/* the dragger element */
	position: relative;
	width: 16px;
	height: 100%;
	margin: 0 auto;
	border-radius: 0;
	text-align: center;
}

.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_dragger.mCSB_dragger_onDrag_expanded .mCSB_dragger_bar,
.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_draggerContainer:hover .mCSB_dragger .mCSB_dragger_bar {
	width: 12px;
	/* auto-expanded scrollbar */
}

.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_dragger.mCSB_dragger_onDrag_expanded + .mCSB_draggerRail,
.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_draggerContainer:hover .mCSB_draggerRail {
	width: 8px;
	/* auto-expanded scrollbar */
}

.mCSB_scrollTools .mCSB_buttonUp,
.mCSB_scrollTools .mCSB_buttonDown {
	display: block;
	position: absolute;
	height: 20px;
	width: 100%;
	overflow: hidden;
	margin: 0 auto;
	cursor: pointer;
}

.mCSB_scrollTools .mCSB_buttonDown {
	bottom: 0;
}

/*
------------------------------------------------------------------------------------------------------------------------
3. HORIZONTAL SCROLLBAR
x-axis
------------------------------------------------------------------------------------------------------------------------
*/
.mCSB_horizontal.mCSB_inside > .mCSB_container {
	margin-right: 0;
	margin-bottom: 30px;
}

.mCSB_horizontal.mCSB_outside > .mCSB_container {
	min-height: 100%;
}

.mCSB_horizontal > .mCSB_container.mCS_no_scrollbar_x.mCS_x_hidden {
	margin-bottom: 0;
}

/* non-visible scrollbar */
.mCSB_scrollTools.mCSB_scrollTools_horizontal {
	width: auto;
	height: 16px;
	top: auto;
	right: 0;
	bottom: 0;
	left: 0;
}

.mCustomScrollBox + .mCSB_scrollTools.mCSB_scrollTools_horizontal,
.mCustomScrollBox + .mCSB_scrollTools + .mCSB_scrollTools.mCSB_scrollTools_horizontal {
	bottom: -26px;
}

/* scrollbar position: outside */
.mCSB_scrollTools.mCSB_scrollTools_horizontal a + .mCSB_draggerContainer {
	margin: 0 20px;
}

.mCSB_scrollTools.mCSB_scrollTools_horizontal .mCSB_draggerRail {
	width: 100%;
	height: 2px;
	margin: 7px 0;
}

.mCSB_scrollTools.mCSB_scrollTools_horizontal .mCSB_dragger {
	width: 30px;
	/* minimum dragger width */
	height: 100%;
	left: 0;
}

.mCSB_scrollTools.mCSB_scrollTools_horizontal .mCSB_dragger .mCSB_dragger_bar {
	width: 100%;
	height: 4px;
	margin: 6px auto;
}

.mCSB_scrollTools_horizontal.mCSB_scrollTools_onDrag_expand .mCSB_dragger.mCSB_dragger_onDrag_expanded .mCSB_dragger_bar,
.mCSB_scrollTools_horizontal.mCSB_scrollTools_onDrag_expand .mCSB_draggerContainer:hover .mCSB_dragger .mCSB_dragger_bar {
	height: 12px;
	/* auto-expanded scrollbar */
	margin: 2px auto;
}

.mCSB_scrollTools_horizontal.mCSB_scrollTools_onDrag_expand .mCSB_dragger.mCSB_dragger_onDrag_expanded + .mCSB_draggerRail,
.mCSB_scrollTools_horizontal.mCSB_scrollTools_onDrag_expand .mCSB_draggerContainer:hover .mCSB_draggerRail {
	height: 8px;
	/* auto-expanded scrollbar */
	margin: 4px 0;
}

.mCSB_scrollTools.mCSB_scrollTools_horizontal .mCSB_buttonLeft,
.mCSB_scrollTools.mCSB_scrollTools_horizontal .mCSB_buttonRight {
	display: block;
	position: absolute;
	width: 20px;
	height: 100%;
	overflow: hidden;
	margin: 0 auto;
	cursor: pointer;
}

.mCSB_scrollTools.mCSB_scrollTools_horizontal .mCSB_buttonLeft {
	left: 0;
}

.mCSB_scrollTools.mCSB_scrollTools_horizontal .mCSB_buttonRight {
	right: 0;
}

/*
------------------------------------------------------------------------------------------------------------------------
4. VERTICAL AND HORIZONTAL SCROLLBARS
yx-axis
------------------------------------------------------------------------------------------------------------------------
*/
.mCSB_container_wrapper {
	position: absolute;
	height: auto;
	width: auto;
	overflow: hidden;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	margin-right: 30px;
	margin-bottom: 30px;
}

.mCSB_container_wrapper > .mCSB_container {
	padding-right: 30px;
	padding-bottom: 30px;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}

.mCSB_vertical_horizontal > .mCSB_scrollTools.mCSB_scrollTools_vertical {
	bottom: 20px;
}

.mCSB_vertical_horizontal > .mCSB_scrollTools.mCSB_scrollTools_horizontal {
	right: 20px;
}

/* non-visible horizontal scrollbar */
.mCSB_container_wrapper.mCS_no_scrollbar_x.mCS_x_hidden + .mCSB_scrollTools.mCSB_scrollTools_vertical {
	bottom: 0;
}

/* non-visible vertical scrollbar/RTL direction/left-side scrollbar */
.mCSB_container_wrapper.mCS_no_scrollbar_y.mCS_y_hidden + .mCSB_scrollTools ~ .mCSB_scrollTools.mCSB_scrollTools_horizontal,
.mCS-dir-rtl-custom > .mCustomScrollBox.mCSB_vertical_horizontal.mCSB_inside > .mCSB_scrollTools.mCSB_scrollTools_horizontal {
	right: 0;
}

/* RTL direction/left-side scrollbar */
.mCS-dir-rtl-custom > .mCustomScrollBox.mCSB_vertical_horizontal.mCSB_inside > .mCSB_scrollTools.mCSB_scrollTools_horizontal {
	left: 20px;
}

/* non-visible scrollbar/RTL direction/left-side scrollbar */
.mCS-dir-rtl-custom > .mCustomScrollBox.mCSB_vertical_horizontal.mCSB_inside > .mCSB_container_wrapper.mCS_no_scrollbar_y.mCS_y_hidden + .mCSB_scrollTools ~ .mCSB_scrollTools.mCSB_scrollTools_horizontal {
	left: 0;
}

.mCS-dir-rtl-custom > .mCSB_inside > .mCSB_container_wrapper {
	/* RTL direction/left-side scrollbar */
	margin-right: 0;
	margin-left: 30px;
}

.mCSB_container_wrapper.mCS_no_scrollbar_y.mCS_y_hidden > .mCSB_container {
	padding-right: 0;
}

.mCSB_container_wrapper.mCS_no_scrollbar_x.mCS_x_hidden > .mCSB_container {
	padding-bottom: 0;
}

.mCustomScrollBox.mCSB_vertical_horizontal.mCSB_inside > .mCSB_container_wrapper.mCS_no_scrollbar_y.mCS_y_hidden {
	margin-right: 0;
	/* non-visible scrollbar */
	margin-left: 0;
}

/* non-visible horizontal scrollbar */
.mCustomScrollBox.mCSB_vertical_horizontal.mCSB_inside > .mCSB_container_wrapper.mCS_no_scrollbar_x.mCS_x_hidden {
	margin-bottom: 0;
}

/*
------------------------------------------------------------------------------------------------------------------------
5. TRANSITIONS
------------------------------------------------------------------------------------------------------------------------
*/
.mCSB_scrollTools,
.mCSB_scrollTools .mCSB_dragger .mCSB_dragger_bar,
.mCSB_scrollTools .mCSB_buttonUp,
.mCSB_scrollTools .mCSB_buttonDown,
.mCSB_scrollTools .mCSB_buttonLeft,
.mCSB_scrollTools .mCSB_buttonRight {
	-webkit-transition: opacity .2s ease-in-out, background-color .2s ease-in-out;
	-moz-transition: opacity .2s ease-in-out, background-color .2s ease-in-out;
	-o-transition: opacity .2s ease-in-out, background-color .2s ease-in-out;
	transition: opacity .2s ease-in-out, background-color .2s ease-in-out;
}

.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_dragger_bar,
.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_draggerRail,
.mCSB_scrollTools_horizontal.mCSB_scrollTools_onDrag_expand .mCSB_dragger_bar,
.mCSB_scrollTools_horizontal.mCSB_scrollTools_onDrag_expand .mCSB_draggerRail {
	-webkit-transition: width .2s ease-out .2s, height .2s ease-out .2s, margin-left .2s ease-out .2s, margin-right .2s ease-out .2s, margin-top .2s ease-out .2s, margin-bottom .2s ease-out .2s, opacity .2s ease-in-out, background-color .2s ease-in-out;
	-moz-transition: width .2s ease-out .2s, height .2s ease-out .2s, margin-left .2s ease-out .2s, margin-right .2s ease-out .2s, margin-top .2s ease-out .2s, margin-bottom .2s ease-out .2s, opacity .2s ease-in-out, background-color .2s ease-in-out;
	-o-transition: width .2s ease-out .2s, height .2s ease-out .2s, margin-left .2s ease-out .2s, margin-right .2s ease-out .2s, margin-top .2s ease-out .2s, margin-bottom .2s ease-out .2s, opacity .2s ease-in-out, background-color .2s ease-in-out;
	transition: width .2s ease-out .2s, height .2s ease-out .2s, margin-left .2s ease-out .2s, margin-right .2s ease-out .2s, margin-top .2s ease-out .2s, margin-bottom .2s ease-out .2s, opacity .2s ease-in-out, background-color .2s ease-in-out;
}

/*
------------------------------------------------------------------------------------------------------------------------
6. SCROLLBAR COLORS, OPACITY AND BACKGROUNDS
------------------------------------------------------------------------------------------------------------------------
*/
/*
----------------------------------------
6.1 THEMES
----------------------------------------
*/
/* default theme ("light") */
.mCSB_scrollTools .mCSB_draggerRail {
	background-color: transparent;
}

.mCSB_scrollTools .mCSB_dragger .mCSB_dragger_bar {
	background-color: #f2f3f8;
}

.mCSB_scrollTools .mCSB_dragger:hover .mCSB_dragger_bar,
.mCSB_scrollTools .mCSB_dragger:active .mCSB_dragger_bar,
.mCSB_scrollTools .mCSB_dragger.mCSB_dragger_onDrag .mCSB_dragger_bar {
	background-color: #d1d4e6;
}

.mCSB_scrollTools .mCSB_buttonUp,
.mCSB_scrollTools .mCSB_buttonDown,
.mCSB_scrollTools .mCSB_buttonLeft,
.mCSB_scrollTools .mCSB_buttonRight {
	background-image: url(../images/mCSB_buttons.png);
	/* css sprites */
	background-repeat: no-repeat;
	opacity: 0.4;
}

.mCSB_scrollTools .mCSB_buttonUp {
	background-position: 0 0;
}

.mCSB_scrollTools .mCSB_buttonDown {
	background-position: 0 -20px;
}

.mCSB_scrollTools .mCSB_buttonLeft {
	background-position: 0 -40px;
}

.mCSB_scrollTools .mCSB_buttonRight {
	background-position: 0 -56px;
}

.mCSB_scrollTools .mCSB_buttonUp:hover,
.mCSB_scrollTools .mCSB_buttonDown:hover,
.mCSB_scrollTools .mCSB_buttonLeft:hover,
.mCSB_scrollTools .mCSB_buttonRight:hover {
	opacity: 0.75;
}

.mCSB_scrollTools .mCSB_buttonUp:active,
.mCSB_scrollTools .mCSB_buttonDown:active,
.mCSB_scrollTools .mCSB_buttonLeft:active,
.mCSB_scrollTools .mCSB_buttonRight:active {
	opacity: 0.9;
}

/* theme: "dark" */
.mCS-dark.mCSB_scrollTools .mCSB_draggerRail {
	background-color: #000000;
	background-color: rgba(0, 0, 0, 0.15);
}

.mCS-dark.mCSB_scrollTools .mCSB_dragger .mCSB_dragger_bar {
	background-color: #000000;
	background-color: rgba(0, 0, 0, 0.75);
}

.mCS-dark.mCSB_scrollTools .mCSB_dragger:hover .mCSB_dragger_bar {
	background-color: rgba(0, 0, 0, 0.85);
}

.mCS-dark.mCSB_scrollTools .mCSB_dragger:active .mCSB_dragger_bar,
.mCS-dark.mCSB_scrollTools .mCSB_dragger.mCSB_dragger_onDrag .mCSB_dragger_bar {
	background-color: rgba(0, 0, 0, 0.9);
}

.mCS-dark.mCSB_scrollTools .mCSB_buttonUp {
	background-position: -80px 0;
}

.mCS-dark.mCSB_scrollTools .mCSB_buttonDown {
	background-position: -80px -20px;
}

.mCS-dark.mCSB_scrollTools .mCSB_buttonLeft {
	background-position: -80px -40px;
}

.mCS-dark.mCSB_scrollTools .mCSB_buttonRight {
	background-position: -80px -56px;
}

/*
*
* Owl Carousel
*/
.owl-carousel .animated {
	animation-duration: 1000ms;
	animation-fill-mode: both;
}

.owl-carousel .owl-animated-in {
	z-index: 0;
}

.owl-carousel .owl-animated-out {
	z-index: 1;
}

.owl-carousel .fadeOut {
	animation-name: fadeOut;
}

@keyframes fadeOut {
	0% {
		opacity: 1;
	}
	100% {
		opacity: 0;
	}
}

/* 
 * 	Owl Carousel - Auto Height Plugin
 */
.owl-height {
	transition: height 500ms ease-in-out;
}

/* 
 *  Core Owl Carousel CSS File
 */
.owl-carousel {
	display: none;
	width: 100%;
	-webkit-tap-highlight-color: transparent;
	/* position relative and z-index fix webkit rendering fonts issue */
	position: relative;
	z-index: 1;
}

.owl-carousel .owl-stage {
	position: relative;
	-ms-touch-action: pan-Y;
}

.owl-carousel .owl-stage:after {
	content: ".";
	display: block;
	clear: both;
	visibility: hidden;
	line-height: 0;
	height: 0;
}

.owl-carousel .owl-stage-outer {
	position: relative;
	overflow: hidden;
	/* fix for flashing background */
	-webkit-transform: translate3d(0px, 0px, 0px);
}

.owl-carousel .owl-controls .owl-nav .owl-prev,
.owl-carousel .owl-controls .owl-nav .owl-next,
.owl-carousel .owl-controls .owl-dot {
	cursor: pointer;
	user-select: none;
}

.owl-carousel.owl-loaded {
	display: block;
}

.owl-carousel.owl-loading {
	opacity: 0;
	display: block;
}

.owl-carousel.owl-hidden {
	opacity: 0;
}

.owl-carousel .owl-refresh .owl-item {
	display: none;
}

.owl-carousel .owl-item {
	position: relative;
	min-height: 1px;
	float: left;
	-webkit-tap-highlight-color: transparent;
	-webkit-touch-callout: none;
}

.owl-carousel .owl-grab {
	cursor: move;
	cursor: -webkit-grab;
	cursor: grab;
}

.owl-carousel.owl-rtl {
	direction: rtl;
}

.owl-carousel.owl-rtl .owl-item {
	float: right;
}

/* No Js */
.no-js .owl-carousel {
	display: block;
}

/* 
 * 	Owl Carousel - Lazy Load Plugin
 */
.owl-carousel .owl-item .owl-lazy {
	opacity: 0;
	transition: opacity 400ms ease;
}

/* 
 * 	Owl Carousel - Video Plugin
 */
.owl-carousel .owl-video-wrapper {
	position: relative;
	height: 100%;
	background: #000000;
}

.owl-carousel .owl-video-play-icon {
	position: absolute;
	height: 80px;
	width: 80px;
	left: 50%;
	top: 50%;
	margin-left: -40px;
	margin-top: -40px;
	font: 400 40px/80px 'FontAwesome';
	cursor: pointer;
	z-index: 1;
	transition: scale 100ms ease;
}

.owl-carousel .owl-video-play-icon:before {
	content: '\f144';
}

.owl-carousel .owl-video-play-icon:hover {
	transform: scale(1.3);
}

.owl-carousel .owl-video-playing .owl-video-tn,
.owl-carousel .owl-video-playing .owl-video-play-icon {
	display: none;
}

.owl-carousel .owl-video-tn {
	opacity: 0;
	height: 100%;
	background-position: center center;
	background-repeat: no-repeat;
	background-size: contain;
	transition: opacity 400ms ease;
}

.owl-carousel .owl-video-frame {
	position: relative;
	z-index: 1;
}

/*
 * Owl Navigation
 */
.owl-nav.disabled {
	display: none !important;
}

.owl-prev,
.owl-next {
	position: absolute;
	top: 50%;
	transform: translateY(-50%);
	font: 400 46px/50px 'FontAwesome';
	color: #aeb1be;
}

.owl-prev:hover,
.owl-next:hover {
	color: #ef172c;
}

.owl-prev {
	left: 0;
}

.owl-prev::before {
	content: '\f104';
}

.owl-next {
	right: 0;
}

.owl-next::before {
	content: '\f105';
}

/*
 * Owl Pagination
 */
.owl-dots {
	margin-top: 10px;
}

.owl-dots.disabled {
	display: none !important;
}

@media (min-width: 576px) {
	.owl-dots {
		margin-top: 25px;
	}
}

button.owl-dot {
	background: none;
	border: none;
	display: inline-block;
	padding: 0;
	outline: none;
	outline-offset: 0;
	cursor: pointer;
	-webkit-appearance: none;
}

button.owl-dot::-moz-focus-inner {
	border: none;
	padding: 0;
}

.owl-dot {
	position: relative;
	display: inline-flex;
	align-items: center;
	justify-content: center;
	vertical-align: middle;
	width: 14px;
	height: 14px;
	border-radius: 50%;
	margin-left: 14px;
	margin-right: 14px;
	text-align: center;
	outline: none;
	cursor: pointer;
}

.owl-dot::before {
	content: '';
	display: block;
	width: 100%;
	height: 100%;
	transform: scale3d(0.56, 0.56, 0.56);
	background: #e8e9ee;
	border-radius: inherit;
	transition: .2s;
}

.owl-dot:only-child {
	display: none;
}

.owl-dot:hover::before, .owl-dot.active::before {
	transform: scale3d(1, 1, 1);
	background-color: #ef172c;
}

* + .owl-carousel {
	margin-top: 30px;
}

.owl-carousel-1 {
	text-align: center;
}

.owl-carousel-1 .owl-stage {
	position: relative;
	display: flex;
	align-items: center;
}

.owl-carousel-centered-pagination .owl-dots {
	text-align: center;
}

.owl-carousel-indigo {
	position: relative;
	overflow: hidden;
	max-width: 100vw;
	padding: 0 15px;
	margin-left: auto;
	margin-right: auto;
	pointer-events: none;
}

.owl-carousel-indigo, .owl-carousel-indigo * {
	backface-visibility: hidden;
}

.owl-carousel-indigo .owl-stage-outer {
	padding: 23px;
	margin: -23px;
}

.owl-carousel-indigo .owl-item.active {
	pointer-events: auto;
}

.owl-carousel-indigo .owl-dots {
	pointer-events: auto;
}

.owl-carousel-indigo * + .owl-dots {
	margin-top: 25px;
}

@media (max-width: 575.98px) {
	.owl-carousel-indigo .owl-dot {
		width: 11px;
		height: 11px;
		margin: 0 6px;
	}
}

@media (min-width: 768px) {
	.owl-carousel-indigo {
		padding: 0 0;
	}
	.owl-carousel-indigo * + .owl-dots {
		margin-top: 60px;
	}
}

.owl-carousel-dots-space .owl-dots {
	margin-bottom: 25px;
}

@media (min-width: 1200px) {
	.owl-style-1 .owl-dots {
		margin-top: 65px;
	}
}

.lg-sub-html, .lg-toolbar {
	background-color: rgba(0, 0, 0, 0.45);
}

@font-face {
	font-family: lg;
	src: url(../fonts/lg.eot?n1z373);
	src: url(../fonts/lg.eot?#iefixn1z373) format("embedded-opentype"), url(../fonts/lg.woff?n1z373) format("woff"), url(../fonts/lg.ttf?n1z373) format("truetype"), url(../fonts/lg.svg?n1z373#lg) format("svg");
	font-weight: 400;
	font-style: normal;
}

.lg-icon {
	font-family: lg;
	speak: none;
	font-style: normal;
	font-weight: 400;
	font-variant: normal;
	text-transform: none;
	line-height: 1;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}

.lg-actions .lg-next, .lg-actions .lg-prev {
	background-color: rgba(0, 0, 0, 0.45);
	border-radius: 2px;
	color: #999;
	cursor: pointer;
	display: block;
	font-size: 22px;
	margin-top: -10px;
	padding: 8px 10px 9px;
	position: absolute;
	top: 50%;
	z-index: 1180;
	border: none;
	outline: 0;
}

.lg-actions .lg-next.disabled, .lg-actions .lg-prev.disabled {
	pointer-events: none;
	opacity: .5;
}

.lg-actions .lg-next:hover, .lg-actions .lg-prev:hover {
	color: #fff;
}

.lg-actions .lg-next {
	right: 20px;
}

.lg-actions .lg-next:before {
	content: "\e095";
}

.lg-actions .lg-prev {
	left: 20px;
}

.lg-actions .lg-prev:after {
	content: "\e094";
}

@-webkit-keyframes lg-right-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: -30px;
	}
}

@-moz-keyframes lg-right-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: -30px;
	}
}

@-ms-keyframes lg-right-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: -30px;
	}
}

@keyframes lg-right-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: -30px;
	}
}

@-webkit-keyframes lg-left-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: 30px;
	}
}

@-moz-keyframes lg-left-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: 30px;
	}
}

@-ms-keyframes lg-left-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: 30px;
	}
}

@keyframes lg-left-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: 30px;
	}
}

.lg-outer.lg-right-end .lg-object {
	-webkit-animation: lg-right-end .3s;
	-o-animation: lg-right-end .3s;
	animation: lg-right-end .3s;
	position: relative;
}

.lg-outer.lg-left-end .lg-object {
	-webkit-animation: lg-left-end .3s;
	-o-animation: lg-left-end .3s;
	animation: lg-left-end .3s;
	position: relative;
}

.lg-toolbar {
	z-index: 1182;
	left: 0;
	position: absolute;
	top: 0;
	width: 100%;
}

.lg-toolbar .lg-icon {
	color: #999;
	cursor: pointer;
	float: right;
	font-size: 24px;
	height: 47px;
	line-height: 27px;
	padding: 10px 0;
	text-align: center;
	width: 50px;
	text-decoration: none !important;
	outline: 0;
	transition: color .2s linear;
}

@media (max-width: 575.98px) {
	.lg-toolbar .lg-icon {
		font-size: 21px;
		width: 36px;
	}
}

@media (max-width: 575.98px) {
	#lg-counter {
		font-size: 14px;
		line-height: 27px;
	}
}

.lg-toolbar .lg-icon:hover {
	color: #fff;
}

.lg-toolbar .lg-close:after {
	content: "\e070";
}

.lg-toolbar .lg-download:after {
	content: "\e0f2";
}

.lg-sub-html {
	bottom: 0;
	color: #eee;
	font-size: 16px;
	left: 0;
	padding: 10px 40px;
	position: fixed;
	right: 0;
	text-align: center;
	z-index: 1180;
}

.lg-sub-html h4 {
	margin: 0;
	font-size: 13px;
	font-weight: 700;
}

.lg-sub-html p {
	font-size: 12px;
	margin: 5px 0 0;
}

#lg-counter {
	color: #999;
	display: inline-block;
	font-size: 16px;
	padding-left: 20px;
	padding-top: 12px;
	vertical-align: middle;
}

.lg-next, .lg-prev, .lg-toolbar {
	opacity: 1;
	transition: transform 0.35s cubic-bezier(0, 0, 0.25, 1) 0s, opacity 0.35s cubic-bezier(0, 0, 0.25, 1) 0s, color 0.2s linear;
}

.lg-hide-items .lg-prev {
	opacity: 0;
	transform: translate3d(-10px, 0, 0);
}

.lg-hide-items .lg-next {
	opacity: 0;
	transform: translate3d(10px, 0, 0);
}

.lg-hide-items .lg-toolbar {
	opacity: 0;
	transform: translate3d(0, -10px, 0);
}

body:not(.lg-from-hash) .lg-outer.lg-start-zoom .lg-object {
	transform: scale3d(0.5, 0.5, 0.5);
	opacity: 0;
	transition: transform 250ms cubic-bezier(0, 0, 0.25, 1) 0s, opacity 250ms cubic-bezier(0, 0, 0.25, 1) !important;
	-moz-transform-origin: 50% 50%;
	-ms-transform-origin: 50% 50%;
	transform-origin: 50% 50%;
}

body:not(.lg-from-hash) .lg-outer.lg-start-zoom .lg-item.lg-complete .lg-object {
	transform: scale3d(1, 1, 1);
	opacity: 1;
}

.lg-outer .lg-thumb-outer {
	background-color: #0d0a0a;
	bottom: 0;
	position: absolute;
	width: 100%;
	z-index: 1180;
	max-height: 350px;
	transform: translate3d(0, 100%, 0);
	transition: transform 0.25s cubic-bezier(0, 0, 0.25, 1) 0s;
}

.lg-outer .lg-thumb-outer.lg-grab .lg-thumb-item {
	cursor: -webkit-grab;
	cursor: -moz-grab;
	cursor: -o-grab;
	cursor: -ms-grab;
	cursor: grab;
}

.lg-outer .lg-thumb-outer.lg-grabbing .lg-thumb-item {
	cursor: move;
	cursor: -webkit-grabbing;
	cursor: -moz-grabbing;
	cursor: -o-grabbing;
	cursor: -ms-grabbing;
	cursor: grabbing;
}

.lg-outer .lg-thumb-outer.lg-dragging .lg-thumb {
	transition-duration: 0s !important;
}

.lg-outer.lg-thumb-open .lg-thumb-outer {
	transform: translate3d(0, 0, 0);
}

.lg-outer .lg-thumb {
	padding: 10px 0;
	height: 100%;
	margin-bottom: -5px;
	margin-left: auto;
	margin-right: auto;
}

.lg-outer .lg-thumb-item {
	cursor: pointer;
	float: left;
	overflow: hidden;
	height: 100%;
	border: 2px solid #fff;
	border-radius: 4px;
	margin-bottom: 5px;
}

@media (min-width: 1025px) {
	.lg-outer .lg-thumb-item {
		transition: border-color .25s ease;
	}
}

.lg-outer .lg-thumb-item.active, .lg-outer .lg-thumb-item:hover {
	border-color: #a90707;
}

.lg-outer .lg-thumb-item img {
	width: 100%;
	height: 100%;
	object-fit: cover;
}

.lg-outer.lg-has-thumb .lg-item {
	padding-bottom: 120px;
}

.lg-outer.lg-can-toggle .lg-item {
	padding-bottom: 0;
}

.lg-outer.lg-pull-caption-up .lg-sub-html {
	transition: bottom .25s ease;
}

.lg-outer.lg-pull-caption-up.lg-thumb-open .lg-sub-html {
	bottom: 100px;
}

.lg-outer .lg-toogle-thumb {
	background-color: #0d0a0a;
	border-radius: 2px 2px 0 0;
	color: #999;
	cursor: pointer;
	font-size: 24px;
	height: 39px;
	line-height: 27px;
	padding: 5px 0;
	position: absolute;
	right: 20px;
	text-align: center;
	top: -39px;
	width: 50px;
}

.lg-outer .lg-toogle-thumb:hover, .lg-outer.lg-dropdown-active #lg-share {
	color: #fff;
}

.lg-outer .lg-toogle-thumb:after {
	content: "\e1ff";
}

.lg-outer .lg-video-cont {
	display: inline-block;
	vertical-align: middle;
	max-width: 1140px;
	max-height: 100%;
	width: 100%;
	padding: 0 5px;
}

.lg-outer .lg-video {
	width: 100%;
	height: 0;
	padding-bottom: 56.25%;
	overflow: hidden;
	position: relative;
}

.lg-outer .lg-video .lg-object {
	display: inline-block;
	position: absolute;
	top: 0;
	left: 0;
	width: 100% !important;
	height: 100% !important;
}

.lg-outer .lg-video .lg-video-play {
	width: 84px;
	height: 59px;
	position: absolute;
	left: 50%;
	top: 50%;
	margin-left: -42px;
	margin-top: -30px;
	z-index: 1180;
	cursor: pointer;
}

.lg-outer .lg-has-iframe .lg-video {
	-webkit-overflow-scrolling: touch;
	overflow: auto;
}

.lg-outer .lg-has-vimeo .lg-video-play {
	background: url(../images/vimeo-play.png) no-repeat;
}

.lg-outer .lg-has-vimeo:hover .lg-video-play {
	background: url(../images/vimeo-play.png) 0 -58px no-repeat;
}

.lg-outer .lg-has-html5 .lg-video-play {
	background: url(../images/video-play.png) no-repeat;
	height: 64px;
	margin-left: -32px;
	margin-top: -32px;
	width: 64px;
	opacity: .8;
}

.lg-outer .lg-has-html5:hover .lg-video-play {
	opacity: 1;
}

.lg-outer .lg-has-youtube .lg-video-play {
	background: url(../images/youtube-play.png) no-repeat;
}

.lg-outer .lg-has-youtube:hover .lg-video-play {
	background: url(../images/youtube-play.png) 0 -60px no-repeat;
}

.lg-outer .lg-video-object {
	width: 100% !important;
	height: 100% !important;
	position: absolute;
	top: 0;
	left: 0;
}

.lg-outer .lg-has-video .lg-video-object {
	visibility: hidden;
}

.lg-outer .lg-has-video.lg-video-playing .lg-object, .lg-outer .lg-has-video.lg-video-playing .lg-video-play {
	display: none;
}

.lg-outer .lg-has-video.lg-video-playing .lg-video-object {
	visibility: visible;
}

.lg-progress-bar {
	background-color: #333;
	height: 5px;
	left: 0;
	position: absolute;
	top: 0;
	width: 100%;
	z-index: 1183;
	opacity: 0;
	transition: opacity 80ms ease 0s;
}

.lg-progress-bar .lg-progress {
	background-color: #a90707;
	height: 5px;
	width: 0;
}

.lg-progress-bar.lg-start .lg-progress {
	width: 100%;
}

.lg-show-autoplay .lg-progress-bar {
	opacity: 1;
}

.lg-autoplay-button:after {
	content: "\e01d";
}

.lg-show-autoplay .lg-autoplay-button:after {
	content: "\e01a";
}

.lg-outer.lg-css3.lg-zoom-dragging .lg-item.lg-complete.lg-zoomable .lg-image, .lg-outer.lg-css3.lg-zoom-dragging .lg-item.lg-complete.lg-zoomable .lg-img-wrap {
	transition-duration: 0s;
}

.lg-outer.lg-use-transition-for-zoom .lg-item.lg-complete.lg-zoomable .lg-img-wrap {
	transition: transform 0.3s cubic-bezier(0, 0, 0.25, 1) 0s;
}

.lg-outer.lg-use-left-for-zoom .lg-item.lg-complete.lg-zoomable .lg-img-wrap {
	transition: left 0.3s cubic-bezier(0, 0, 0.25, 1) 0s, top 0.3s cubic-bezier(0, 0, 0.25, 1) 0s;
}

.lg-outer .lg-item.lg-complete.lg-zoomable .lg-img-wrap {
	transform: translate3d(0, 0, 0);
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	backface-visibility: hidden;
}

.lg-outer .lg-item.lg-complete.lg-zoomable .lg-image {
	transform: scale3d(1, 1, 1);
	transition: transform 0.3s cubic-bezier(0, 0, 0.25, 1) 0s, opacity 0.15s !important;
	-moz-transform-origin: 0 0;
	-ms-transform-origin: 0 0;
	transform-origin: 0 0;
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	backface-visibility: hidden;
}

#lg-zoom-in:after {
	content: "\e311";
}

#lg-actual-size {
	font-size: 20px;
}

#lg-actual-size:after {
	content: "\e033";
}

#lg-zoom-out {
	opacity: .5;
	pointer-events: none;
}

#lg-zoom-out:after {
	content: "\e312";
}

.lg-zoomed #lg-zoom-out {
	opacity: 1;
	pointer-events: auto;
}

.lg-outer .lg-pager-outer {
	bottom: 60px;
	left: 0;
	position: absolute;
	right: 0;
	text-align: center;
	z-index: 1180;
	height: 10px;
}

.lg-outer .lg-pager-outer.lg-pager-hover .lg-pager-cont {
	overflow: visible;
}

.lg-outer .lg-pager-cont {
	cursor: pointer;
	display: inline-block;
	overflow: hidden;
	position: relative;
	vertical-align: top;
	margin: 0 5px;
}

.lg-outer .lg-pager-cont:hover .lg-pager-thumb-cont {
	opacity: 1;
	transform: translate3d(0, 0, 0);
}

.lg-outer .lg-pager-cont.lg-pager-active .lg-pager {
	box-shadow: 0 0 0 2px #fff inset;
}

.lg-outer .lg-pager-thumb-cont {
	background-color: #fff;
	color: #fff;
	bottom: 100%;
	height: 83px;
	left: 0;
	margin-bottom: 20px;
	margin-left: -60px;
	opacity: 0;
	padding: 5px;
	position: absolute;
	width: 120px;
	border-radius: 3px;
	transition: opacity .15s ease 0s, transform .15s ease 0s;
	transform: translate3d(0, 5px, 0);
}

.lg-outer .lg-pager-thumb-cont img {
	width: 100%;
	height: 100%;
}

.lg-outer .lg-pager {
	background-color: rgba(255, 255, 255, 0.5);
	border-radius: 50%;
	box-shadow: 0 0 0 8px rgba(255, 255, 255, 0.7) inset;
	display: block;
	height: 12px;
	transition: box-shadow .3s ease 0s;
	width: 12px;
}

.lg-outer .lg-pager:focus, .lg-outer .lg-pager:hover {
	box-shadow: 0 0 0 8px #fff inset;
}

.lg-outer .lg-caret {
	border-left: 10px solid transparent;
	border-right: 10px solid transparent;
	border-top: 10px dashed;
	bottom: -10px;
	display: inline-block;
	height: 0;
	left: 50%;
	margin-left: -5px;
	position: absolute;
	vertical-align: middle;
	width: 0;
}

.lg-fullscreen:after {
	content: "\e20c";
}

.lg-fullscreen-on .lg-fullscreen:after {
	content: "\e20d";
}

.lg-outer #lg-dropdown-overlay {
	background-color: rgba(0, 0, 0, 0.25);
	bottom: 0;
	cursor: default;
	left: 0;
	position: fixed;
	right: 0;
	top: 0;
	z-index: 1181;
	opacity: 0;
	visibility: hidden;
	transition: visibility 0s linear .18s, opacity .18s linear 0s;
}

.lg-outer.lg-dropdown-active #lg-dropdown-overlay, .lg-outer.lg-dropdown-active .lg-dropdown {
	transition-delay: 0s;
	-moz-transform: translate3d(0, 0, 0);
	-ms-transform: translate3d(0, 0, 0);
	transform: translate3d(0, 0, 0);
	opacity: 1;
	visibility: visible;
}

.lg-outer .lg-dropdown {
	background-color: #fff;
	border-radius: 2px;
	font-size: 14px;
	list-style-type: none;
	margin: 0;
	padding: 10px 0;
	position: absolute;
	right: 0;
	text-align: left;
	top: 50px;
	opacity: 0;
	visibility: hidden;
	-moz-transform: translate3d(0, 5px, 0);
	-ms-transform: translate3d(0, 5px, 0);
	transform: translate3d(0, 5px, 0);
	transition: transform .18s linear 0s, visibility 0s linear .5s, opacity .18s linear 0s;
}

.lg-outer .lg-dropdown:after {
	content: "";
	display: block;
	height: 0;
	width: 0;
	position: absolute;
	border: 8px solid transparent;
	border-bottom-color: #fff;
	right: 16px;
	top: -16px;
}

.lg-outer .lg-dropdown > li:last-child {
	margin-bottom: 0;
}

.lg-outer .lg-dropdown > li:hover .lg-icon, .lg-outer .lg-dropdown > li:hover a {
	color: #333;
}

.lg-outer .lg-dropdown a {
	color: #333;
	display: block;
	white-space: pre;
	padding: 4px 12px;
	font-family: "Averia Libre";
	font-size: 12px;
}

.lg-outer .lg-dropdown a:hover {
	background-color: rgba(0, 0, 0, 0.07);
}

.lg-outer .lg-dropdown .lg-dropdown-text {
	display: inline-block;
	line-height: 1;
	margin-top: -3px;
	vertical-align: middle;
}

.lg-outer .lg-dropdown .lg-icon {
	color: #333;
	display: inline-block;
	float: none;
	font-size: 20px;
	height: auto;
	line-height: 1;
	margin-right: 8px;
	padding: 0;
	vertical-align: middle;
	width: auto;
}

.lg-outer, .lg-outer .lg, .lg-outer .lg-inner {
	width: 100%;
	height: 100%;
}

.lg-outer #lg-share {
	position: relative;
}

.lg-outer #lg-share:after {
	content: "\e80d";
}

.lg-outer #lg-share-facebook .lg-icon {
	color: #3b5998;
}

.lg-outer #lg-share-facebook .lg-icon:after {
	content: "\e901";
}

.lg-outer #lg-share-twitter .lg-icon {
	color: #00aced;
}

.lg-outer #lg-share-twitter .lg-icon:after {
	content: "\e904";
}

.lg-outer #lg-share-googleplus .lg-icon {
	color: #dd4b39;
}

.lg-outer #lg-share-googleplus .lg-icon:after {
	content: "\e902";
}

.lg-outer #lg-share-pinterest .lg-icon {
	color: #cb2027;
}

.lg-outer #lg-share-pinterest .lg-icon:after {
	content: "\e903";
}

.lg-group:after {
	content: "";
	display: table;
	clear: both;
}

.lg-outer {
	position: fixed;
	top: 0;
	left: 0;
	z-index: 1150;
	text-align: left;
	opacity: 0;
	transition: opacity .15s ease 0s;
}

.lg-outer * {
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}

.lg-outer.lg-visible {
	opacity: 1;
}

.lg-outer.lg-css3 .lg-item.lg-current, .lg-outer.lg-css3 .lg-item.lg-next-slide, .lg-outer.lg-css3 .lg-item.lg-prev-slide {
	transition-duration: inherit !important;
	transition-timing-function: inherit !important;
}

.lg-outer.lg-css3.lg-dragging .lg-item.lg-current, .lg-outer.lg-css3.lg-dragging .lg-item.lg-next-slide, .lg-outer.lg-css3.lg-dragging .lg-item.lg-prev-slide {
	transition-duration: 0s !important;
	opacity: 1;
}

.lg-outer.lg-grab img.lg-object {
	cursor: -webkit-grab;
	cursor: -moz-grab;
	cursor: -o-grab;
	cursor: -ms-grab;
	cursor: grab;
}

.lg-outer.lg-grabbing img.lg-object {
	cursor: move;
	cursor: -webkit-grabbing;
	cursor: -moz-grabbing;
	cursor: -o-grabbing;
	cursor: -ms-grabbing;
	cursor: grabbing;
}

.lg-outer .lg {
	position: relative;
	overflow: hidden;
	margin-left: auto;
	margin-right: auto;
	max-width: 100%;
	max-height: 100%;
}

.lg-outer .lg-inner {
	position: absolute;
	left: 0;
	top: 0;
	white-space: nowrap;
}

.lg-outer .lg-item {
	background: url(../images/loading.gif) center center no-repeat;
	display: none !important;
}

.lg-outer.lg-css .lg-current, .lg-outer.lg-css3 .lg-current, .lg-outer.lg-css3 .lg-next-slide, .lg-outer.lg-css3 .lg-prev-slide {
	display: inline-block !important;
}

.lg-outer .lg-img-wrap, .lg-outer .lg-item {
	display: inline-block;
	text-align: center;
	position: absolute;
	width: 100%;
	height: 100%;
}

.lg-outer .lg-img-wrap:before, .lg-outer .lg-item:before {
	content: "";
	display: inline-block;
	height: 50%;
	width: 1px;
	margin-right: -1px;
}

.lg-outer .lg-img-wrap {
	position: absolute;
	padding: 0 5px;
	left: 0;
	right: 0;
	top: 0;
	bottom: 0;
}

.lg-outer .lg-item.lg-complete {
	background-image: none;
}

.lg-outer .lg-item.lg-current {
	z-index: 1160;
}

.lg-outer .lg-image {
	display: inline-block;
	vertical-align: middle;
	max-width: 100%;
	max-height: 100%;
	width: auto !important;
	height: auto !important;
}

.lg-outer.lg-show-after-load .lg-item .lg-object, .lg-outer.lg-show-after-load .lg-item .lg-video-play {
	opacity: 0;
	transition: opacity .15s ease 0s;
}

.lg-outer.lg-show-after-load .lg-item.lg-complete .lg-object, .lg-outer.lg-show-after-load .lg-item.lg-complete .lg-video-play {
	opacity: 1;
}

.lg-outer .lg-empty-html, .lg-outer.lg-hide-download #lg-download {
	display: none;
}

.lg-backdrop {
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	z-index: 1140;
	background-color: #000;
	opacity: 0;
	transition: opacity .15s ease 0s;
}

.lg-css3.lg-no-trans .lg-current, .lg-css3.lg-no-trans .lg-next-slide, .lg-css3.lg-no-trans .lg-prev-slide {
	transition: none 0s ease 0s !important;
}

.lg-css3.lg-use-css3 .lg-item, .lg-css3.lg-use-left .lg-item {
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	backface-visibility: hidden;
}

.lg-css3.lg-fade .lg-item {
	opacity: 0;
}

.lg-css3.lg-fade .lg-item.lg-current {
	opacity: 1;
}

.lg-css3.lg-fade .lg-item.lg-current, .lg-css3.lg-fade .lg-item.lg-next-slide, .lg-css3.lg-fade .lg-item.lg-prev-slide {
	transition: opacity .1s ease 0s;
}

.lg-css3.lg-slide.lg-use-css3 .lg-item {
	opacity: 0;
}

.lg-css3.lg-slide.lg-use-css3 .lg-item.lg-prev-slide {
	transform: translate3d(-100%, 0, 0);
}

.lg-css3.lg-slide.lg-use-css3 .lg-item.lg-next-slide {
	transform: translate3d(100%, 0, 0);
}

.lg-css3.lg-slide.lg-use-css3 .lg-item.lg-current {
	transform: translate3d(0, 0, 0);
	opacity: 1;
}

.lg-css3.lg-slide.lg-use-css3 .lg-item.lg-current, .lg-css3.lg-slide.lg-use-css3 .lg-item.lg-next-slide, .lg-css3.lg-slide.lg-use-css3 .lg-item.lg-prev-slide {
	transition: transform 1s cubic-bezier(0, 0, 0.25, 1) 0s, opacity 0.1s ease 0s;
}

.lg-css3.lg-slide.lg-use-left .lg-item {
	opacity: 0;
	position: absolute;
	left: 0;
}

.lg-css3.lg-slide.lg-use-left .lg-item.lg-prev-slide {
	left: -100%;
}

.lg-css3.lg-slide.lg-use-left .lg-item.lg-next-slide {
	left: 100%;
}

.lg-css3.lg-slide.lg-use-left .lg-item.lg-current {
	left: 0;
	opacity: 1;
}

.lg-css3.lg-slide.lg-use-left .lg-item.lg-current, .lg-css3.lg-slide.lg-use-left .lg-item.lg-next-slide, .lg-css3.lg-slide.lg-use-left .lg-item.lg-prev-slide {
	transition: left 1s cubic-bezier(0, 0, 0.25, 1) 0s, opacity 0.1s ease 0s;
}

.lg-sub-html, .lg-toolbar {
	background-color: rgba(0, 0, 0, 0.45);
}

@font-face {
	font-family: lg;
	src: url(../fonts/lg.eot?n1z373);
	src: url(../fonts/lg.eot?#iefixn1z373) format("embedded-opentype"), url(../fonts/lg.woff?n1z373) format("woff"), url(../fonts/lg.ttf?n1z373) format("truetype"), url(../fonts/lg.svg?n1z373#lg) format("svg");
	font-weight: 400;
	font-style: normal;
}

.lg-icon {
	font-family: lg;
	speak: none;
	font-style: normal;
	font-weight: 400;
	font-variant: normal;
	text-transform: none;
	line-height: 1;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}

.lg-actions .lg-next, .lg-actions .lg-prev {
	background-color: rgba(0, 0, 0, 0.45);
	border-radius: 2px;
	color: #999;
	cursor: pointer;
	display: block;
	font-size: 22px;
	margin-top: -10px;
	padding: 8px 10px 9px;
	position: absolute;
	top: 50%;
	z-index: 1180;
	border: none;
	outline: 0;
}

.lg-actions .lg-next.disabled, .lg-actions .lg-prev.disabled {
	pointer-events: none;
	opacity: .5;
}

.lg-actions .lg-next:hover, .lg-actions .lg-prev:hover {
	color: #fff;
}

.lg-actions .lg-next {
	right: 20px;
}

.lg-actions .lg-next:before {
	content: "\e095";
}

.lg-actions .lg-prev {
	left: 20px;
}

.lg-actions .lg-prev:after {
	content: "\e094";
}

@-webkit-keyframes lg-right-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: -30px;
	}
}

@-moz-keyframes lg-right-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: -30px;
	}
}

@-ms-keyframes lg-right-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: -30px;
	}
}

@keyframes lg-right-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: -30px;
	}
}

@-webkit-keyframes lg-left-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: 30px;
	}
}

@-moz-keyframes lg-left-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: 30px;
	}
}

@-ms-keyframes lg-left-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: 30px;
	}
}

@keyframes lg-left-end {
	0%, 100% {
		left: 0;
	}
	50% {
		left: 30px;
	}
}

.lg-outer.lg-right-end .lg-object {
	-webkit-animation: lg-right-end .3s;
	-o-animation: lg-right-end .3s;
	animation: lg-right-end .3s;
	position: relative;
}

.lg-outer.lg-left-end .lg-object {
	-webkit-animation: lg-left-end .3s;
	-o-animation: lg-left-end .3s;
	animation: lg-left-end .3s;
	position: relative;
}

.lg-toolbar {
	z-index: 1182;
	left: 0;
	position: absolute;
	top: 0;
	width: 100%;
}

.lg-toolbar .lg-icon:hover {
	color: #fff;
}

.lg-toolbar .lg-close:after {
	content: "\e070";
}

.lg-toolbar .lg-download:after {
	content: "\e0f2";
}

.lg-sub-html {
	bottom: 0;
	color: #eee;
	font-size: 16px;
	left: 0;
	padding: 10px 40px;
	position: fixed;
	right: 0;
	text-align: center;
	z-index: 1180;
}

.lg-sub-html h4 {
	margin: 0;
	font-size: 13px;
	font-weight: 700;
}

.lg-sub-html p {
	font-size: 12px;
	margin: 5px 0 0;
}

#lg-counter {
	color: #999;
	display: inline-block;
	font-size: 16px;
	padding-left: 20px;
	padding-top: 12px;
	vertical-align: middle;
}

.lg-next, .lg-prev, .lg-toolbar {
	opacity: 1;
	transition: transform 0.35s cubic-bezier(0, 0, 0.25, 1) 0s, opacity 0.35s cubic-bezier(0, 0, 0.25, 1) 0s, color 0.2s linear;
}

.lg-hide-items .lg-prev {
	opacity: 0;
	transform: translate3d(-10px, 0, 0);
}

.lg-hide-items .lg-next {
	opacity: 0;
	transform: translate3d(10px, 0, 0);
}

.lg-hide-items .lg-toolbar {
	opacity: 0;
	transform: translate3d(0, -10px, 0);
}

body:not(.lg-from-hash) .lg-outer.lg-start-zoom .lg-object {
	transform: scale3d(0.5, 0.5, 0.5);
	opacity: 0;
	transition: transform 250ms cubic-bezier(0, 0, 0.25, 1) 0s, opacity 250ms cubic-bezier(0, 0, 0.25, 1) !important;
	-moz-transform-origin: 50% 50%;
	-ms-transform-origin: 50% 50%;
	transform-origin: 50% 50%;
}

body:not(.lg-from-hash) .lg-outer.lg-start-zoom .lg-item.lg-complete .lg-object {
	transform: scale3d(1, 1, 1);
	opacity: 1;
}

.lg-outer .lg-thumb-outer {
	background-color: #0d0a0a;
	bottom: 0;
	position: absolute;
	width: 100%;
	z-index: 1180;
	max-height: 350px;
	transform: translate3d(0, 100%, 0);
	transition: transform 0.25s cubic-bezier(0, 0, 0.25, 1) 0s;
}

.lg-outer .lg-thumb-outer.lg-grab .lg-thumb-item {
	cursor: -webkit-grab;
	cursor: -moz-grab;
	cursor: -o-grab;
	cursor: -ms-grab;
	cursor: grab;
}

.lg-outer .lg-thumb-outer.lg-grabbing .lg-thumb-item {
	cursor: move;
	cursor: -webkit-grabbing;
	cursor: -moz-grabbing;
	cursor: -o-grabbing;
	cursor: -ms-grabbing;
	cursor: grabbing;
}

.lg-outer .lg-thumb-outer.lg-dragging .lg-thumb {
	transition-duration: 0s !important;
}

.lg-outer.lg-thumb-open .lg-thumb-outer {
	transform: translate3d(0, 0, 0);
}

.lg-outer .lg-thumb {
	padding: 10px 0;
	height: 100%;
	margin-bottom: -5px;
}

.lg-outer .lg-thumb-item {
	cursor: pointer;
	float: left;
	overflow: hidden;
	height: 100%;
	border: 2px solid rgba(255, 255, 255, 0.4);
	border-radius: 0;
	margin-bottom: 5px;
}

@media (min-width: 1025px) {
	.lg-outer .lg-thumb-item {
		transition: border-color .25s ease;
	}
}

.lg-outer .lg-thumb-item.active, .lg-outer .lg-thumb-item:hover {
	border-color: #ef172c;
}

.lg-outer .lg-thumb-item img {
	width: 100%;
	height: 100%;
	object-fit: cover;
	border-radius: 0;
}

.lg-outer.lg-has-thumb .lg-item {
	padding-bottom: 120px;
}

.lg-outer.lg-can-toggle .lg-item {
	padding-bottom: 0;
}

.lg-outer.lg-pull-caption-up .lg-sub-html {
	transition: bottom .25s ease;
}

.lg-outer.lg-pull-caption-up.lg-thumb-open .lg-sub-html {
	bottom: 100px;
}

.lg-outer .lg-toogle-thumb {
	background-color: #0d0a0a;
	border-radius: 2px 2px 0 0;
	color: #999;
	cursor: pointer;
	font-size: 24px;
	height: 39px;
	line-height: 27px;
	padding: 5px 0;
	position: absolute;
	right: 20px;
	text-align: center;
	top: -39px;
	width: 50px;
}

.lg-outer .lg-toogle-thumb:hover, .lg-outer.lg-dropdown-active #lg-share {
	color: #fff;
}

.lg-outer .lg-toogle-thumb:after {
	content: "\e1ff";
}

.lg-outer .lg-video-cont {
	display: inline-block;
	vertical-align: middle;
	max-width: 1140px;
	max-height: 100%;
	width: 100%;
	padding: 0 5px;
}

.lg-outer .lg-video {
	width: 100%;
	height: 0;
	padding-bottom: 56.25%;
	overflow: hidden;
	position: relative;
}

.lg-outer .lg-video .lg-object {
	display: inline-block;
	position: absolute;
	top: 0;
	left: 0;
	width: 100% !important;
	height: 100% !important;
}

.lg-outer .lg-video .lg-video-play {
	width: 84px;
	height: 59px;
	position: absolute;
	left: 50%;
	top: 50%;
	margin-left: -42px;
	margin-top: -30px;
	z-index: 1180;
	cursor: pointer;
}

.lg-outer .lg-has-iframe .lg-video {
	-webkit-overflow-scrolling: touch;
	overflow: auto;
}

.lg-outer .lg-has-vimeo .lg-video-play {
	background: url(../images/vimeo-play.png) no-repeat;
}

.lg-outer .lg-has-vimeo:hover .lg-video-play {
	background: url(../images/vimeo-play.png) 0 -58px no-repeat;
}

.lg-outer .lg-has-html5 .lg-video-play {
	background: url(../images/video-play.png) no-repeat;
	height: 64px;
	margin-left: -32px;
	margin-top: -32px;
	width: 64px;
	opacity: .8;
}

.lg-outer .lg-has-html5:hover .lg-video-play {
	opacity: 1;
}

.lg-outer .lg-has-youtube .lg-video-play {
	background: url(../images/youtube-play.png) no-repeat;
}

.lg-outer .lg-has-youtube:hover .lg-video-play {
	background: url(../images/youtube-play.png) 0 -60px no-repeat;
}

.lg-outer .lg-video-object {
	width: 100% !important;
	height: 100% !important;
	position: absolute;
	top: 0;
	left: 0;
}

.lg-outer .lg-has-video .lg-video-object {
	visibility: hidden;
}

.lg-outer .lg-has-video.lg-video-playing .lg-object, .lg-outer .lg-has-video.lg-video-playing .lg-video-play {
	display: none;
}

.lg-outer .lg-has-video.lg-video-playing .lg-video-object {
	visibility: visible;
}

.lg-progress-bar {
	background-color: #333;
	height: 5px;
	left: 0;
	position: absolute;
	top: 0;
	width: 100%;
	z-index: 1183;
	opacity: 0;
	transition: opacity 80ms ease 0s;
}

.lg-progress-bar .lg-progress {
	background-color: #ef172c;
	height: 5px;
	width: 0;
}

.lg-progress-bar.lg-start .lg-progress {
	width: 100%;
}

.lg-show-autoplay .lg-progress-bar {
	opacity: 1;
}

.lg-autoplay-button:after {
	content: "\e01d";
}

.lg-show-autoplay .lg-autoplay-button:after {
	content: "\e01a";
}

.lg-outer.lg-css3.lg-zoom-dragging .lg-item.lg-complete.lg-zoomable .lg-image, .lg-outer.lg-css3.lg-zoom-dragging .lg-item.lg-complete.lg-zoomable .lg-img-wrap {
	transition-duration: 0s;
}

.lg-outer.lg-use-transition-for-zoom .lg-item.lg-complete.lg-zoomable .lg-img-wrap {
	transition: transform 0.3s cubic-bezier(0, 0, 0.25, 1) 0s;
}

.lg-outer.lg-use-left-for-zoom .lg-item.lg-complete.lg-zoomable .lg-img-wrap {
	transition: left 0.3s cubic-bezier(0, 0, 0.25, 1) 0s, top 0.3s cubic-bezier(0, 0, 0.25, 1) 0s;
}

.lg-outer .lg-item.lg-complete.lg-zoomable .lg-img-wrap {
	transform: translate3d(0, 0, 0);
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	backface-visibility: hidden;
}

.lg-outer .lg-item.lg-complete.lg-zoomable .lg-image {
	transform: scale3d(1, 1, 1);
	transition: transform 0.3s cubic-bezier(0, 0, 0.25, 1) 0s, opacity 0.15s !important;
	-moz-transform-origin: 0 0;
	-ms-transform-origin: 0 0;
	transform-origin: 0 0;
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	backface-visibility: hidden;
}

#lg-zoom-in:after {
	content: "\e311";
}

#lg-actual-size {
	font-size: 20px;
}

#lg-actual-size:after {
	content: "\e033";
}

#lg-zoom-out {
	opacity: .5;
	pointer-events: none;
}

#lg-zoom-out:after {
	content: "\e312";
}

.lg-zoomed #lg-zoom-out {
	opacity: 1;
	pointer-events: auto;
}

.lg-outer .lg-pager-outer {
	bottom: 60px;
	left: 0;
	position: absolute;
	right: 0;
	text-align: center;
	z-index: 1180;
	height: 10px;
}

.lg-outer .lg-pager-outer.lg-pager-hover .lg-pager-cont {
	overflow: visible;
}

.lg-outer .lg-pager-cont {
	cursor: pointer;
	display: inline-block;
	overflow: hidden;
	position: relative;
	vertical-align: top;
	margin: 0 5px;
}

.lg-outer .lg-pager-cont:hover .lg-pager-thumb-cont {
	opacity: 1;
	transform: translate3d(0, 0, 0);
}

.lg-outer .lg-pager-cont.lg-pager-active .lg-pager {
	box-shadow: 0 0 0 2px #fff inset;
}

.lg-outer .lg-pager-thumb-cont {
	background-color: #fff;
	color: #fff;
	bottom: 100%;
	height: 83px;
	left: 0;
	margin-bottom: 20px;
	margin-left: -60px;
	opacity: 0;
	padding: 5px;
	position: absolute;
	width: 120px;
	border-radius: 3px;
	transition: opacity .15s ease 0s, transform .15s ease 0s;
	transform: translate3d(0, 5px, 0);
}

.lg-outer .lg-pager-thumb-cont img {
	width: 100%;
	height: 100%;
}

.lg-outer .lg-pager {
	background-color: rgba(255, 255, 255, 0.5);
	border-radius: 50%;
	box-shadow: 0 0 0 8px rgba(255, 255, 255, 0.7) inset;
	display: block;
	height: 12px;
	transition: box-shadow .3s ease 0s;
	width: 12px;
}

.lg-outer .lg-pager:focus, .lg-outer .lg-pager:hover {
	box-shadow: 0 0 0 8px #fff inset;
}

.lg-outer .lg-caret {
	border-left: 10px solid transparent;
	border-right: 10px solid transparent;
	border-top: 10px dashed;
	bottom: -10px;
	display: inline-block;
	height: 0;
	left: 50%;
	margin-left: -5px;
	position: absolute;
	vertical-align: middle;
	width: 0;
}

.lg-fullscreen:after {
	content: "\e20c";
}

.lg-fullscreen-on .lg-fullscreen:after {
	content: "\e20d";
}

.lg-outer #lg-dropdown-overlay {
	background-color: rgba(0, 0, 0, 0.25);
	bottom: 0;
	cursor: default;
	left: 0;
	position: fixed;
	right: 0;
	top: 0;
	z-index: 1181;
	opacity: 0;
	visibility: hidden;
	transition: visibility 0s linear .18s, opacity .18s linear 0s;
}

.lg-outer.lg-dropdown-active #lg-dropdown-overlay, .lg-outer.lg-dropdown-active .lg-dropdown {
	transition-delay: 0s;
	-moz-transform: translate3d(0, 0, 0);
	-ms-transform: translate3d(0, 0, 0);
	transform: translate3d(0, 0, 0);
	opacity: 1;
	visibility: visible;
}

.lg-outer .lg-dropdown {
	background-color: #fff;
	border-radius: 2px;
	font-size: 14px;
	list-style-type: none;
	margin: 0;
	padding: 10px 0;
	position: absolute;
	right: 0;
	text-align: left;
	top: 50px;
	opacity: 0;
	visibility: hidden;
	-moz-transform: translate3d(0, 5px, 0);
	-ms-transform: translate3d(0, 5px, 0);
	transform: translate3d(0, 5px, 0);
	transition: transform .18s linear 0s, visibility 0s linear .5s, opacity .18s linear 0s;
}

.lg-outer .lg-dropdown:after {
	content: "";
	display: block;
	height: 0;
	width: 0;
	position: absolute;
	border: 8px solid transparent;
	border-bottom-color: #fff;
	right: 16px;
	top: -16px;
}

.lg-outer .lg-dropdown > li:last-child {
	margin-bottom: 0;
}

.lg-outer .lg-dropdown > li:hover .lg-icon, .lg-outer .lg-dropdown > li:hover a {
	color: #333;
}

.lg-outer .lg-dropdown a {
	color: #333;
	display: block;
	white-space: pre;
	padding: 4px 12px;
	font-family: "Averia Libre";
	font-size: 12px;
}

.lg-outer .lg-dropdown a:hover {
	background-color: rgba(0, 0, 0, 0.07);
}

.lg-outer .lg-dropdown .lg-dropdown-text {
	display: inline-block;
	line-height: 1;
	margin-top: -3px;
	vertical-align: middle;
}

.lg-outer .lg-dropdown .lg-icon {
	color: #333;
	display: inline-block;
	float: none;
	font-size: 20px;
	height: auto;
	line-height: 1;
	margin-right: 8px;
	padding: 0;
	vertical-align: middle;
	width: auto;
}

.lg-outer, .lg-outer .lg, .lg-outer .lg-inner {
	width: 100%;
	height: 100%;
}

.lg-outer #lg-share {
	position: relative;
}

.lg-outer #lg-share:after {
	content: "\e80d";
}

.lg-outer #lg-share-facebook .lg-icon {
	color: #3b5998;
}

.lg-outer #lg-share-facebook .lg-icon:after {
	content: "\e901";
}

.lg-outer #lg-share-twitter .lg-icon {
	color: #00aced;
}

.lg-outer #lg-share-twitter .lg-icon:after {
	content: "\e904";
}

.lg-outer #lg-share-googleplus .lg-icon {
	color: #dd4b39;
}

.lg-outer #lg-share-googleplus .lg-icon:after {
	content: "\e902";
}

.lg-outer #lg-share-pinterest .lg-icon {
	color: #cb2027;
}

.lg-outer #lg-share-pinterest .lg-icon:after {
	content: "\e903";
}

.lg-group:after {
	content: "";
	display: table;
	clear: both;
}

.lg-outer {
	position: fixed;
	top: 0;
	left: 0;
	z-index: 1150;
	text-align: left;
	opacity: 0;
	transition: opacity .15s ease 0s;
}

.lg-outer * {
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}

.lg-outer.lg-visible {
	opacity: 1;
}

.lg-outer.lg-css3 .lg-item.lg-current, .lg-outer.lg-css3 .lg-item.lg-next-slide, .lg-outer.lg-css3 .lg-item.lg-prev-slide {
	transition-duration: inherit !important;
	transition-timing-function: inherit !important;
}

.lg-outer.lg-css3.lg-dragging .lg-item.lg-current, .lg-outer.lg-css3.lg-dragging .lg-item.lg-next-slide, .lg-outer.lg-css3.lg-dragging .lg-item.lg-prev-slide {
	transition-duration: 0s !important;
	opacity: 1;
}

.lg-outer.lg-grab img.lg-object {
	cursor: grab;
}

.lg-outer.lg-grabbing img.lg-object {
	cursor: grabbing;
}

.lg-outer .lg {
	position: relative;
	overflow: hidden;
	margin-left: auto;
	margin-right: auto;
	max-width: 100%;
	max-height: 100%;
}

.lg-outer .lg-inner {
	position: absolute;
	left: 0;
	top: 0;
	white-space: nowrap;
}

.lg-outer .lg-item {
	background: url(../images/loading.gif) center center no-repeat;
	display: none !important;
}

.lg-outer.lg-css .lg-current, .lg-outer.lg-css3 .lg-current, .lg-outer.lg-css3 .lg-next-slide, .lg-outer.lg-css3 .lg-prev-slide {
	display: inline-block !important;
}

.lg-outer .lg-img-wrap, .lg-outer .lg-item {
	display: inline-block;
	text-align: center;
	position: absolute;
	width: 100%;
	height: 100%;
}

.lg-outer .lg-img-wrap:before, .lg-outer .lg-item:before {
	content: "";
	display: inline-block;
	height: 50%;
	width: 1px;
	margin-right: -1px;
}

.lg-outer .lg-img-wrap {
	position: absolute;
	padding: 0 5px;
	left: 0;
	right: 0;
	top: 0;
	bottom: 0;
}

.lg-outer .lg-item.lg-complete {
	background-image: none;
}

.lg-outer .lg-item.lg-current {
	z-index: 1160;
}

.lg-outer .lg-image {
	display: inline-block;
	vertical-align: middle;
	max-width: 100%;
	max-height: 100%;
	width: auto !important;
	height: auto !important;
}

.lg-outer.lg-show-after-load .lg-item .lg-object, .lg-outer.lg-show-after-load .lg-item .lg-video-play {
	opacity: 0;
	transition: opacity .15s ease 0s;
}

.lg-outer.lg-show-after-load .lg-item.lg-complete .lg-object, .lg-outer.lg-show-after-load .lg-item.lg-complete .lg-video-play {
	opacity: 1;
}

.lg-outer .lg-empty-html, .lg-outer.lg-hide-download #lg-download {
	display: none;
}

.lg-backdrop {
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	z-index: 1140;
	background-color: #000;
	opacity: 0;
	transition: opacity .15s ease 0s;
}

.lg-backdrop.in {
	opacity: .8;
}

.lg-css3.lg-no-trans .lg-current, .lg-css3.lg-no-trans .lg-next-slide, .lg-css3.lg-no-trans .lg-prev-slide {
	transition: none 0s ease 0s !important;
}

.lg-css3.lg-use-css3 .lg-item, .lg-css3.lg-use-left .lg-item {
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	backface-visibility: hidden;
}

.lg-css3.lg-fade .lg-item {
	opacity: 0;
}

.lg-css3.lg-fade .lg-item.lg-current {
	opacity: 1;
}

.lg-css3.lg-fade .lg-item.lg-current, .lg-css3.lg-fade .lg-item.lg-next-slide, .lg-css3.lg-fade .lg-item.lg-prev-slide {
	transition: opacity .1s ease 0s;
}

.lg-css3.lg-slide.lg-use-css3 .lg-item {
	opacity: 0;
}

.lg-css3.lg-slide.lg-use-css3 .lg-item.lg-prev-slide {
	transform: translate3d(-100%, 0, 0);
}

.lg-css3.lg-slide.lg-use-css3 .lg-item.lg-next-slide {
	transform: translate3d(100%, 0, 0);
}

.lg-css3.lg-slide.lg-use-css3 .lg-item.lg-current {
	transform: translate3d(0, 0, 0);
	opacity: 1;
}

.lg-css3.lg-slide.lg-use-css3 .lg-item.lg-current, .lg-css3.lg-slide.lg-use-css3 .lg-item.lg-next-slide, .lg-css3.lg-slide.lg-use-css3 .lg-item.lg-prev-slide {
	transition: transform 1s cubic-bezier(0, 0, 0.25, 1) 0s, opacity 0.1s ease 0s;
}

.lg-css3.lg-slide.lg-use-left .lg-item {
	opacity: 0;
	position: absolute;
	left: 0;
}

.lg-css3.lg-slide.lg-use-left .lg-item.lg-prev-slide {
	left: -100%;
}

.lg-css3.lg-slide.lg-use-left .lg-item.lg-next-slide {
	left: 100%;
}

.lg-css3.lg-slide.lg-use-left .lg-item.lg-current {
	left: 0;
	opacity: 1;
}

.lg-css3.lg-slide.lg-use-left .lg-item.lg-current, .lg-css3.lg-slide.lg-use-left .lg-item.lg-next-slide, .lg-css3.lg-slide.lg-use-left .lg-item.lg-prev-slide {
	transition: left 1s cubic-bezier(0, 0, 0.25, 1) 0s, opacity 0.1s ease 0s;
}

@media (max-width: 380px) {
	#lg-zoom-in,
	#lg-zoom-out {
		display: none;
	}
}

/*
*
* Material Parallax
*/
.parallax-content {
	position: relative;
	z-index: 1;
}

.parallax-container {
	position: relative;
	overflow: hidden;
	background-position: center center;
	background-size: cover;
}

.material-parallax {
	position: absolute;
	top: 0;
	left: -1px;
	right: -1px;
	bottom: 0;
	z-index: 0;
	background-position: center center;
}

.ipad .parallax-container,
.iphone .parallax-container {
	background-attachment: scroll !important;
}

.material-parallax img {
	display: none;
	position: absolute;
	left: 50%;
	bottom: 0;
	min-width: 101%;
	min-height: 101%;
	max-width: none;
	transform: translate3d(-50%, 0, 0);
}

/*
*
* Slick Carousel
*/
/*rtl:begin:ignore*/
.slick-slider {
	position: relative;
	display: block;
	box-sizing: border-box;
	-webkit-touch-callout: none;
	-webkit-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
	-ms-touch-action: pan-y;
	touch-action: pan-y;
	-webkit-tap-highlight-color: transparent;
}

.slick-list {
	position: relative;
	overflow: hidden;
	display: block;
	margin: 0;
	padding: 0;
}

.slick-list:focus {
	outline: none;
}

.slick-list.dragging {
	cursor: pointer;
	cursor: hand;
}

.slick-slider .slick-track,
.slick-slider .slick-list {
	transform: translate3d(0, 0, 0);
}

.slick-track {
	position: relative;
	left: 0;
	top: 0;
	display: block;
}

.slick-track::before, .slick-track::after {
	content: "";
	display: table;
}

.slick-track::after {
	clear: both;
}

.slick-loading .slick-track {
	visibility: hidden;
}

.slick-slide {
	float: left;
	height: 100%;
	min-height: 1px;
	display: none;
}

[dir="rtl"] .slick-slide {
	float: right;
}

.slick-slide img {
	display: block;
}

.slick-slide.slick-loading img {
	display: none;
}

.slick-slide.dragging img {
	pointer-events: none;
}

.slick-initialized .slick-slide {
	display: block;
}

.slick-loading .slick-slide {
	visibility: hidden;
}

.slick-vertical .slick-slide {
	display: block;
	height: auto;
	border: 1px solid transparent;
}

.slick-arrow.slick-hidden {
	display: none;
}

.slick-loading .slick-list {
	background: #fff url("./../images/ajax-loader.gif") center center no-repeat;
}

/* Icons */
/* Arrows */
.slick-prev,
.slick-next {
	position: absolute;
	display: block;
	height: 20px;
	width: 20px;
	line-height: 0;
	font-size: 0;
	cursor: pointer;
	color: transparent;
	background-color: transparent;
	top: 50%;
	transform: translate(0, -50%);
	padding: 0;
	border: none;
	outline: none;
	z-index: 9;
}

.slick-prev.slick-disabled:before,
.slick-next.slick-disabled:before {
	opacity: 0.25;
}

.slick-prev::before,
.slick-next::before {
	font-family: "fl-bigmug-line";
	font-size: 24px;
	line-height: 1;
	color: #ef172c;
	opacity: 0.75;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	transition: .22s;
}

.slick-prev:hover::before,
.slick-next:hover::before {
	color: #37020e;
}

.slick-prev {
	left: 0;
}

[dir="rtl"] .slick-prev {
	left: auto;
	right: 0;
}

.slick-prev:before {
	content: "";
}

[dir="rtl"] .slick-prev:before {
	content: "";
}

.slick-next {
	right: 0;
}

[dir="rtl"] .slick-next {
	left: 0;
	right: auto;
}

.slick-next:before {
	content: "";
}

[dir="rtl"] .slick-next:before {
	content: "";
}

/* Dots */
.slick-dots {
	position: absolute;
	bottom: -45px;
	list-style: none;
	display: block;
	text-align: center;
	padding: 0;
	width: 100%;
}

.slick-dots li {
	position: relative;
	display: inline-block;
	height: 20px;
	width: 20px;
	margin: 0 5px;
	padding: 0;
	cursor: pointer;
}

.slick-dots li button {
	border: 0;
	background: transparent;
	display: block;
	height: 20px;
	width: 20px;
	outline: none;
	line-height: 0;
	font-size: 0;
	color: transparent;
	padding: 5px;
	cursor: pointer;
}

.slick-dots li button:hover, .slick-dots li button:focus {
	outline: none;
}

.slick-dots li button:hover:before, .slick-dots li button:focus:before {
	opacity: 1;
}

.slick-dots li button:before {
	position: absolute;
	top: 0;
	left: 0;
	content: "";
	font-family: "fl-bigmug-line";
	font-size: 6px;
	line-height: 20px;
	text-align: center;
	color: #ef172c;
	opacity: 0.25;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}

.slick-dots li.slick-active button:before {
	color: #ef172c;
	opacity: 0.75;
}

/*rtl:end:ignore*/
.slick-widget-testimonials .carousel-child {
	max-width: 570px;
	padding: 0 50px;
	margin-left: auto;
	margin-right: auto;
}

.slick-widget-testimonials .carousel-child .item {
	border-radius: 50%;
	cursor: pointer;
	transform: scale3d(0.66, 0.66, 0.66);
	transition: .22s;
	text-align: center;
}

.slick-widget-testimonials .carousel-child .slick-center {
	transform: scale3d(1, 1, 1);
}

.slick-widget-testimonials .carousel-child img {
	border-radius: inherit;
	max-width: 100%;
	margin: 0 auto;
}

@media (max-width: 575.98px) {
	.slick-widget-testimonials .carousel-child .slick-prev {
		left: 30px;
	}
	.slick-widget-testimonials .carousel-child .slick-next {
		right: 30px;
	}
}

.slick-widget-testimonials .carousel-parent {
	max-width: 780px;
	margin-left: auto;
	margin-right: auto;
}

.slick-widget-testimonials .carousel-parent .item > * {
	transform-origin: 50% 0;
	opacity: 0;
	transition: .44s;
}

.slick-widget-testimonials .carousel-parent .slick-active > * {
	opacity: 1;
}

.slick-widget-testimonials > * + * {
	margin-top: 20px;
}

* + .slick-widget-testimonials {
	margin-top: 30px;
}

@media (min-width: 768px) {
	* + .slick-widget-testimonials {
		margin-top: 55px;
	}
}

@media (min-width: 1200px) {
	* + .slick-widget-testimonials {
		margin-top: 75px;
	}
}

/*
*
* Select 2 v4
*/
.select2-container {
	box-sizing: border-box;
	display: inline-block;
	margin: 0;
	position: relative;
	vertical-align: middle;
}

.select2-container .select2-selection--single {
	display: block;
	cursor: pointer;
	user-select: none;
}

.select2-container .select2-selection--single .select2-selection__rendered {
	display: block;
	padding-left: 8px;
	padding-right: 20px;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}

.select2-container .select2-selection--single .select2-selection__clear {
	position: relative;
}

.select2-container[dir="rtl"] .select2-selection--single .select2-selection__rendered {
	padding-right: 8px;
	padding-left: 20px;
}

.select2-container .select2-selection--multiple {
	display: block;
	cursor: pointer;
	min-height: 32px;
	user-select: none;
	-webkit-user-select: none;
}

.select2-container .select2-selection--multiple .select2-selection__rendered {
	display: inline-block;
	overflow: hidden;
	padding-left: 8px;
	text-overflow: ellipsis;
	white-space: nowrap;
}

.select2-container .select2-search--inline {
	float: left;
}

.select2-container .select2-search--inline .select2-search__field {
	border: none;
	font-size: 100%;
	margin-top: 5px;
	padding: 0;
}

.select2-container .select2-search--inline .select2-search__field::-webkit-search-cancel-button {
	-webkit-appearance: none;
}

.select2-dropdown {
	position: absolute;
	left: -100000px;
	z-index: 1051;
	display: block;
	overflow: hidden;
	width: 100%;
	border: 0;
	border-radius: 0px;
	background-color: #fff;
	box-shadow: 0 0 5px 0 rgba(41, 41, 58, 0.2);
}

.select2-results {
	display: block;
}

.select2-results__options {
	list-style: none;
	margin: 0;
	padding: 0;
}

.select2-results__option {
	padding: 6px;
	user-select: none;
	-webkit-user-select: none;
}

.select2-results__option[aria-selected] {
	cursor: pointer;
}

.select2-container--open .select2-dropdown {
	left: 0;
}

.select2-container--open .select2-dropdown--above {
	border-bottom: none;
	border-bottom-left-radius: 0;
	border-bottom-right-radius: 0;
}

.select2-container--open .select2-dropdown--below {
	border-top: none;
	border-top-left-radius: 0;
	border-top-right-radius: 0;
}

.select2-search--dropdown {
	display: block;
	padding: 4px;
}

.select2-search--dropdown .select2-search__field {
	padding: 4px;
	width: 100%;
	box-sizing: border-box;
}

.select2-search--dropdown .select2-search__field::-webkit-search-cancel-button {
	-webkit-appearance: none;
}

.select2-search--dropdown.select2-search--hide {
	display: none;
}

.select2-close-mask {
	border: 0;
	margin: 0;
	padding: 0;
	display: block;
	position: fixed;
	left: 0;
	top: 0;
	min-height: 100%;
	min-width: 100%;
	height: auto;
	width: auto;
	opacity: 0;
	z-index: 99;
	background-color: #fff;
	filter: alpha(opacity=0);
}

.select2-hidden-accessible {
	border: 0 !important;
	clip: rect(0 0 0 0) !important;
	height: 1px !important;
	margin: -1px !important;
	overflow: hidden !important;
	padding: 0 !important;
	position: absolute !important;
	width: 1px !important;
}

.select2-container--default .select2-selection--single {
	background-color: #fff;
	border: 0;
	border-radius: 0px;
}

.select2-container--default .select2-selection--single .select2-selection__rendered {
	display: block;
	padding: 11px 29px 11px 19px;
	color: #29293a;
	font-size: 16px;
	line-height: 1.4875;
	font-weight: 400;
	min-height: 48px;
}

.select2-container--default .select2-selection--single .select2-selection__clear {
	cursor: pointer;
	float: right;
	font-weight: 700;
}

.select2-container--default .select2-selection--single .select2-selection__placeholder {
	color: #15191f;
}

.select2-container--default .select2-selection--single .select2-selection__arrow {
	position: absolute;
	top: 50%;
	transform: translate3d(0, -50%, 0);
	right: 5px;
	width: 20px;
}

.select2-container--default .select2-selection--single .select2-selection__arrow b {
	pointer-events: none;
	color: #29293a;
}

.select2-container--default .select2-selection--single .select2-selection__arrow b::before {
	position: relative;
	display: inline-block;
	content: "";
	font-family: "Material Design Icons";
	font-size: 18px;
	transform: rotate(0deg);
	transition: .1s;
}

.select2-container--default[dir="rtl"] .select2-selection--single .select2-selection__clear {
	float: left;
}

.select2-container--default[dir="rtl"] .select2-selection--single .select2-selection__arrow {
	left: 1px;
	right: auto;
}

.select2-container--default.select2-container--disabled .select2-selection--single {
	background-color: #f5f6fa;
	cursor: default;
}

.select2-container--default.select2-container--disabled .select2-selection--single .select2-selection__clear {
	display: none;
}

.select2-container--default.select2-container--open .select2-selection--single .select2-selection__arrow b::before {
	transform: rotate(180deg);
}

.select2-container--default .select2-selection--multiple {
	background-color: #fff;
	border: 1px solid #aaa;
	border-radius: 0px;
	cursor: text;
}

.select2-container--default .select2-selection--multiple .select2-selection__rendered {
	box-sizing: border-box;
	list-style: none;
	margin: 0;
	padding: 0 5px;
	width: 100%;
}

.select2-container--default .select2-selection--multiple .select2-selection__rendered li {
	list-style: none;
}

.select2-container--default .select2-selection--multiple .select2-selection__placeholder {
	color: #999;
	margin-top: 5px;
	float: left;
}

.select2-container--default .select2-selection--multiple .select2-selection__clear {
	cursor: pointer;
	float: right;
	font-weight: bold;
	margin-top: 5px;
	margin-right: 10px;
}

.select2-container--default .select2-selection--multiple .select2-selection__choice {
	background-color: #e4e4e4;
	border: 1px solid #aaa;
	border-radius: 4px;
	cursor: default;
	float: left;
	margin-right: 5px;
	margin-top: 5px;
	padding: 0 5px;
}

.select2-container--default .select2-selection--multiple .select2-selection__choice__remove {
	color: #999;
	cursor: pointer;
	display: inline-block;
	font-weight: bold;
	margin-right: 2px;
}

.select2-container--default .select2-selection--multiple .select2-selection__choice__remove:hover {
	color: #333;
}

.select2-container--default[dir="rtl"] .select2-selection--multiple .select2-selection__choice, .select2-container--default[dir="rtl"] .select2-selection--multiple .select2-selection__placeholder, .select2-container--default[dir="rtl"] .select2-selection--multiple .select2-search--inline {
	float: right;
}

.select2-container--default[dir="rtl"] .select2-selection--multiple .select2-selection__choice {
	margin-left: 5px;
	margin-right: auto;
}

.select2-container--default[dir="rtl"] .select2-selection--multiple .select2-selection__choice__remove {
	margin-left: 2px;
	margin-right: auto;
}

.select2-container--default.select2-container--focus .select2-selection--multiple {
	border: solid black 1px;
	outline: 0;
}

.select2-container--default.select2-container--disabled .select2-selection--multiple {
	background-color: #eee;
	cursor: default;
}

.select2-container--default.select2-container--disabled .select2-selection__choice__remove {
	display: none;
}

.select2-container--default.select2-container--open.select2-container--above .select2-selection--single, .select2-container--default.select2-container--open.select2-container--above .select2-selection--multiple {
	border-top-left-radius: 0;
	border-top-right-radius: 0;
}

.select2-container--default.select2-container--open.select2-container--below .select2-selection--single, .select2-container--default.select2-container--open.select2-container--below .select2-selection--multiple {
	border-bottom-left-radius: 0;
	border-bottom-right-radius: 0;
}

.select2-container--default .select2-search--dropdown {
	border-top: 0;
}

.select2-container--default .select2-search--dropdown .select2-search__field {
	border: 1px solid #c5c6cd;
}

.select2-container--default .select2-search--inline .select2-search__field {
	background: transparent;
	border: none;
	outline: 0;
	box-shadow: none;
	-webkit-appearance: textfield;
}

.select2-container--default .select2-results > .select2-results__options {
	max-height: 200px;
	overflow-y: auto;
}

.select2-container--default .select2-results__option[role=group] {
	padding: 0;
}

.select2-container--default .select2-results__option[aria-disabled=true] {
	color: #9b9b9b;
}

.select2-container--default .select2-results__option[aria-selected=true] {
	color: #fff;
	background-color: #f40941;
}

.select2-container--default .select2-results__option .select2-results__option {
	padding-left: 1em;
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__group {
	padding-left: 0;
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option {
	margin-left: -1em;
	padding-left: 2em;
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option .select2-results__option {
	margin-left: -2em;
	padding-left: 3em;
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option {
	margin-left: -3em;
	padding-left: 4em;
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option {
	margin-left: -4em;
	padding-left: 5em;
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option {
	margin-left: -5em;
	padding-left: 6em;
}

.select2-container--default .select2-results__option--highlighted[aria-selected] {
	color: #fff;
	background-color: #ef172c;
}

.select2-container--default .select2-results__group {
	cursor: default;
	display: block;
	padding: 6px;
}

/*
*
* D3 Charts
*/
.c3 svg {
	padding-left: 4px;
	width: 100%;
	-webkit-tap-highlight-color: transparent;
}

.c3 path,
.c3 line {
	fill: none;
	stroke: #9f9f9f;
}

.c3 text {
	font-family: "Averia Libre";
	font-size: 16px;
	fill: #9b9b9b;
	user-select: none;
}

.c3-legend-item-tile,
.c3-xgrid-focus,
.c3-ygrid,
.c3-event-rect,
.c3-bars path {
	shape-rendering: crispEdges;
}

.c3-chart-arc path {
	stroke: #fff;
}

.c3-chart-arc text {
	fill: #fff;
	font-size: 14px;
}

/*-- Axis --*/
/*-- Grid --*/
.c3-grid line {
	stroke: #eaebee;
}

.c3-grid text {
	fill: #aaa;
}

.c3-xgrid,
.c3-ygrid {
	stroke-dasharray: 0 0;
}

/*-- Text on Chart --*/
.c3-text.c3-empty {
	fill: #808080;
	font-size: 2em;
}

/*-- Line --*/
.c3-line {
	stroke-width: 3px;
}

/*-- Point --*/
.c3-circle._expanded_ {
	stroke-width: 2px;
	stroke: white;
}

.c3-selected-circle {
	fill: white;
	stroke-width: 2px;
}

/*-- Bar --*/
.c3-bar {
	stroke-width: 0;
}

.c3-bar._expanded_ {
	fill-opacity: 0.75;
}

/*-- Focus --*/
.c3-target.c3-focused {
	opacity: 1;
}

.c3-target.c3-focused path.c3-line,
.c3-target.c3-focused path.c3-step {
	stroke-width: 2px;
}

.c3-target.c3-defocused {
	opacity: 0.3 !important;
}

/*-- Region --*/
.c3-region {
	fill: steelblue;
	fill-opacity: .1;
}

/*-- Brush --*/
.c3-brush .extent {
	fill-opacity: .1;
	fill: #000;
}

/*-- Select - Drag --*/
/*-- Legend --*/
.c3-legend-item {
	font-size: 12px;
}

.c3-legend-item-hidden {
	opacity: 0.15;
}

.c3-legend-background {
	opacity: 0.75;
	fill: white;
	stroke: lightgray;
	stroke-width: 1;
}

/*-- Title --*/
.c3-title {
	font: 14px sans-serif;
}

/*-- Tooltip --*/
.c3-tooltip-container {
	z-index: 10;
}

.c3-tooltip {
	border-collapse: collapse;
	border-spacing: 0;
	background-color: #fff;
	empty-cells: show;
	opacity: 0.9;
	border: 1px solid #ccc;
}

.c3-tooltip tr {
	border: 1px solid #ccc;
}

.c3-tooltip th {
	background-color: #aaa;
	font-size: 14px;
	line-height: 1.2;
	padding: 2px 5px;
	text-align: left;
	color: #fff;
}

.c3-tooltip td {
	font-size: 13px;
	padding: 3px 6px;
	background-color: #fff;
	color: #000;
	border-left: 1px dotted #999;
}

.c3-tooltip td > span {
	display: inline-block;
	width: 10px;
	height: 10px;
	margin-right: 6px;
}

.c3-tooltip td.value {
	text-align: right;
}

/*-- Area --*/
.c3-area {
	stroke-width: 0;
	opacity: 0.2;
}

/*-- Arc --*/
.c3-chart-arcs-title {
	dominant-baseline: middle;
	font-size: 1.3em;
}

.c3-chart-arcs .c3-chart-arcs-background {
	fill: #e0e0e0;
	stroke: none;
}

.c3-chart-arcs .c3-chart-arcs-gauge-unit {
	fill: #000;
	font-size: 16px;
}

.c3-chart-arcs .c3-chart-arcs-gauge-max {
	fill: #777;
}

.c3-chart-arcs .c3-chart-arcs-gauge-min {
	fill: #777;
}

.c3-chart-arc .c3-gauge-value {
	fill: #000;
}

.c3 .domain {
	stroke: #c8c8c8;
}

.d3-chart .tick line {
	display: none;
}

.d3-chart .c3-tooltip {
	opacity: 1;
	color: #fff;
	background: #ef172c;
	border: 1px solid #aeb1be;
}

.d3-chart .c3-tooltip tr th {
	padding: 8px 10px;
	color: #fff;
	background: #29293a;
}

.d3-chart .c3-tooltip tr td {
	padding: 5px 10px;
	color: #838386;
	background: #fff;
}

.d3-chart .c3-tooltip .value {
	border-left: 1px solid #f2f3f9;
}

#line-chart .c3-tooltip-container {
	border-radius: 0px;
	overflow: hidden;
	box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.05);
}

#line-chart .c3-tooltip-container tr {
	border: 0;
}

#line-chart .c3-tooltip-container .name {
	border-left: 0;
}

#line-chart .c3-tooltip-container table {
	border: 0 solid transparent;
	border-radius: 0px;
}

#line-chart .c3-axis-y-label {
	transform: translateY(-10px);
}

#line-chart .c3-axis-y .tick text {
	transform: translateX(1px);
}

#line-chart .c3-axis-x {
	text-align: left;
}

#line-chart .c3-axis-x text {
	transform: translateX(-1px);
	text-anchor: start !important;
}

#line-chart .c3-legend-item {
	display: none !important;
	transform: translateY(15px);
}

#line-chart .c3-legend-item text {
	font-size: 16px;
	color: #29293a;
}

.d3-chart-wrap {
	width: 100%;
	max-width: 100%;
	overflow-y: hidden;
	overflow-x: auto;
	padding-bottom: 30px;
}

.d3-chart-wrap > .d3-chart {
	min-width: 520px;
}

.d3-chart-legend {
	transform: translateY(-5px);
	margin-bottom: -5px;
	margin-left: -30px;
	text-align: center;
}

.d3-chart-legend > * {
	display: inline-block;
	margin-top: 5px;
	margin-left: 30px;
}

.d3-chart-legend span {
	position: relative;
	display: inline-block;
	font-size: 16px;
	color: #15191f;
	cursor: pointer;
}

.d3-chart-legend span::before {
	content: '';
	display: inline-block;
	height: 3px;
	width: 30px;
	margin-right: 12px;
	vertical-align: middle;
}

.d3-chart-legend span:nth-child(1)::before {
	background: #ef172c;
}

.d3-chart-legend span:nth-child(2)::before {
	background: #aeb1be;
}

* + .d3-chart-legend {
	margin-top: 20px;
}

@media (min-width: 1600px) {
	.d3-chart-legend span {
		font-size: 18px;
	}
}
