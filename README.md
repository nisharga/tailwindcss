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

1.Layout
2.Flexbox & Grid
3.Spacing
4.Sizing
5.Typography
6.Backgrounds
7.Borders
8.Effects
9.Filters
10.Tables
11.Transitions & Animation
12.Transforms
13.Interactivity
14.SVG
15.Accessibility

5.Typography:

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

