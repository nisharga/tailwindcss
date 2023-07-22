<h2>Install Tailwind CSS in React App </h2>

<code><b>npm install -D tailwindcss postcss autoprefixer</b></code></br>
<code><b>npx tailwindcss init -p</b></code></br>

then in tailwind.config.js file write this code.</br>
<code><b>content: content: ["./src/**/*.{js,jsx,ts,tsx}"],</b>,</code></br>

then index.css file paste this code on top

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

<code>container mx-auto</code> === container <br/>
<code>columns-3</code> === for 3 column <br/>
<code>break-after-column, break-before-column, break-inside-avoid-column </code> === start new column  <br/>
<code>box-border, box-content </code> === box size <br/>
<code>block, inline-block </code> === display property <br/>
<code>inline-flex</code> === inline image+ content <br/>
<code>float-left, float-right, clear-none </code> === preview like a newspaper <br/>
<code>object-cover, object-contain, object-fill </code> === Object fit <br/>
<code>overflow-visible, overflow-hidden </code> === overflow <br/>
<code>static + absolute bottom-0 left-0 </code> === position absolute any object. <br/>
<code>inset-x-0	</code> === left 0 right 0 <br/>
<code>inset-y-0 </code> === top 0 bottom 0 <br/>
<code>visible,invisible </code> === visibility <br/>  
<code>z-10 </code> === Z for z-index <br/>


<hr>


<h2>2.Flexbox & Grid</h2>

<code>flex flex-row</code> === flex row wise<br/> 
<code>flex flex-col-reverse</code> === col reverse flex<br/> 
<code>flex-wrap, flex-norap</code> === flex wrap declire<br/> 
<code>flex-none, flex-auto, flex-1 </code> === no flex, auto mean width messure, 1 mean all same<br/> 
<code>basis-2/5, basis-1/5 </code> === 2/3 mean 40%, 1/5 mean 20%<br/> 
<code>grow, shrink </code> === grow mean bigger, shrink mean small<br/> 
<code>order-last, order-first, order-1 </code> === order of a div<br/> 
<code>grid grid-cols-4 gap-4 </code> === grid+column 4<br/> 
<code>col-span-2 </code> == double size col<br/> 
<code>col-start-2, col-end-5 </code> == start from 2 number, end before 5<br/> 
<code>grid grid-rows-4 grid-flow-col </code> === 4 item in a row<br/> 
<code>(grid for more explore, plese read docs)</code><br/> 
<code>gap-x-8 gap-y-4 </code> === grid item gap<br/> 
<code>flex justify-center </code> === all items center<br/> 
<code>justify-between, justify-around </code> === between and around<br/> 
<code>grid justify-items-center </code> === all items center<br/> 
<code>justify-self-end </code> === in items... it will last<br/> 
<code>justify-self-stretch </code> === full width take<br/> 
<code>content-center, content-between </code> ==== inside div all items will center and between<br/> 
<code>content-around, content-evenly </code> === inside div all items will around and evenly<br/> 
<code>items-center, items-end, items-baseline </code> === indide div all items center, end<br/> 
<code>self-center, self-end, self-stretch </code> === single item apply<br/> 
<code>(Place Conent for more visit doc)</code><br/> 
<code>grid grid-cols-3 gap-4 place-items-center </code> === inside all div center<br/> 
<code>place-self-center </code> === single item center<br/> 

<hr>

<h2>3.Spacing</h2>

<code>px-1 py-1  </code> === padding x 4px right-left, and bottom-top<br/> 
<code>px-5 py-5  </code> === padding x 20px right-left, and bottom-top<br/> 
<code>pr, pl, pb, pt  </code> === padding right, left, bottom, top<br/> 
<code>my-2.5 mx-2.5  </code> === margin y (4*2.5) 10px, x 10px<br/> 
<code>m-16  </code> === (16*4) 64px all side<br/> 
<code>space-x-8, space-y-8  </code> === (8*4) 32px margin left and margin top<br/> 

<hr>

<h2>4.Sizing</h2>

<code>w-5 </code> === (5*4) 20px width <br/> 
<code>w-2/3, w-3/4, w-3/12, w-11/12 </code> === 66% width, 75% width, 25% width, 91% width <br/> 
<code>w-full </code> === 100% width <br/> 
<code>min-w-[50%], min-w-full </code> === min width 50%, min width 100% <br/> 
<code>min-w-0, min-w-min </code> === min width 0, min-width min content <br/> 
<code>max-w-sm, max-w-md, max-w-lg, max-w-xl, max-w-2xl</code> === (24,28,32)rem*16 = px max width<br/>  
<code>max-w-full, max-w-max </code> === 100%, max-content <br/> 
<code>max-w-screen-sm, max-w-screen-md, max-w-screen-lg, max-w-screen-xl, max-w-screen-2xl </code> === 640px, 768px, 1024px, 1280px, 1536px <br/> 
<code>h-10 </code> === (10*4) 40px height <br/> 
<code>h-2/3, h-3/4, h-5/6 </code> === 66%, 75%, 83%, <br/> 
<code>h-full, h-screen, h-[32rem] </code> === 100%, 100vh, 32rem height <br/> 
<code>min-h-0, min-h-full, min-h-screen </code> === 0, 100%, 100vh <br/> 
<code>min-h-max, min-h-fit, min-h-[50%] </code> === max-content, fit-content, 50% <br/> 
<code>max-h-8, max-h-full </code> === (8*4) 32px, 100% <br/> 

<hr>

<h2>5.Typography:</h2>

FontSize: every rem meaning 16px; 0.25rem mean 4px;  <br/> 
<code>text-sm, text-base, text-xl, text-2xl </code> === (14px, 16, 20, 24px)  <br/> 
<code>italic font-mono</code> === (font-family: ui-monospace)(font-style: italic;)  <br/> 
<code>font-normal, font-semibold, font-bold, font-extrabold, font-black </code> === (font-weight: 400, 600, 700, 800, 900)   <br/> 
<code>diagonal-fractions </code> === (for half writing) <br/> 
<code>tracking-[.25em] </code> === (for spaceing in letter) <br/> 
<code>leading-relaxed </code> === (line-height: 1.625rem) <br/> 
<code>leading-loose </code> === (line-height: 2) <br/> 
<code>list-disc </code> === (bulletList) <br/> 
<code>list-decimal </code> ==== (number list) <br/> 
<code>list-outside </code> === (for list start left) <br/> 
<code>text-center, text-right, text-justify </code> === (for text align) <br/> 
text-current, text-slate-600, text-gray-900, text-zinc-800 <br/> 
text-neutral-700, text-stone-500, text-amber-600, text-cyan-400 <br/> 
text-teal-200, text-fuchsia-200 </code>  <br/> 
<code>text-blue-600/100 </code> === (color with opacity) <br/> 
<code>text-[#50d71e] </code> ===(rgb value) <br/> 
<code>underline, overline, line-through, no-underline </code> ===(no underline for a link) <br/> 
<code>underline decoration-wavy </code> === (for bottom ~ design) <br/> 
<code>uppercase, lowercase, capitalize, normal-case </code> === (text-transform: "") <br/> 
<code>truncate </code> === (overflow: hidden;) <br/> 
<code>align-bottom, align-top, align-middle </code> === (vertical-align: middle;) <br/> 

<hr>

<h2>6.Backgrounds</h2>

<code>bg-fixed, bg-scroll </code> === Background image <br/> 
<code>bg-clip-border, bg-clip-content </code> === background Clip Box <br/> 
<code>bg-gray-200 bg-zinc-300 bg-neutral-400 bg-stone-500 </code> <br/> 
<code>bg-amber-600 bg-lime-700 bg-emerald-800 bg-teal-900 </code> <br/> 
<code>bg-cyan-100 bg-sky-200 bg-indigo-300 bg-violet-400 bg-purple-500 </code> <br/> 
<code>bg-fuchsia-600 bg-pink-700 bg-rose-800 </code> <br/> 
<code>bg-sky-500/100 </code> === bg color with opacity <br/> 
<code>bg-[#50d71e] </code> === direct use <br/> 
<code>bg-left-top, bg-right-bottom, bg-center </code> === bg position <br/> 
<code>bg-no-repeat, bg-repeat-y, bg-repeat-round, bg-repeat-space </code> === bg repect <br/> 
<code>bg-auto, bg-cover, bg-contain </code> === background size <br/> 
<code>bg-gradient-to-r, bg-gradient-to-br, bg-gradient-to-tl </code> === right, bottom-right, top-left <br/> 
<code>bg-gradient-to-r from-pink-500 via-lime-500 via-to-sky-800 </code> === gredient bg <br/> 


<hr>

<h2>7.Borders</h2>


<code>rounded, rounded-md, rounded-lg, rounded-full </code> === border round <br/>
<code>border-2, border-4 </code> === border <br/>
<code>border-x-2, border-y-2, border-r-4, border-l-4 </code> === border problem <br/>
<code>border-violet-100, border-y-pink-900, border-4 border-indigo-500/100 </code> ==== border  <br/>
<code>border-solid, border-dashed, border-dotted </code> === border style <br/>
<code>outline-1, outline-0, outline-4 </code> === border outline <br/>
<code>outline-2 outline-blue-500/50 </code> === outline color border <br/>
<code>outline-dotted, outline-double </code> === outline style <br/>
<code>outline-offset-2, outline-offset-4 </code> === outline offset border <br/>
<code>ring-offset-2 ring-2 </code> === box-shadow <br/>
<code>ring-2 ring-blue-500/50 </code> === ring color <br/>
<code>ring-offset-2 ring-offset-slate-100 </code> === ring offset color <br/>

<hr>

<h2>8.Effects</h2>

<code>shadow-md, shadow-lg, shadow-xl, shadow-2xl </code> === shadow <br/>
<code>shadow-indigo-500/40 </code> === shadow color <br/>
<code>opacity-50, opacity-75, opacity-100 </code> === opacity <br/>
<code>mix-blend-multiply </code> === two circle together <br/>


<hr>

<h2>9.Filters</h2>


<code>blur-sm, blur-lg </code> === blur
<code>brightness-50, brightness-100, brightness-200 </code> === brightness <br/>
<code>contrast-50, contrast-100, contrast-200 </code> === contrast <br/>
<code>drop-shadow-lg, drop-shadow-xl, drop-shadow-2xl </code> === drop-shadow <br/>
<code>grayscale-0, grayscale </code> === grayscale <br/>
<code>hue-rotate-90, hue-rotate-180, -hue-rotate-60 </code> === hue-rotate <br/>
<code>invert-0, invert </code> === invert <br/>
<code>saturate-100, saturate-150, saturate-200 </code> === saturate <br/>
<code>sepia-0, sepia </code> === sepia <br/>
<code>backdrop-blur-md, backdrop-blur-xl </code> === backdrop-blur <br/>
<code>backdrop-grayscale, backdrop-contrast-200, backdrop-brightness-200 </code> <br/>
<code>backdrop-hue-rotate-180, backdrop-invert, backdrop-opacity-95 </code> <br/>
<code>backdrop-saturate-200, backdrop-sepia </code> <br/>


<hr>

<h2>10.Tables</h2>


<code>border-collapse, border-separate </code> === border <br/>
<code>border border-slate-300</code> === table style <br/>
<code>border-spacing-2</code> === table spacing <br/>
<code>table-auto, table-fixed</code> === table fixed <br/>


<hr>

<h2>11.Transitions & Animation</h2>


<code>transition, transition-shadow, transition-transform </code> === transition <br/>
<code>duration-150, duration-300, duration-700 </code> === duration <br/>
<code>ease-in, ease-in-out, ease-out </code> === transition timing  <br/>
<code>delay-150, delay-300, delay-700 </code> === delay <br/>
<code>animate-spin, animate-ping, animate-pulse, animate-bounce </code> === animation <br/>

<hr>

<h2>12.Transforms</h2>


<code>scale-125, scale-50, -scale-50, transform-gpu </code> === transform <br/>
<code>rotate-45, rotate-90, rotate-180 </code> === rotate <br/>
<code>translate-y-6, -translate-y-6 </code> === translate <br/>
<code>skew-y-6, skew-y-12 </code> === skew  <br/>
<code>origin-center, origin-top-left </code> === origin <br/>

<hr>

<h2>13.Interactivity</h2>


<code>cursor-auto, cursor-pointer, cursor-progress, cursor-zoom-in </code> === cursor <br/>
<code>caret-pink-500, resize-y </code> === caret color + resize <br/> 
<code>scroll-smooth, scroll-ml-6, scroll-pl-6</code> === scroll <br/>
<code>snap-center, snap-start, snap-always, snap-y</code>	=== snap <br/>
<code>overflow-auto touch-auto , will-change-scroll</code> === scrool <br/>
<code>select-text, select-auto </code> === text highlight <br/>

<hr>

<h2>14.SVG && 15.Accessibility</h2>

<code>fill-blue-500, stroke-cyan-500, stroke-1, stroke-2</code> === SVG <br/>
<code>sr-only, not-sr-only </code> === Accessibility <br/>

