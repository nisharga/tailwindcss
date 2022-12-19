<h2>Install Tailwind CSS in React App </h2>

<code><b>npm install -D tailwindcss postcss autoprefixer</b></code></br>
<code><b>npx tailwindcss init</b></code></br>

then in tailwind.config.js file write this code.</br>
<code><b>content: ["./src/**/*.{html,js}"]</b>,</code></br>

then index.css file peast this code on top

<code><b>@tailwind base;</br>
@tailwind components;</br>
@tailwind utilities;</b></br></code>

npm start for run react app

<h2>Tailwind CSS 15 Parts Needs to watch </h2>

<b>1.Layout</b><br>
<b>2.Flexbox & Grid</b><br>
<b>3.Spacing</b><br>
<b>4.Sizing</b><br>
<b>5.Typography</b><br>
<b>6.Backgrounds</b><br>
<b>7.Borders</b><br>
<b>8.Effects</b><br>
<b>9.Filters</b><br>
<b>10.Tables</b><br>
<b>11.Transitions & Animation</b><br>
<b>12.Transforms</b><br>
<b>13.Interactivity</b><br>
<b>14.SVG</b><br>
<b>15.Accessibility</b><br>

<hr>

<h2>1.Layout:</h2>

<code>container mx-auto</code> === container
<code>columns-3</code> === for 3 column
<code>break-after-column, break-before-column, break-inside-avoid-column </code> === start new column 
<code>box-border, box-content </code> === box size
<code>block, inline-block </code> === display property
<code>inline-flex</code> === inline image+ content
<code>float-left, float-right, clear-none </code> === preview like a newspaper
<code>object-cover, object-contain, object-fill </code> === Object fit
<code>overflow-visible, overflow-hidden </code> === overflow
<code>static + absolute bottom-0 left-0 </code> === position absolute any object.
<code>inset-x-0	</code> === left 0 right 0
<code>inset-y-0 </code> === top 0 bottom 0
<code>visible,invisible </code> === visibility 
<code>z-10 </code> === Z for z-index


<h2>5.Typography:</h2>

FontSize: every rem meaning 16px; 0.25rem mean 4px;
text-sm (14px)
text-base(1rem)(16px)
text-xl(1.25rem)(20px)
text-2xl(1.5rem)(24px)

italic font-mono (font-family: ui-monospace)(font-style: italic;)

font-normal(font-weight: 400)
font-semibold(font-weight: 600)
font-bold(font-weight: 700)
font-extrabold(font-weight: 800)
font-black(font-weight: 900)

diagonal-fractions(for half writing)

tracking-[.25em](for spaceing in letter)

leading-relaxed (line-height: 1.625rem)
leading-loose (line-height: 2)

list-disc (bulletList)
list-decimal (number list)
list-outside(for list start left)

text-center, text-right, text-justify (for text align)

text-current, text-slate-600, text-gray-900, text-zinc-800
text-neutral-700, text-stone-500, text-amber-600, text-cyan-400
text-teal-200, text-fuchsia-200

text-blue-600/100 (color with opacity)
text-[#50d71e] (rgb value)

underline, overline, line-through, no-underline(no underline for a link)
underline decoration-wavy (for bottom ~ design)

uppercase, lowercase, capitalize, normal-case (text-transform: "")

truncate (overflow: hidden;)

align-bottom, align-top, align-middle (vertical-align: middle;)

