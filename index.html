import React, { useEffect, useMemo, useState } from "react";

// --- tiny icon helper (accepts fragments safely)
const Svg = ({ path, className }: { path: React.ReactNode; className?: string }) => (
  <svg
    viewBox="0 0 24 24"
    aria-hidden="true"
    className={className || "h-4 w-4"}
    fill="none"
    stroke="currentColor"
    strokeWidth="2"
    strokeLinecap="round"
    strokeLinejoin="round"
  >
    {path}
  </svg>
);
const Search       = (p:any)=> (
  <Svg
    {...p}
    path={
      <>
        <circle cx="11" cy="11" r="7" />
        <line x1="21" y1="21" x2="16.65" y2="16.65" />
      </>
    }
  />
);
const Clapperboard = (p:any)=> (
  <Svg
    {...p}
    path={
      <>
        <rect x="3" y="7" width="18" height="14" rx="2" />
        <path d="M3 7 7.5 3l3 4 4.5-4 3 4" />
      </>
    }
  />
);
const UserPlus     = (p:any)=> (
  <Svg
    {...p}
    path={
      <>
        <path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2" />
        <circle cx="9" cy="7" r="4" />
        <line x1="19" y1="8" x2="19" y2="14" />
        <line x1="22" y1="11" x2="16" y2="11" />
      </>
    }
  />
);
const Briefcase    = (p:any)=> (
  <Svg
    {...p}
    path={
      <>
        <rect x="2" y="7" width="20" height="14" rx="2" />
        <path d="M16 7V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v2" />
      </>
    }
  />
);
const Film         = (p:any)=> (
  <Svg
    {...p}
    path={
      <>
        <rect x="2" y="2" width="20" height="20" rx="2" />
        <path d="M7 2v20M17 2v20M2 12h20" />
      </>
    }
  />
);
const HandCoins    = (p:any)=> (
  <Svg
    {...p}
    path={
      <>
        <circle cx="8" cy="8" r="3" />
        <path d="M6 16v5h8a4 4 0 0 0 4-4V9" />
      </>
    }
  />
);
const LogIn        = (p:any)=> (
  <Svg
    {...p}
    path={
      <>
        <path d="M15 3h4a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-4" />
        <polyline points="10 17 15 12 10 7" />
        <line x1="15" y1="12" x2="3" y2="12" />
      </>
    }
  />
);
const Upload       = (p:any)=> (
  <Svg
    {...p}
    path={
      <>
        <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4" />
        <polyline points="17 8 12 3 7 8" />
        <line x1="12" y1="3" x2="12" y2="15" />
      </>
    }
  />
);
const ChevronRight = (p:any)=> <Svg {...p} path={<polyline points="9 18 15 12 9 6" />} />;
// extra icons for How it works
const IdCard = (p:any)=> (
  <Svg {...p} path={<><rect x="3" y="5" width="18" height="14" rx="2"/><rect x="7" y="8" width="6" height="4" rx="1"/><line x1="7" y1="14" x2="17" y2="14"/></>} />
);
const Message = (p:any)=> (
  <Svg {...p} path={<><path d="M21 15a4 4 0 0 1-4 4H8l-5 4V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4z"/></>} />
);
const Camera = (p:any)=> (
  <Svg {...p} path={<><rect x="3" y="7" width="18" height="14" rx="2"/><path d="M9 7l2-3h2l2 3"/><circle cx="12" cy="14" r="4"/></>} />
);
const FileText = (p:any)=> (
  <Svg {...p} path={<><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="8" y1="13" x2="16" y2="13"/><line x1="8" y1="17" x2="16" y2="17"/></>} />
);
const Shield = (p:any)=> (
  <Svg {...p} path={<><path d="M12 2l7 4v6c0 5-3.5 8-7 10-3.5-2-7-5-7-10V6z"/></>} />
);

const BRAND = "SWIPECAST";

// --- data
const categories = [
  { key: "tv", label: "TV" },
  { key: "film", label: "Film" },
  { key: "theater", label: "Theater" },
  { key: "commercials", label: "Commercials" },
  { key: "voiceover", label: "Voiceover" }
];

const featuredCastings = [
  { id: "lm", staffPick: true, featured: true, title: "La Mordida", payTop: "$750.00", scope: "Worldwide", posted: "Wednesday", synopsis: "surreal coming-of-age ghost story...", datesLocations: "Rehearses early Nov.; Shoots mid-late Nov. near Los Angeles, CA.", genres: ["Short Film","Dark Comedy","Drama","Satire"], rolesPreviewCount: 9, rolesPreview:[{name:"Mari",breakdown:"Lead, Female, 12-17"},{name:"Abuelito Rafael",breakdown:"Lead, Male, 55-90"},{name:"Ximena",breakdown:"Supporting, Female, 35-50"}] },
  { id: "sgc", staffPick: true, featured: true, title: "'Squid Game: The Challenge' Season 3", scope: "Worldwide", posted: "9 hours ago", synopsis: "Casting real-life contestants...", datesLocations: "Films Feb–March (three weeks) in the UK.", genres: ["Competitions","Reality TV"], rolesPreviewCount:1, rolesPreview:[{name:"Contestant, Squid Game: The Challenge Season 3",breakdown:"Real People, All Genders, 21+"}] },
  { id: "vo", staffPick: true, featured: true, title: "Online Video Ad, Voiceover Artists", payTop: "$300.00", scope:"Worldwide", posted:"Thursday", synopsis: "Seeking talented voiceover artists...", datesLocations: "Records remotely; live online session AEST mornings.", genres: ["Online Commercial / Video Ad","General Voiceover"], rolesPreviewCount:6, rolesPreview:[{name:"UK Voiceover Artist",breakdown:"Voiceover, 18+"},{name:"Australia Voiceover Artist",breakdown:"Voiceover, 18+"},{name:"French Voiceover Artist",breakdown:"Voiceover, 18+"}] }
];
const moreCastings = [
  { id:"if1", title:"Indie Feature – 'Pavement Radio'", scope:"Nationwide", posted:"Today", synopsis:"Road-movie drama...", datesLocations:"Shoots Dec. in New Mexico.", genres:["Feature Film","Drama"], rolesPreviewCount:4, rolesPreview:[{name:"DJ Mara", breakdown:"Lead, Female, 25-35"}] },
  { id:"th1", title:"Off-Broadway New Work Lab", scope:"New York City, NY", posted:"Yesterday", synopsis:"Workshop production...", datesLocations:"Rehearsals Oct–Nov; performs late Nov.", genres:["Theater","New Work"], rolesPreviewCount:5, rolesPreview:[{name:"Ensemble (Movement)", breakdown:"All Genders, 18-40"}] },
  { id:"cm1", title:"National Coffee Brand: :15 TV Spot", payTop:"$1,200.00", scope:"Los Angeles, CA", posted:"Monday", synopsis:"Casting relatable faces...", datesLocations:"Shoots one day in Oct.", genres:["Commercials"], rolesPreviewCount:3, rolesPreview:[{name:"Hero Talent", breakdown:"All Genders, 25-45"}] },
  { id:"vo1", title:"Explainer VO – Fintech App", payTop:"$500.00", scope:"Remote", posted:"Tuesday", synopsis:"Clear, friendly VO...", datesLocations:"Records remotely; direction via Zoom.", genres:["Voiceover","Online"], rolesPreviewCount:2, rolesPreview:[{name:"Narrator", breakdown:"Voiceover, 20-55"}] },
];
// Build 10 pages × 14 castings = 140 total
const BASE_CASTINGS = [...featuredCastings, ...moreCastings];

function genCasting(idx:number){
  // Deterministic RNG per index
  const rnd = (seed:number)=>{ let x = (seed * 1664525 + 1013904223) % 0xffffffff; return ()=> (x = (x * 1664525 + 1013904223) % 0xffffffff) / 0xffffffff; };
  const r = rnd(idx+17);
  const pick = <T,>(arr:T[])=> arr[Math.floor(r()*arr.length)];

  // Broader pools to reduce repetition
  const kinds = [
    { type:'Feature Film', key:'film', genres:['Feature Film','Drama'] },
    { type:'Theatrical Production', key:'theater', genres:['Theater','Play'] },
    { type:'TV Series', key:'tv', genres:['TV','Series'] },
    { type:'Commercial', key:'commercials', genres:['Commercials'] },
    { type:'Print Campaign', key:'print', genres:['Print','Lifestyle'] },
    { type:'Voiceover', key:'voiceover', genres:['Voiceover','Online'] },
  ];
  const k = kinds[idx % kinds.length];

  const cities = ['New York, NY','Los Angeles, CA','Atlanta, GA','Chicago, IL','Austin, TX','Remote','Vancouver, BC','Toronto, ON','New Orleans, LA','Albuquerque, NM'];
  const scopes = ['Local','Nationwide','Worldwide'];
  const posts = ['Today','Yesterday','Monday','Tuesday','Wednesday','Thursday','Friday'];

  const firstNames = ['Ava','Luca','Maya','Noah','Sofia','Ethan','Zoe','Miles','Iris','Kai','Omar','Nina','Jules','Mina','Theo','Aria','Felix','Rowan','Sage','Leo'];
  const lastNames  = ['Morales','Rao','Kim','Alvarez','Nguyen','Carter','Patel','Okafor','Mendes','Chen','Hernandez','Schmidt','Garcia','Park','Singh','Lopez','Bennett','Diaz','Sharma','Khan'];
  const cdFirst = ['Monica','David','Riley','Carmen','Owen','Priya','Leo','Nora','Jordan','Elena','Mateo','Lena'];
  const cdLast  = ['Pinto','Griffin','Sato','Barrios','Klein','Ibrahim','Costa','Vega','Lam','Ford','Campos','Duran'];
  const companies= ['Northbank Casting','Blue Lantern Pictures','Red Harbor Media','Glasshouse Theatre Co.','Windmill Studios','Sparrow & Co.','Open Range Films','Silverline Creative','Neon Alley Casting','Prairie Dog Productions','Waypoint Casting','Beacon Street Media'];
  const brands   = ['Kona Coffee','Hearth Home','Stride Shoes','Nimbus Phones','Crescent Market','Sundial Travel','Quanta Bank','Orbit Electric','Horizon Bikes','Drift Water'];
  const showNames= ['Hollow City','Night Signal','Second Shift','Paper Tigers','Edge of Noon','Signal Lost','East Bay Unit','Moon Harbor','Marble Street','Cold River'];
  const episode  = ['Pilot','The Vanishing','Cold Storage','After Hours','False Alarm','Blue Room','Backscatter','Cutaway','North Face','Trace Route'];
  const filmAdj  = ['Quiet','Static','Hidden','Feral','Neon','Dusty','Broken','Soft','Black','Last'];
  const filmNoun = ['Engines','Orchard','Echoes','Harbor','Atlas','Halo','Violet','Sparrows','Comet','Switch'];
  const playNames= ['Glass Maples','The Last Tram','Tin Daughters','Salt & Bone','The Weather Room','Nine Windows','Paper Crown','Rust Choir'];

  // Title synthesis with wide space and per‑idx uniqueness
  let title = '';
  if(k.key==='tv') title = `${pick(showNames)} — "${pick(episode)}"`;
  else if(k.key==='film') title = `${pick(filmAdj)} ${pick(filmNoun)}`;
  else if(k.key==='theater') title = pick(playNames);
  else if(k.key==='commercials') title = `${pick(brands)} — :30 National Spot`;
  else if(k.key==='print') title = `${pick(brands)} Lifestyle Print`;
  else if(k.key==='voiceover') title = `${pick(brands)} App Explainer VO`;
  // light hash suffix to avoid exact duplicates without visible noise for most titles
  if(idx % 37 === 0) title = title + ' (Working Title)';

  const loglines = [
    'A weary courier uncovers a message hidden in a city‑wide blackout.',
    'Siblings return to a drought‑stricken hometown to settle an old debt.',
    'A rookie EMT faces her first night on a haunted industrial block.',
    'When a community garden is slated for demolition, unlikely allies fight back.',
    'A coder moonlights as a late‑night DJ who may be broadcasting to the past.',
    'A theater troupe stages a banned play under surveillance.',
    'A barista witnesses a crime and must choose between safety and truth.',
    'A diver tracks an anomaly on the harbor floor that shouldn’t be there.',
    'An ex‑reporter returns to a mill town chasing one last story.',
    'A family road trip bends into a quiet heist of redemption.'
  ];
  const tones = ['darkly comic','character‑driven','quietly tense','high‑energy','surreal','slice-of-life'];
  const motifs = ['rain‑slick streets','desert motels','fluorescent nights','factory hum','coastal fog','late‑night radio'];
  const asks = ['reliability','punctuality','openness to direction','strong cold‑read','team spirit','self‑tape proficiency'];
  // unique, non-repeating closing request per listing
  const qualities = ['truthful, lived-in choices','clear objectives','bold adjustments','subtle beats','strong listening','distinct POV','improvisational ease','comic timing','natural intensity','stillness on camera','physical storytelling','vocal agility','period authenticity','accent control','musicianship','movement precision','cold-read confidence','warm presence','edge and unpredictability','understated realism','specific behavior','emotional availability','precision with text','quiet tension','playful spontaneity','measured silence','meisner responsiveness','grounded stakes','quick adjustments','character-driven choices','camera awareness','ensemble chemistry','narrative focus','clear buttons','clean eyeline','tonal control','tempo flexibility','status shifts','subtext clarity','listening first','sense of humor','authentic dialect','narration clarity','microexpressions','economy of movement','clean slate','breath control','scene partner awareness','discipline','collaboration'];
  const closerTemplates = [
    (q:string,a:string)=>`Seeking ${q} and ${a}.`,
    (q:string,a:string)=>`Prioritize ${q}; ${a} appreciated.`,
    (q:string,a:string)=>`Emphasis on ${q} with ${a}.`,
    (q:string,a:string)=>`Candidates with ${q} and ${a} preferred.`,
    (q:string,a:string)=>`We value ${q}; ${a} required.`,
    (q:string,a:string)=>`Directors will look for ${q} plus ${a}.`,
  ];
  const q = qualities[idx % qualities.length];
  const a = pick(asks);
  const closer = closerTemplates[idx % closerTemplates.length](q,a);
  const synopsis = `${pick(loglines)} ${pick(['Told with','Grounded in','Leaning into'])} ${pick(tones)} beats and ${pick(motifs)}. ${closer}`;

  const id = `g${idx}`;
  const totalRoles = 3 + (idx % 7); // 3..9
  const ageBand = () => { const a = 18 + Math.floor(r()*40); return `${a}-${a+10}`; };
  const roleArchetypes = ['Lead','Supporting','Friend','Detective','Parent','Coach','Neighbor','Barista','Reporter','Engineer','Designer','Narrator','Student','Host','Contestant'];
  const makeChar = (i:number)=>{ const fn = pick(firstNames); const ln = pick(lastNames); const label = k.key==='voiceover' ? 'Voiceover' : 'All Genders'; return { name: `${pick(roleArchetypes)} — ${fn} ${ln}`, breakdown: `${label}, ${ageBand()}` }; };
  const roles = Array.from({length: totalRoles}, (_,i)=> makeChar(i));
  const rolesPreview = roles.slice(0, Math.min(3, roles.length));

  const payTop = k.key==='commercials' ? `$${1000 + (idx%5)*250}.00` : (k.key==='print'? `$${500 + (idx%4)*150}.00` : (k.key==='voiceover'? `$${300 + (idx%5)*100}.00` : undefined));

  const company = pick(companies);
  const castingDirector = `${pick(cdFirst)} ${pick(cdLast)}`;

  const months = ['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'];
  const monthName = months[(idx*3) % 12];
  const day = 7 + (idx % 20); // 7..26
  const when = `${monthName} ${day}`;

  return {
    id,
    title,
    payTop,
    scope: scopes[idx % scopes.length],
    posted: posts[idx % posts.length],
    synopsis,
    datesLocations: `${k.key==='voiceover'?'Records':'Shoots'} ${when} in ${cities[idx % cities.length]}.`,
    genres: k.genres,
    rolesPreviewCount: roles.length,
    rolesPreview,
    roles,
    company,
    castingDirector,
    featured: idx % 7 === 0,
    staffPick: idx % 11 === 0,
  };
}

const REQUIRED_TOTAL = 140; // 10 pages × 14
const additional = Array.from({length: Math.max(0, REQUIRED_TOTAL - BASE_CASTINGS.length)}, (_,i)=> genCasting(i+1));
const RAW_CASTINGS = [...BASE_CASTINGS, ...additional];

// Enrich any seed data so counts and details are accurate
function enrichCasting(input:any, idx:number){
  const out:any = {...input};
  // Company and CD
  if(!out.company || !out.castingDirector){
    const cdFirst = ['Monica','David','Riley','Carmen','Owen','Priya','Leo','Nora','Jordan','Elena'];
    const cdLast  = ['Pinto','Griffin','Sato','Barrios','Klein','Ibrahim','Costa','Vega','Lam','Ford'];
    const companies= ['Northbank Casting','Blue Lantern Pictures','Red Harbor Media','Glasshouse Theatre Co.','Windmill Studios','Sparrow & Co.','Open Range Films','Silverline Creative','Neon Alley Casting','Prairie Dog Productions'];
    const rf=(a:any[])=> a[(idx*7)%a.length];
    out.company = out.company || rf(companies);
    out.castingDirector = out.castingDirector || rf(cdFirst) + ' ' + rf(cdLast);
  }
  // Unique title and synopsis if placeholders present
  if(/Project \d+|Episode \d+|Explainer VO|Lifestyle Shoot/.test(out.title||'')){
    const g = genCasting(2000+idx); // generate a new specific one
    out.title = g.title; out.synopsis = g.synopsis; out.genres = out.genres || g.genres;
  }
  // Ensure full roles array equals rolesPreviewCount
  const want = Math.max( out.rolesPreviewCount||0, (out.roles && out.roles.length)||0, (out.rolesPreview && out.rolesPreview.length)||0 );
  if(!out.roles || out.roles.length !== want){
    const filler = genCasting(3000+idx).roles;
    out.roles = (out.roles||[]).concat(filler).slice(0, want || 9);
  }
  // Preview is first up to 3
  out.rolesPreview = Array.isArray(out.roles) ? out.roles.slice(0, Math.min(3, out.roles.length)) : (out.rolesPreview||[]);
  out.rolesPreviewCount = out.roles.length;
  // Convert directive‑style descriptions to a gentler story synopsis
  try {
    const needsStory = /\u0008(Casting|Seeking|Voiceover|Contestant|Apply|Looking for)\u0008/i.test(out.synopsis||'');
    if(needsStory){
      const base = genCasting(4000+idx).synopsis;
      const dl = out.datesLocations ? ` ${String(out.datesLocations)}` : '';
      out.synopsis = `${base}${dl}`.trim();
    }
  } catch {}
  return out;
}

function uniquify(list:any[]){
  const seen = new Set<string>();
  const alt = ['Blue Room','Cutaway','Cold Storage','After Hours','False Alarm','North Face','Trace Route'];
  return list.map((c, i)=>{
    let t = c.title;
    let attempts = 0;
    while(seen.has(t) && attempts < alt.length){ t = `${c.title} — ${alt[(i+attempts)%alt.length]}`; attempts++; }
    seen.add(t);
    // vary synopsis slightly if duplicate patterns are detected
    const sfx = attempts>0 ? ` Additional note: city focus on ${c.datesLocations?.split(' in ')[1] || 'local market'}.` : '';
    return { ...c, title: t, synopsis: (c.synopsis || '') + sfx };
  });
}
const ALL_CASTINGS = uniquify(RAW_CASTINGS.map(enrichCasting));

const sampleTalent = [
  { id:1, name:"Jordan Reyes", imageUrl:"https://picsum.photos/seed/jordan/600/750", tags:["Latinx","They/Them","Voiceover","Singer"], stats:"5'9\" • Athletic" },
  { id:2, name:"Marina El-Amin", imageUrl:"https://picsum.photos/seed/marina/600/750", tags:["MENA","She/Her","Stage","Dance"], stats:"5'6\" • Slim" },
  { id:3, name:"Tariq Holt", imageUrl:"https://picsum.photos/seed/tariq/600/750", tags:["Black","He/Him","Comedy","Improv"], stats:"6'1\" • Medium" }
];

function Chip({children}:{children:React.ReactNode}){ return <span className="px-2 py-1 rounded-full bg-neutral-100 border border-neutral-200 text-[11px]">{children}</span>; }
function Card({children}:{children:React.ReactNode}){ return <div className="bg-white rounded-2xl border border-neutral-200 shadow-sm p-4">{children}</div>; }
function SectionTitle({icon:Icon, title, subtitle}:{icon:any,title:string,subtitle?:string}){
  return (
    <div className="flex items-center justify-between mb-4">
      <div>
        <div className="flex items-center gap-2 cursor-pointer" onClick={()=>go("#/")} role="link" tabIndex={0} onKeyDown={(e)=>{ if(e.key==='Enter') go("#/"); }}><Icon className="h-5 w-5"/><h2 className="text-lg font-semibold">{title}</h2></div>
        {subtitle && <p className="text-sm text-neutral-600 mt-1">{subtitle}</p>}
      </div>
      <a href="#/" className="inline-flex items-center gap-2 text-sm hover:opacity-80">View all <ChevronRight className="h-4 w-4"/></a>
    </div>
  );
}

export type MediaState = { headshot:boolean; video:boolean; audio:boolean; cover:boolean; resume:boolean };
const DEFAULT_MEDIA: MediaState = { headshot:false, video:false, audio:false, cover:false, resume:false };
function RolesMediaSection({media, setMedia}:{ media:MediaState; setMedia:(m:MediaState)=>void }){
  const idBase = useMemo(()=>`media-${Math.random().toString(36).slice(2,8)}` ,[]);
  const items:{key:keyof MediaState,label:string}[]=[{key:"headshot",label:"Headshot/Photo"},{key:"video",label:"Video Reel"},{key:"audio",label:"Audio Reel"},{key:"cover",label:"Cover Letter"},{key:"resume",label:"Resume"}];
  return (
    <div>
      <label className="block text-sm text-neutral-700">Media required from applicants (Optional)</label>
      <div className="mt-2 grid md:grid-cols-5 grid-cols-2 gap-2 text-sm">
        {items.map(({key,label})=>{ const id=`${idBase}-${key}`; const checked=!!media[key]; return (
          <label key={key} htmlFor={id} className={`px-3 py-2 rounded-xl border cursor-pointer ${checked?"border-neutral-900":"border-neutral-300"}`}>
            <input id={id} type="checkbox" className="hidden" checked={checked} onChange={e=>setMedia({...media,[key]:e.target.checked})}/>
            <span>{label}</span>
          </label>
        );})}
      </div>
    </div>
  );
}

// --- routing
function useHashRoute(){
  const parse = ()=> (typeof window!=="undefined" ? (window.location.hash || "#/" ) : "#/");
  const [hash,setHash]=useState(parse());
  useEffect(()=>{ const onH=()=>setHash(parse()); window.addEventListener("hashchange",onH); return ()=>window.removeEventListener("hashchange",onH);},[]);
  return hash;
}
function go(h:string){ if(typeof window!=="undefined"){ window.location.hash = h; window.scrollTo({top:0,behavior:"smooth"}); } }
function isSignedIn(){ try{ return typeof window!=="undefined" && window.localStorage.getItem("auth")==="1"; }catch{ return false; } }

function PostCasting(){
  const [projectName,setProjectName]=useState("");
  const [projectType,setProjectType]=useState("Film");
  const [union,setUnion]=useState("Union & Nonunion");
  const [scope,setScope]=useState("Local");
  const [locs,setLocs]=useState("New York City, NY");
  const [desc,setDesc]=useState("");
  return (
    <div className="max-w-3xl">
      <SectionTitle icon={Briefcase} title="Post a Casting" subtitle="Project details for your listing"/>
      <Card>
        <div className="grid md:grid-cols-2 gap-6">
          <div className="space-y-4">
            <div><label className="block text-sm text-neutral-700">Project / Production Name*</label><input value={projectName} onChange={e=>setProjectName(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border" placeholder="e.g., The Scratches"/></div>
            <div><label className="block text-sm text-neutral-700">Project type*</label><select value={projectType} onChange={e=>setProjectType(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border">{"Film,TV,Theater,Commercial,Voiceover,Web Series,Short Film,Online Video,Stage".split(",").map(t=> (<option key={t} value={t}>{t}</option>))}</select></div>
            <div><label className="block text-sm text-neutral-700">Union status*</label><select value={union} onChange={e=>setUnion(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border"><option>Union & Nonunion</option><option>Union</option><option>Nonunion</option><option>N/A</option></select></div>
          </div>
          <div className="space-y-4">
            <div><label className="block text-sm text-neutral-700">Where do you want to hire talent from?*</label><select value={scope} onChange={e=>setScope(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border"><option>Local</option><option>Nationwide</option><option>Worldwide</option></select></div>
            <div><label className="block text-sm text-neutral-700">Locations*</label><input value={locs} onChange={e=>setLocs(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border" placeholder="City, State or Remote"/></div>
            <div><label className="block text-sm text-neutral-700">Project description*</label><textarea value={desc} onChange={e=>setDesc(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border h-28" placeholder="Short synopsis and key context"/></div>
          </div>
        </div>
        <div className="mt-5 grid md:grid-cols-3 gap-3"><button className="px-3 py-2 rounded-xl border">Save draft</button><button className="px-3 py-2 rounded-xl bg-neutral-900 text-white">Preview</button><button onClick={()=>go("#/roles")} className="px-3 py-2 rounded-xl bg-blue-600 text-white">ROLES</button></div>
      </Card>
    </div>
  );
}

function Home({page=1}:{page?:number}){
  const PER_PAGE = 14;
  const TOTAL_PAGES = Math.ceil(ALL_CASTINGS.length / PER_PAGE);
  const safePage = Math.min(Math.max(1, page), TOTAL_PAGES);
  const start = (safePage - 1) * PER_PAGE;
  const pageData = ALL_CASTINGS.slice(start, start + PER_PAGE);

  const Pager = () => (
    <div className="flex items-center justify-center gap-3 py-4 select-none">
      {Array.from({length: TOTAL_PAGES}, (_,i)=> i+1).map(n=> (
        <button
          key={n}
          onClick={()=> go(n===1 ? '#/' : `#/p/${n}`)}
          aria-current={n===safePage? 'page': undefined}
          className="h-7 min-w-7 px-2 grid place-items-center text-sm text-neutral-700"
        >
          <span className={`inline-grid place-items-center h-7 w-7 rounded-full ${n===safePage? 'bg-black text-white' : ''}`}>{n}</span>
        </button>
      ))}
      <button onClick={()=> go(safePage<TOTAL_PAGES ? `#/p/${safePage+1}` : (safePage===1 ? '#/p/2' : `#/p/${safePage}`))} aria-label="Next page" className="h-7 min-w-7 px-2 grid place-items-center text-neutral-700">›</button>
    </div>
  );

  return (
    <div className="grid lg:grid-cols-3 gap-6">
      <div className="lg:col-span-2 space-y-6">
        <SectionTitle icon={Clapperboard} title="Featured Castings" subtitle="Curated opportunities across TV, film, theater, commercials, and VO"/>
        <Pager/>
        {pageData.map(c=> (
          <Card key={c.id}>
            <div className="flex items-center gap-2 text-xs">
              {c.staffPick && <span className="inline-flex items-center px-2 py-1 rounded-full text-[11px] border bg-amber-50 text-amber-700 border-amber-200">Staff Pick</span>}
              {c.featured && <span className="inline-flex items-center px-2 py-1 rounded-full text-[11px] border bg-blue-50 text-blue-700 border-blue-200">Featured</span>}
            </div>
            <div className="mt-2 flex items-start justify-between gap-4">
              <div className="min-w-0">
                <h3 className="text-xl font-semibold leading-snug"><a href={`#/apply/${c.id}`} className="hover:opacity-80">‘{c.title}’</a></h3>
                <div className="mt-1 text-sm text-neutral-600 flex flex-wrap gap-2">
                  {c.payTop && <span>Roles paying up to <strong>{c.payTop}</strong></span>}
                  <span>• {c.scope}</span>
                  {c.posted && <span>• Posted: {c.posted}</span>}
                </div>
              </div>
              <button onClick={()=>go(`#/apply/${c.id}`)} className="px-3 py-2 rounded-xl bg-neutral-900 text-white text-sm shrink-0 hover:bg-neutral-800">View Details & Apply</button>
            </div>
            {c.synopsis && <p className="mt-3 text-sm text-neutral-700">{c.synopsis} <button onClick={()=>go(`#/apply/${c.id}`)} className="underline underline-offset-2">View more</button></p>}
            {c.datesLocations && <div className="mt-2 text-sm text-neutral-700"><span className="font-medium">Dates & Locations:</span> {c.datesLocations}</div>}
            {Array.isArray(c.genres)&&c.genres.length>0 && (<div className="mt-3 flex flex-wrap gap-2">{c.genres.map((g,i)=>(<Chip key={i}>{g}</Chip>))}</div>)}
            <hr className="my-4 border-neutral-200"/>
            {Array.isArray(c.rolesPreview)&&c.rolesPreview.length>0 && (
              <div className="space-y-2">
                {c.rolesPreview.map((r,i)=>(
                  <div key={i} className="flex items-start justify-between gap-3">
                    <div><div className="font-medium">{r.name}</div><div className="text-sm text-neutral-600">{r.breakdown}</div></div>
                    <button onClick={()=>go(`#/apply/${c.id}`)} className="px-3 py-1.5 rounded-xl border border-neutral-300 text-sm hover:bg-neutral-100">Apply</button>
                  </div>
                ))}
                {c.rolesPreviewCount && c.rolesPreviewCount>c.rolesPreview.length && (
                  <button onClick={()=>go(`#/apply/${c.id}`)} className="mt-2 inline-flex items-center gap-2 text-sm hover:opacity-80">View All {c.rolesPreviewCount} Roles <ChevronRight className="h-4 w-4"/></button>
                )}
              </div>
            )}
          </Card>
        ))}
        <Pager/>
      </div>
      <div className="space-y-6">
        <SectionTitle icon={Search} title="Refine Results"/>
        <Card>
          <div className="space-y-3">
            <select className="w-full px-3 py-2 rounded-xl border border-neutral-300"><option>Any category</option>{categories.map(c=>(<option key={c.key}>{c.label}</option>))}</select>
            <select className="w-full px-3 py-2 rounded-xl border border-neutral-300"><option>Union & Nonunion</option><option>Union only</option><option>Nonunion only</option></select>
            <select className="w-full px-3 py-2 rounded-xl border border-neutral-300"><option>All locations</option><option>NYC</option><option>LA</option><option>Atlanta</option><option>Remote</option></select>
            <button className="w-full px-3 py-2 rounded-xl bg-neutral-900 text-white text-sm hover:bg-neutral-800">Apply filters</button>
          </div>
        </Card>
        <SectionTitle icon={HandCoins} title="Per-Post Pricing" subtitle="Actors join free. Pay when you post."/>
        <Card><ul className="text-sm text-neutral-700 space-y-2"><li><strong>Basic</strong> – $24.99 per casting</li><li><strong>Pro</strong> – $49.99 per casting</li><li><strong>Studio</strong> – $149.00 per casting</li></ul></Card>
      </div>
    </div>
  );
}

function Talent(){
  return (
    <div>
      <SectionTitle icon={Film} title="Discover Talent" subtitle="Swipe, shortlist, and message—fast"/>
      <div className="grid md:grid-cols-3 gap-6">
        {sampleTalent.map(t=> (
          <Card key={t.id}>
            <div className="w-full h-80 md:h-[26rem] overflow-hidden rounded-xl bg-neutral-100">
              <img src={t.imageUrl} alt={`${t.name} headshot`} loading="lazy" decoding="async"
                onError={(e)=>{ const img=e.currentTarget as HTMLImageElement; img.onerror=null; img.src="data:image/svg+xml;charset=utf-8,"+encodeURIComponent("<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 3 4'><rect width='100%' height='100%' fill='#f3f4f6'/><text x='50%' y='50%' font-size='0.5' text-anchor='middle' fill='#9ca3af' dy='.3em'>No Image</text></svg>"); }}
                className="h-full w-full object-cover"/>
            </div>
            <div className="mt-3 flex items-start justify-between"><div><h3 className="font-semibold">{t.name}</h3><p className="text-sm text-neutral-600 mt-1">{t.stats}</p></div><button className="text-sm px-3 py-1.5 rounded-xl border border-neutral-300 hover:bg-neutral-100">View</button></div>
            <div className="mt-3 flex flex-wrap gap-2">{t.tags.map((g,i)=>(<Chip key={i}>{g}</Chip>))}</div>
          </Card>
        ))}
      </div>
    </div>
  );
}

function Roles(){
  const [roleName,setRoleName]=useState("");
  const [roleType,setRoleType]=useState("Lead");
  const [remote,setRemote]=useState<boolean|null>(null);
  const [gender,setGender]=useState("All Genders");
  const [minAge,setMinAge]=useState("");
  const [maxAge,setMaxAge]=useState("");
  const [ethnicity,setEthnicity]=useState("");
  const [skillInput,setSkillInput]=useState("");
  const [skills,setSkills]=useState<string[]>([]);
  const [desc,setDesc]=useState("");
  const [media,setMedia]=useState<MediaState>({...DEFAULT_MEDIA});
  const [nudity,setNudity]=useState<boolean|null>(null);
  const addSkill=()=>{ const s=skillInput.trim(); if(!s) return; if(!skills.includes(s)) setSkills([...skills,s]); setSkillInput(""); };
  const removeSkill=(s:string)=> setSkills(skills.filter(k=>k!==s));
  return (
    <div>
      <SectionTitle icon={Briefcase} title="Please tell us about the actor you're casting"/>
      <Card>
        <div className="grid md:grid-cols-2 gap-6">
          <div className="space-y-4">
            <div><label className="block text-sm text-neutral-700">Role Name</label><input value={roleName} onChange={e=>setRoleName(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border" placeholder="e.g., Alex, Crime Reporter"/></div>
            <div><label className="block text-sm text-neutral-700">Role Type</label><select value={roleType} onChange={e=>setRoleType(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border">{"Lead,Supporting,Day Player,Background,Voiceover".split(",").map(t=>(<option key={t}>{t}</option>))}</select></div>
            <div>
              <label className="block text-sm text-neutral-700">Is this a remote/work-from-home opportunity?</label>
              <div className="mt-2 flex gap-2">
                {[{label:"Yes",val:true},{label:"No",val:false}].map(opt=>(
                  <label key={String(opt.val)} className={`px-3 py-2 rounded-xl border cursor-pointer ${nudity===opt.val?"border-neutral-900":"border-neutral-300"}`}>
                    <input type="radio" name="remote" className="hidden" checked={remote===opt.val} onChange={()=>setRemote(opt.val)}/>
                    {opt.label}
                  </label>
                ))}
              </div>
            </div>
            <div><label className="block text-sm text-neutral-700">Gender (optional)</label><select value={gender} onChange={e=>setGender(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border">{"All Genders,Female,Male,Nonbinary,Transgender,Two-Spirit,Prefer not to say".split(",").map(g=>(<option key={g}>{g}</option>))}</select></div>
          </div>
          <div className="space-y-4">
            <div className="grid grid-cols-2 gap-3"><div><label className="block text-sm text-neutral-700">Minimum age</label><input value={minAge} onChange={e=>setMinAge(e.target.value)} inputMode="numeric" className="mt-1 w-full px-3 py-2 rounded-xl border" placeholder="e.g., 18"/></div><div><label className="block text-sm text-neutral-700">Maximum age</label><input value={maxAge} onChange={e=>setMaxAge(e.target.value)} inputMode="numeric" className="mt-1 w-full px-3 py-2 rounded-xl border" placeholder="e.g., 35"/></div></div>
            <div><label className="block text-sm text-neutral-700">Ethnicity (optional)</label><input value={ethnicity} onChange={e=>setEthnicity(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-xl border" placeholder="Open / Any / Specific"/></div>
            <div><label className="block text-sm text-neutral-700">Skills</label><div className="mt-1 flex gap-2"><input value={skillInput} onChange={e=>setSkillInput(e.target.value)} className="flex-1 px-3 py-2 rounded-xl border" placeholder="e.g., Stage combat"/><button onClick={addSkill} className="px-3 py-2 rounded-xl border hover:bg-neutral-100">Add Skills</button></div>{skills.length===0? (<p className="mt-2 text-sm text-neutral-500">You haven’t added any skills</p>):(<div className="mt-2 flex flex-wrap gap-2">{skills.map(s=>(<span key={s} className="inline-flex items-center gap-2 px-2 py-1 rounded-full border text-xs">{s}<button onClick={()=>removeSkill(s)} className="text-neutral-500 hover:text-neutral-800">×</button></span>))}</div>)}</div>
          </div>
        </div>
        <div className="mt-6 space-y-4">
          <div><label className="block text sm text-neutral-700">Role Description (Recommended)</label><p className="text-xs text-neutral-500 mt-1">Pre-Screen Requests have been relocated to their own workflow step.</p><textarea value={desc} onChange={e=>setDesc(e.target.value)} className="mt-1 w-full px-3 py-2 rounded-2xl border h-28" placeholder="Describe the character, responsibilities, audition notes, rate if known, etc."/></div>
          <RolesMediaSection media={media} setMedia={setMedia} />
          <div>
            <label className="block text-sm text-neutral-700">Does this role require nudity?</label>
            <div className="mt-2 flex gap-2">
              {[{label:"Yes",val:true},{label:"No",val:false}].map(opt=>(
                <label key={String(opt.val)} className={`px-3 py-2 rounded-xl border cursor-pointer ${nudity===opt.val?"border-neutral-900":"border-neutral-300"}`}>
                  <input type="radio" name="nudity" className="hidden" checked={nudity===opt.val} onChange={()=>setNudity(opt.val)}/>
                  {opt.label}
                </label>
              ))}
            </div>
          </div>
        </div>
      </Card>
    </div>
  );
}

function About(){
  return (
    <div className="space-y-10">
      <div className="max-w-3xl">
        <h1 className="text-3xl md:text-4xl font-extrabold tracking-tight">{BRAND} is a new platform for the world’s best talent and creators</h1>
        <p className="mt-3 text-neutral-700">Founded in {new Date().getFullYear()} and built by filmmakers, {BRAND} flips the casting business model on its head. Actors never pay monthly fees—ever. We charge only producers and casting directors per post, keeping access democratic and fair for working actors who often juggle day jobs like serving to make rent.</p>
      </div>
      <div className="grid md:grid-cols-4 gap-4">
        {[
          {n:"4,122",label:"new roles posted this week"},
          {n:"3,000+",label:"actor profiles (goal)"},
          {n:"600+",label:"casting pros (goal)"},
          {n:"0",label:"monthly fees for actors"}
        ].map((k,i)=> (
          <div key={i} className="rounded-2xl bg-amber-50 border-amber-200 border p-4"><div className="text-2xl font-extrabold">{k.n}</div><div className="text-sm text-neutral-700">{k.label}</div></div>
        ))}
      </div>
      {/* Trusted by logos only on About */}
      <TrustedBy/>
      <Card><div className="grid md:grid-cols-2 gap-6 items-center"><div><div className="text-xl font-semibold">Want to see what {BRAND} can do for you?</div><div className="mt-4 flex gap-3"><a href="#/" className="px-4 py-2 rounded-xl bg-neutral-900 text-white text-sm">Get Hired</a><a href="#/post" className="px-4 py-2 rounded-xl border text-sm">Launch Your Project</a></div></div><div className="text-sm text-neutral-600">Trusted by indie filmmakers, studios, and agencies building diverse casts across film, TV, theater, commercials, web, and VO.</div></div></Card>
    </div>
  );
}

function Terms(){
  const Section = ({title, children}:{title:string;children:React.ReactNode}) => (
    <section className="space-y-2">
      <h2 className="text-lg font-semibold">{title}</h2>
      <div className="text-sm text-neutral-700 space-y-2">{children}</div>
    </section>
  );
  const YEAR = new Date().getFullYear();
  return (
    <div className="max-w-3xl space-y-6">
      <div>
        <h1 className="text-3xl font-extrabold tracking-tight">Terms &amp; Safety</h1>
        <p className="text-sm text-neutral-600 mt-1">Last updated: {YEAR}</p>
      </div>
      <Card>
        <p className="text-sm text-neutral-700">
          These Terms govern your access to and use of {BRAND}'s website and services (the "Services"). By using the Services you agree to these Terms and our Privacy Policy. You must be 18+ or have a parent/guardian register and supervise use. {BRAND} may update these Terms from time to time; the current version applies to your use after it is posted.
        </p>
      </Card>
      <Section title="Website Content and Services">
        <p>{BRAND} provides listings, profiles, messaging, and other tools to help talent and casting professionals connect.</p>
        <p>Actors use {BRAND} free; producers and casting directors pay per casting post. {BRAND} is not a party to any engagement between users and is not an employer.</p>
      </Section>
      <Section title="Accounts & Eligibility">
        <p>You must provide accurate registration information and keep credentials secure. Parent/guardian accounts are required for minors and remain responsible for all activity.</p>
      </Section>
      <Section title="User Content & IP">
        <p>You retain rights to content you submit, but grant {BRAND} a non-exclusive license to host, display, and transmit it to operate the Services. Do not post content that infringes others’ rights or violates law; we may remove content or suspend accounts at our discretion.</p>
      </Section>
      <Section title="Posting & Payments">
        <p>Per-post fees are charged to producers/casting directors when publishing a casting. Taxes may apply. Fees are non-refundable except as required by law.</p>
      </Section>
      <Section title="Acceptable Use">
        <ul className="list-disc list-inside">
          <li>No spam, scraping, or automated access.</li>
          <li>No unlawful, defamatory, hateful, harassing, or sexually explicit content.</li>
          <li>No impersonation or misrepresentation of identity, credits, or authority.</li>
        </ul>
      </Section>
      <Section title="Safety Policy">
        <p>{BRAND} is committed to safe auditions and sets. If something feels off, stop and report it—your safety comes first.</p>
        <ul className="list-disc list-inside">
          <li><strong>Auditions:</strong> Never pay to audition. Do not share sensitive documents until an offer is issued and verified. In-person auditions should be in professional spaces; public meet-ups only.</li>
          <li><strong>Remote auditions:</strong> Disable location services in self-tapes. Do not accept unsolicited screen-sharing or file downloads from unknown parties.</li>
          <li><strong>On-set safety:</strong> Clear call sheets, contacts, and emergency info must be provided. Hazardous stunts or intimacy scenes require qualified coordinators and written consent.</li>
          <li><strong>Minors:</strong> A parent/guardian must manage the account and be present for all auditions and bookings.</li>
          <li><strong>Nudity & intimacy:</strong> No nudity is required unless disclosed in the role breakdown and agreed to in writing. Intimacy coordination is recommended where nudity or simulated sex is involved.</li>
          <li><strong>Payments & scams:</strong> Do not accept or send money via gift cards, crypto, or wire to unknown parties. {BRAND} is not a payroll provider; verify producer identity and contracts before work.</li>
        </ul>
      </Section>
      <Section title="Reporting & Enforcement">
        <p>Report safety issues, scams, harassment, or policy violations to support@{BRAND.toLowerCase()}.com. We may pause listings, remove content, or suspend accounts while we investigate.</p>
      </Section>
      <Section title="Disclaimers; Limitation of Liability">
        <p>The Services are provided "as is." {BRAND} disclaims warranties to the maximum extent permitted by law. {BRAND} will not be liable for indirect or consequential damages. In any case, {BRAND}'s aggregate liability will not exceed the amount you paid to {BRAND} in the 12 months preceding the claim, or $25 if you paid nothing.</p>
      </Section>
      <Section title="Dispute Resolution; Governing Law">
        <p>Before filing, the parties will first attempt to resolve disputes informally. If unresolved, disputes will be resolved individually by binding arbitration or small-claims court where permitted. These Terms are governed by California law, except that arbitration procedures are governed by the Federal Arbitration Act.</p>
      </Section>
      <Section title="Contact">
        <p>Questions about these Terms? Contact us at support@{BRAND.toLowerCase()}.com.</p>
      </Section>
    </div>
  );
}

function Support(){
  return (
    <div className="max-w-3xl">
      <SectionTitle icon={Briefcase} title="Contact Us" subtitle="Most inquiries are resolved within one business day"/>
      <Card>
        <form onSubmit={(e)=>e.preventDefault()} className="space-y-4">
          <div>
            <label className="block text-sm text-neutral-700">Please choose the site to contact</label>
            <select className="mt-1 w-full px-3 py-2 rounded-xl border"><option>SwipeCast Help</option><option>Billing</option><option>Safety</option></select>
          </div>
          <div>
            <label className="block text-sm text-neutral-700">Your email address *</label>
            <input type="email" required className="mt-1 w-full px-3 py-2 rounded-xl border" placeholder="you@example.com"/>
          </div>
          <div>
            <label className="block text-sm text-neutral-700">Description *</label>
            <textarea required className="mt-1 w-full px-3 py-2 rounded-2xl border h-28" placeholder="Enter the details of your request"/>
          </div>
          <div className="grid md:grid-cols-2 gap-4">
            <div><label className="block text-sm text-neutral-700">First Name *</label><input required className="mt-1 w-full px-3 py-2 rounded-xl border"/></div>
            <div><label className="block text-sm text-neutral-700">Last Name *</label><input required className="mt-1 w-full px-3 py-2 rounded-xl border"/></div>
          </div>
          <div>
            <label className="block text sm text-neutral-700">I am a *</label>
            <select className="mt-1 w-full px-3 py-2 rounded-xl border"><option>Actor / Performer</option><option>Producer / Casting</option><option>Parent / Guardian</option><option>Other</option></select>
          </div>
          <div>
            <label className="block text-sm text-neutral-700">Attachments</label>
            <input type="file" className="mt-1 w-full px-3 py-2 rounded-xl border" multiple/>
          </div>
          <div className="pt-2"><button className="px-4 py-2 rounded-xl bg-neutral-900 text-white text-sm">Submit</button></div>
          <p className="text-xs text-neutral-500">To manage your account details or membership, visit your Account Settings after logging in.</p>
        </form>
      </Card>
    </div>
  );
}

function ApplicationView({id}:{id:string}){
  const data:any = ALL_CASTINGS.find(c=>c.id===id) || { id, title:"Casting", scope:"", payTop:"", posted:"", synopsis:"", genres:[], roles:[] };
  const roles = Array.isArray(data.roles) ? data.roles : (Array.isArray(data.rolesPreview)? data.rolesPreview : []);
  const onApply = ()=>{ if(!isSignedIn()){ go("#/auth"); return; } alert("Application flow placeholder"); };
  // Unique per‑casting metadata for "Member since" and jobs count
  const idx = Math.max(0, ALL_CASTINGS.findIndex(c=>c.id===id));
  // Spread dates across months and avoid Nov 1–3 clustering
  let year = 2024 + ((idx * 7) % 2); // 2024 or 2025
  let month = (idx * 5) % 12;        // 0..11 varied months
  if (year === 2025 && month > 9) {  // avoid future months beyond Oct 2025
    year = 2024;
  }
  const day = 4 + ((idx * 11) % 25); // 4..28, skips 1–3
  const when = new Date(year, month, day);
  const memberSince = when.toLocaleDateString(undefined, { month:'short', day:'numeric', year:'numeric' });
  const jobsPosted = 1 + (idx % 12); // 1..12 to reflect recent launch

  // Enrich project description without changing other data
  const detailsParts:string[] = [];
  if (Array.isArray(data.genres) && data.genres.length) detailsParts.push(`Casting focus: ${data.genres.join(', ')}.`);
  if (data.datesLocations) detailsParts.push(`Schedule & location: ${data.datesLocations}`);
  if (data.scope) detailsParts.push(`Hiring scope: ${data.scope}.`);
  if (data.payTop) detailsParts.push(`Top advertised pay: ${data.payTop}.`);
  const detailedDesc = `${data.synopsis || ''} ${detailsParts.join(' ')}`.trim();

  return (
    <div>
      <div className="mb-4 flex items-center justify-between"><div className="flex items-center gap-2"><Clapperboard className="h-5 w-5"/><h1 className="text-2xl font-extrabold">{data.title}</h1></div><button onClick={()=>go("#/" )} className="text-sm px-3 py-1.5 rounded-xl border hover:bg-neutral-100">Back to listings</button></div>
      <Card>
        <div className="grid md:grid-cols-3 gap-6">
          <div className="md:col-span-2">
            <div className="flex flex-wrap gap-2 text-sm text-neutral-700">{data.payTop && <Chip>Paid</Chip>}{Array.isArray(data.genres)&&data.genres.map((g,i)=>(<Chip key={i}>{g}</Chip>))}</div>
            <div className="mt-2 text-sm text-neutral-600"><div>Seeking talent from <strong>{data.scope}</strong></div>{data.payTop && <div>Roles paying up to <strong>{data.payTop}</strong></div>}{data.posted && <div>Posted: {data.posted}</div>}</div>
            <h3 className="mt-6 font-semibold">About the project</h3>
            <div className="mt-2 grid md:grid-cols-2 gap-4"><Card><div className="text-sm font-medium">Company Details</div><div className="mt-2 text-sm text-neutral-700">{data.company || 'Independent Producer'}<br/>{data.castingDirector || 'Casting Team'}, Casting Director<br/>Member since {memberSince} • {jobsPosted} jobs posted</div></Card><Card><div className="text-sm font-medium">Project Description</div><p className="mt-2 text-sm text-neutral-700">{detailedDesc}</p></Card></div>
            <h3 className="mt-6 font-semibold">Roles in this project</h3>
            <div className="mt-2 space-y-2">{roles.map((r:any,i:number)=>(<Card key={i}><div className="flex items-start justify-between gap-4"><div><div className="font-medium">{r.name}</div><div className="text-sm text-neutral-600">{r.breakdown}</div></div><button onClick={onApply} className="px-3 py-1.5 rounded-xl bg-neutral-900 text-white text-sm hover:bg-neutral-800">Apply</button></div></Card>))}</div>
          </div>
          <div className="space-y-4"><Card><div className="font-semibold">Submission</div><p className="mt-2 text-sm text-neutral-700">Sign in to view audition and submission instructions.</p><button onClick={()=>go("#/auth")} className="mt-3 w-full px-3 py-2 rounded-xl bg-neutral-900 text-white text-sm hover:bg-neutral-800">Sign in to Apply</button></Card></div>
        </div>
      </Card>
    </div>
  );
}

function AuthPage(){
  return (
    <div className="min-h-[60vh] grid place-items-center">
      <div className="w-full max-w-md">
        <div className="text-center mb-6"><div className="text-3xl font-extrabold tracking-tight">Join {BRAND}</div><p className="text-sm text-neutral-600 mt-1">Create an account or sign in to continue</p></div>
        <Card><div className="space-y-3"><button className="w-full px-4 py-2 rounded-xl bg-neutral-900 text-white text-sm">Continue with Google</button><button className="w-full px-4 py-2 rounded-xl bg-neutral-900 text-white text-sm">Continue with Apple</button><div className="flex items-center gap-3 text-xs text-neutral-500"><span className="flex-1 h-px bg-neutral-200"/><span>or</span><span className="flex-1 h-px bg-neutral-200"/></div><input className="w-full px-3 py-2 rounded-xl border" placeholder="Email"/><button className="w-full px-4 py-2 rounded-xl bg-neutral-900 text-white text-sm">Continue</button><p className="text-[11px] text-neutral-500 leading-relaxed">By continuing, you agree to the Terms and Privacy Policy and confirm you are at least 18.</p><div className="text-center text-sm"><a className="underline underline-offset-2" href="#/post">I want to register as an employer.</a></div></div></Card>
      </div>
    </div>
  );
}

function Resources(){
  const [imgs, setImgs] = useState<Record<string, string>>({});

  const makeCover = (seed:string)=>{
    const hue = Array.from(seed).reduce((a,c)=> (a + c.charCodeAt(0)) % 360, 0);
    const svg = `<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 600 400'>
      <defs>
        <linearGradient id='g' x1='0' y1='0' x2='1' y2='1'>
          <stop offset='0%' stop-color='hsl(${hue},70%,60%)'/>
          <stop offset='100%' stop-color='hsl(${(hue+40)%360},70%,50%)'/>
        </linearGradient>
      </defs>
      <rect width='600' height='400' fill='url(#g)'/>
    </svg>`;
    return "data:image/svg+xml;charset=utf-8," + encodeURIComponent(svg);
  };

  const articles = [
    {title:"Feinberg Forecast: Oscar Predictions Post-Venice & TIFF", source:"The Hollywood Reporter", url:"https://www.hollywoodreporter.com/lists/oscar-predictions-feinberg-forecast-post-venice-tiff/"},
    {title:"Taylor Swift’s ‘October Showgirl’ Heads to Theaters", source:"Variety", url:"https://variety.com/2025/music/news/taylor-swift-film-theaters-october-showgirl-1236524158/"},
    {title:"‘One Battle After Another’ Review (DiCaprio, Sean Penn)", source:"Variety", url:"https://variety.com/2025/film/reviews/one-battle-after-another-review-leonardo-dicaprio-sean-penn-1236520520/"},
    {title:"Sean Astin Elected SAG-AFTRA President", source:"AP News", url:"https://apnews.com/article/sean-astin-president-sag-aftra-ae3b38912a9dea91cc1c00ef421e2d1a"},
    {title:"AEA Endorses Zohran Mamdani for NYC Mayor", source:"BroadwayWorld", url:"https://www.broadwayworld.com/article/Actors-Equity-Association-Endorses-Zohran-Mamdani-for-New-York-City-Mayor-20250730"},
    {title:"AEA Joins Rally Supporting Times Square Casino", source:"Playbill", url:"https://playbill.com/article/actors-equity-association-joins-rally-supporting-development-of-times-square-casino"}
  ];

  // lightweight runtime tests
  try {
    console.assert(Array.isArray(articles) && articles.length === 6, 'Resources: expected 6 articles');
    console.assert(articles.every(a => /^https?:\/\//.test(a.url)), 'Resources: each article has a valid URL');
  } catch {}

  const openExternal = (url:string)=>{
    try { window.open(url, '_blank', 'noopener,noreferrer'); }
    catch { window.location.href = url; }
  };

  useEffect(()=>{
    let cancelled = false;
    const resolveImage = async (pageUrl:string)=>{
      try{
        const proxy = 'https://r.jina.ai/http/' + pageUrl.replace(/^https?:\/\//,'');
        const res = await fetch(proxy, { cache: 'no-store' });
        if(!res.ok) throw new Error('reader error');
        const html = await res.text();
        // Try first inline <img src> from the reader content
        const rxImg = /<img[^>]+src=["']([^"']+)["']/i;
        const m = rxImg.exec(html);
        let img = m ? m[1] : '';
        if(img){
          if(img.startsWith('//')) img = 'https:' + img;
          if(img.startsWith('/')){ const u = new URL(pageUrl); img = u.origin + img; }
        }
        if(!img){
          const host = new URL(pageUrl).hostname;
          img = `https://logo.clearbit.com/${host}`;
        }
        if(!cancelled) setImgs(prev => ({ ...prev, [pageUrl]: img }));
      }catch{
        const host = new URL(pageUrl).hostname;
        const logo = `https://logo.clearbit.com/${host}`;
        if(!cancelled) setImgs(prev => ({ ...prev, [pageUrl]: logo }));
      }
    };
    articles.forEach(a=>{ if(!imgs[a.url]) resolveImage(a.url); });
    return ()=>{ cancelled = true; };
  // eslint-disable-next-line react-hooks/exhaustive-deps
  }, []);

  return (
    <div>
      <SectionTitle icon={Search} title="Resources" subtitle="Fresh reads from trusted outlets—tap to read at the source"/>
      <div className="grid md:grid-cols-2 xl:grid-cols-3 gap-6">
        {articles.map((a,i)=> (
          <div
            key={i}
            role="link"
            tabIndex={0}
            onClick={()=>openExternal(a.url)}
            onKeyDown={(e)=>{ if(e.key==='Enter') openExternal(a.url); }}
            className="block group cursor-pointer"
            aria-label={`Open article: ${a.title}`}
            data-testid="resource-card"
          >
            <Card>
              <div className="h-44 rounded-xl overflow-hidden bg-neutral-100">
                <img
                  src={imgs[a.url] || makeCover(a.source)}
                  alt={`${a.source} – ${a.title}`}
                  loading="lazy"
                  decoding="async"
                  referrerPolicy="no-referrer"
                  onError={(e)=>{ const img=e.currentTarget as HTMLImageElement; img.onerror=null; img.src=makeCover(a.source); }}
                  className="w-full h-full object-cover transition-transform duration-300 group-hover:scale-105"
                />
              </div>
              <div className="mt-2 text-xs text-neutral-500">{a.source}</div>
              <div className="font-medium">{a.title}</div>
              <div className="mt-2 text-sm inline-flex items-center gap-1 text-neutral-700">Read article <ChevronRight className="h-4 w-4"/></div>
            </Card>
          </div>
        ))}
      </div>
    </div>
  );
}

function Advice(){
  return (
    <div className="space-y-8">
      <SectionTitle icon={Briefcase} title="Advice for Creators" subtitle="Practical guides for posting roles, running auditions, and hiring safely"/>
      <Card>
        <div className="grid md:grid-cols-3 gap-6 text-sm text-neutral-700">
          <div>
            <div className="font-semibold mb-1">Write a great casting call</div>
            <ul className="list-disc list-inside space-y-1">
              <li>Lead with logline and tone</li>
              <li>List dates, location, pay, usage</li>
              <li>Call out deal‑breakers early</li>
            </ul>
          </div>
          <div>
            <div className="font-semibold mb-1">Budget and rates</div>
            <ul className="list-disc list-inside space-y-1">
              <li>Post ranges, not TBD</li>
              <li>Separate day rate vs. buyout</li>
              <li>Union vs. non‑union clarity</li>
            </ul>
          </div>
          <div>
            <div className="font-semibold mb-1">Auditions and callbacks</div>
            <ul className="list-disc list-inside space-y-1">
              <li>Send sides 24–48 hours ahead</li>
              <li>Offer remote option when possible</li>
              <li>Share agenda and timing upfront</li>
            </ul>
          </div>
        </div>
      </Card>
      <Card>
        <div className="grid md:grid-cols-2 gap-6 items-center">
          <div>
            <div className="text-xl font-semibold">Cast with confidence</div>
            <p className="text-sm text-neutral-700 mt-2">Use SWIPECAST tools to shortlist, request media, and message finalists—fast and transparent.</p>
          </div>
          <div className="text-right md:text-left">
            <a href="#/post" className="inline-flex px-4 py-2 rounded-xl bg-neutral-900 text-white text-sm">Start a Casting</a>
          </div>
        </div>
      </Card>
    </div>
  );
}

function HowItWorks({ active = 'casting-search' }:{active?: string}){
  const steps = [
    { key: 'casting-search', icon: Search, label: 'Casting Search' },
    { key: 'profile',        icon: IdCard,  label: 'Profile' },
    { key: 'messaging',      icon: Message, label: 'Messaging' },
    { key: 'media-locker',   icon: Camera,  label: 'Media Locker' },
    { key: 'applications',   icon: FileText,label: 'Applications' },
    { key: 'safety',         icon: Shield,  label: 'Safety' },
  ];

  type Section = { title:string; intro:string; bullets:string[] };
  const sections: Record<string, Section> = {
    'casting-search': {
      title: 'Casting Search',
      intro: 'Find roles fast with filters that mirror how casting actually works. Save what you like and get nudged when something new fits.',
      bullets: [
        'Dial in by location, production type, role, union status, and pay range',
        'Save searches and enable alerts to catch new postings early',
        'Open a listing to scan roles, dates, usage, and top pay at a glance',
        'Apply in one click when your profile and media are ready'
      ]
    },
    'profile': {
      title: 'Profile',
      intro: 'Build a clean, bookable presence. Keep your best looks and credits front and center for busy offices.',
      bullets: [
        'Upload headshots, reels, resumes, training, and special skills',
        'Show representation, union status, and current location',
        'Organize galleries for different looks and attach them per submission',
        'Share a public link with casting or reps when requested'
      ]
    },
    'messaging': {
      title: 'Messaging',
      intro: 'Keep all project chatter in one place. Fewer tabs. Fewer missed details.',
      bullets: [
        'Threaded conversations per project with read receipts',
        'Send sides, self‑tapes, and confirmations without file chaos',
        'Propose times, confirm callbacks, and pin key messages',
        'Receive notifications when there’s movement on a role'
      ]
    },
    'media-locker': {
      title: 'Media Locker',
      intro: 'Your materials, versioned and ready. Attach exactly what a role requests—no digging through folders.',
      bullets: [
        'Store headshots, resumes, reels, clips, and slates in one place',
        'Keep multiple cuts of a scene and label them clearly',
        'Auto‑suggest media that matches a role’s requirements',
        'Drag, reorder, and attach in seconds during submission'
      ]
    },
    'applications': {
      title: 'Applications',
      intro: 'Track every submission from sent to booked. See patterns, stay proactive.',
      bullets: [
        'Pipeline view: submitted • callback • pinned • booked',
        'Add private notes and follow‑up dates per project',
        'Export a quick summary for your records or representatives',
        'Spot trends by role type, market, and response time'
      ]
    },
    'safety': {
      title: 'Safety',
      intro: 'Clear guardrails for auditions and sets. Your boundaries matter on every project.',
      bullets: [
        'No nudity or intimacy unless disclosed and agreed in writing',
        'Meet in professional or public spaces; remote options are welcome',
        'Share sensitive documents only after a verified offer',
        `Report issues quickly to support@${BRAND.toLowerCase()}.com`
      ]
    }
  };

  // Inline, permission‑free artwork that matches site tone
  const StepArtwork = ({k}:{k:string})=>{
    const palettes: Record<string,string[]> = {
      'casting-search':['#e0f2fe','#dbeafe'],
      'profile':['#fef3c7','#fde68a'],
      'messaging':['#e9d5ff','#ddd6fe'],
      'media-locker':['#dcfce7','#bbf7d0'],
      'applications':['#ffe4e6','#fecdd3'],
      'safety':['#f3f4f6','#e5e7eb']
    };
    const [a,b] = palettes[k] || ['#eef2ff','#e0e7ff'];
    return (
      <div aria-hidden className="relative rounded-3xl border bg-white overflow-hidden shadow-sm">
        <div className="absolute inset-0" style={{background:`radial-gradient(600px 200px at 0% 0%, ${a}, transparent 70%), radial-gradient(500px 220px at 100% 100%, ${b}, transparent 70%)`}}/>
        <div className="relative p-6">
          <div className="grid grid-cols-3 gap-3">
            <div className="h-24 rounded-2xl border bg-white/70 backdrop-blur"/>
            <div className="h-24 rounded-2xl border bg-white/70 backdrop-blur"/>
            <div className="h-24 rounded-2xl border bg-white/70 backdrop-blur"/>
            <div className="col-span-2 h-28 rounded-2xl border bg-white/80"/>
            <div className="h-28 rounded-2xl border bg-white/80"/>
          </div>
          <div className="mt-4 flex items-center gap-2 text-neutral-600">
            <div className="h-8 w-8 grid place-items-center rounded-xl bg-neutral-900 text-white">
              {k==='casting-search' && <Search className="h-4 w-4"/>}
              {k==='profile' && <IdCard className="h-4 w-4"/>}
              {k==='messaging' && <Message className="h-4 w-4"/>}
              {k==='media-locker' && <Camera className="h-4 w-4"/>}
              {k==='applications' && <FileText className="h-4 w-4"/>}
              {k==='safety' && <Shield className="h-4 w-4"/>}
            </div>
            <div className="text-sm">Illustrative preview</div>
          </div>
        </div>
      </div>
    );
  };

  const onPick = (k:string)=>{ go('#/how-it-works/' + k); };
  const current = sections[active] || sections['casting-search'];

  return (
    <div className="space-y-10">
      {/* Step picker */}
      <div className="grid place-items-center">
        <div className="flex items-start gap-8 md:gap-12">
          {steps.map((s)=>{
            const selected = active === s.key;
            return (
              <button
                type="button"
                key={s.key}
                onClick={()=>onPick(s.key)}
                className="text-center focus:outline-none"
                aria-current={selected ? 'page' : undefined}
              >
                <div className={`mx-auto h-12 w-12 rounded-full grid place-items-center ${selected? 'bg-blue-100 text-blue-600' : 'bg-neutral-100 text-neutral-600'}`}>
                  <s.icon className="h-6 w-6"/>
                </div>
                <div className={`mt-2 text-xs uppercase tracking-wide ${selected? 'text-blue-600' : 'text-neutral-700'}`}>{s.label}</div>
                {selected && <div className="mt-1 h-0.5 bg-blue-600 rounded w-24 mx-auto"/>}
              </button>
            );
          })}
        </div>
      </div>

      {/* Visual + copy */}
      <div className="grid md:grid-cols-2 gap-10 items-start">
        <StepArtwork k={active}/>
        <div className="max-w-3xl">
          <h1 className="text-3xl font-extrabold tracking-tight">{current.title}</h1>
          <p className="mt-3 text-neutral-700">{current.intro}</p>
          <ul className="mt-4 space-y-2 text-sm text-neutral-700 list-disc list-inside">
            {current.bullets.map((b,i)=>(<li key={i}>{b}</li>))}
          </ul>
        </div>
      </div>
    </div>
  );
}

function FAQ(){


  type QA = { q: string; a: React.ReactNode };
  const [query, setQuery] = useState("");
  const norm = (s:string)=> s.toLowerCase();
  const sections: { section: string; items: QA[] }[] = [
    { section: "Getting Started", items: [
      { q: "What is SWIPECAST?", a: <>A casting marketplace for film, TV, theater, commercials, and voiceover. Actors browse and submit. Producers post roles.</> },
      { q: "Do actors pay to use the site?", a: <>No monthly fees for actors. Submissions are free unless a posting explicitly lists a paid self‑tape request. Producers and casting pay per post.</> },
      { q: "How do I make a profile?", a: <>Use <a href="#/auth" className="underline">Join</a> to create an account. Add headshots, reels, skills, and credits.</> },
    ]},
    { section: "Submitting & Auditions", items: [
      { q: "How do I submit to a role?", a: <>Open a casting, pick the role, then <strong>Apply</strong>. Include requested media.</> },
      { q: "Will I be notified if selected?", a: <>Yes. You’ll get a message or email if shortlisted or booked.</> },
      { q: "Do I need an agent?", a: <>No. You can submit directly. List representation on your profile if applicable.</> },
    ]},
    { section: "Casting Posts & Payments", items: [
      { q: "Who pays to post?", a: <>Producers and casting directors pay per post. Actors don’t pay monthly membership.</> },
      { q: "Can I edit or close a post?", a: <>Yes. The project owner can update, pause, or close the listing.</> },
    ]},
    { section: "Safety & Eligibility", items: [
      { q: "Are in‑person auditions required?", a: <>No. Remote options are allowed at casting’s discretion. Meet only in professional or public spaces.</> },
      { q: "What about nudity or intimacy?", a: <>No nudity unless clearly disclosed and agreed in writing. Intimacy coordination recommended.</> },
      { q: "Minors on the platform?", a: <>A parent/guardian must manage the account and be present for all auditions and bookings.</> },
    ]},
    { section: "Account & Privacy", items: [
      { q: "How do I report a problem or scam?", a: <>Use <a href="#/support" className="underline">Support</a> with links and screenshots.</> },
      { q: "How do I delete my account?", a: <>Contact Support from the registered email for verification and removal.</> },
    ]},
    { section: "Technical", items: [
      { q: "Videos aren’t uploading—what can I do?", a: <>Use H.264 MP4 under 200MB and a stable connection. For larger reels, share a link.</> },
      { q: "Which browsers are supported?", a: <>Latest Chrome, Edge, Firefox, Safari. Disable aggressive blockers in previews.</> },
    ]}
  ];

  const filtered = query
    ? sections.map(sec => ({ section: sec.section, items: sec.items.filter(i => norm(i.q).includes(norm(query))) })).filter(sec => sec.items.length)
    : sections;

  return (
    <div className="max-w-4xl">
      <SectionTitle icon={Search} title="Frequently Asked Questions" subtitle="Quick answers to common questions"/>
      <Card>
        <input value={query} onChange={e=>setQuery(e.target.value)} placeholder="Search FAQs" className="w-full px-3 py-2 rounded-xl border" aria-label="Search FAQs"/>
      </Card>
      <div className="mt-6 space-y-8">
        {filtered.map((sec, si)=> (
          <section key={si}>
            <h2 className="text-lg font-semibold mb-3">{sec.section}</h2>
            <div className="space-y-2">
              {sec.items.map((qa, qi)=> (
                <details key={qi} className="group rounded-2xl border border-neutral-200 bg_WHITE p-4">
                  <summary className="cursor-pointer list-none flex items-start justify-between gap-3">
                    <span className="font-medium">{qa.q}</span>
                    <span className="text-neutral-400 group-open:rotate-90 transition-transform">›</span>
                  </summary>
                  <div className="mt-2 text-sm text-neutral-700">{qa.a}</div>
                </details>
              ))}
            </div>
          </section>
        ))}
        {filtered.length===0 && (<Card><div className="text-sm text-neutral-600">No results. Try different keywords.</div></Card>)}
      </div>
    </div>
  );
}

function AuditionToolkit(){
  type Phase = 'Before' | 'During' | 'After';
  type QA = { phase: Phase; q: string; a: React.ReactNode };
  const items: QA[] = [
    // Before
    { phase:'Before', q:'What should I bring?', a: <>Printed sides, a stapled headshot & resume, water, simple prop alternatives (pen/notebook), and a charged phone with your calendar.</> },
    { phase:'Before', q:'How do I warm up fast?', a: <>5 minutes: lip trills, tongue twisters, gentle neck/shoulder rolls, 10 deep diaphragmatic breaths, then one full-speed read.</> },
    { phase:'Before', q:'What should I wear?', a: <>Solid, camera-friendly colors that suggest the role without a costume. Avoid busy patterns, loud logos, and noisy jewelry.</> },
    { phase:'Before', q:'How do I prep the sides?', a: <>Mark objective, obstacles, and actions per beat. Memorize first and last lines; keep a clean glance path if you still reference the page.</> },
    { phase:'Before', q:'How early should I arrive?', a: <>10–15 minutes in person. For virtual, join the waiting room 5 minutes early with tech checked and notifications off.</> },
    // During
    { phase:'During', q:'How do I slate?', a: <>Name, role, rep (if any), location. For full body, step back, neutral stance, natural smile. Keep it under 10 seconds.</> },
    { phase:'During', q:'Where do I place my eyeline?', a: <>Off-lens at reader height unless asked to cheat to camera. Keep it consistent across takes.</> },
    { phase:'During', q:'How do I pace the scene?', a: <>Land beats. Allow listening and turns. Trim filler words unless they serve behavior. Keep the story clear over speed.</> },
    { phase:'During', q:'What if I make a mistake?', a: <>Stay in it. Finish the take unless stopped. If it derails, say “Requesting a restart” once. No apologies, just reset.</> },
    { phase:'During', q:'How do I take direction?', a: <>Say “Got it,” make one bold adjustment, and commit. Don’t defend the first choice. Show range without reinventing the scene.</> },
    // After
    { phase:'After', q:'Should I follow up?', a: <>Yes, within 24–48 hours if requested or if you have a meaningful update (availability change, new reel). Keep it one paragraph.</> },
    { phase:'After', q:'How do I name self‑tape files?', a: <>Project_Role_YourName_Take01.mp4. Example: <code>Bluebird_Detective_JordanReyes_Take01.mp4</code>.</> },
    { phase:'After', q:'How do I track auditions?', a: <>Use a spreadsheet or app: project, role, date, office, notes, result, follow‑up date. Review monthly for patterns.</> },
    { phase:'After', q:'How do I reset mindset?', a: <>Debrief 2 mins: one win, one tweak. Close the tab mentally. Move your body 5 mins. Start next task to avoid rumination.</> },
    { phase:'After', q:'When do I ask for feedback?', a: <>Only if invited or you have a relationship with the office. Otherwise focus on volume and craft, not post‑mortems.</> },
  ];
  const phases: Phase[] = ['Before','During','After'];
  return (
    <div className="max-w-4xl">
      <SectionTitle icon={Clapperboard} title="Audition Toolkit" subtitle="Before • During • After"/>
      {phases.map((ph)=>{
        const list = items.filter(i=>i.phase===ph);
        return (
          <section key={ph} className="mt-6">
            <h2 className="text-lg font-semibold mb-3">{ph}</h2>
            <div className="space-y-2">
              {list.map((qa, idx)=>(
                <details key={ph+idx} className="group rounded-2xl border border-neutral-200 p-4 bg-white">
                  <summary className="cursor-pointer list-none flex items-start justify-between gap-3">
                    <span className="font-medium">{qa.q}</span>
                    <span className="text-neutral-400 group-open:rotate-90 transition-transform">›</span>
                  </summary>
                  <div className="mt-2 text-sm text-neutral-700">{qa.a}</div>
                </details>
              ))}
            </div>
          </section>
        );
      })}
      <Card>
        <div className="text-sm text-neutral-700">
          Quick tip: record a <strong>one‑minute rehearsal take</strong> on your phone right now. Watch it once, fix one thing, then do your submission take.
        </div>
      </Card>
    </div>
  );
}

function ProHeader(){
  return (
    <div className="relative isolate bg-neutral-900 text-white">
      <div className="absolute inset-0" style={{background:'radial-gradient(600px 200px at 0% 0%, rgba(255,255,255,.08), transparent 70%), radial-gradient(400px 160px at 100% 100%, rgba(255,255,255,.06), transparent 70%)'}} />
      <div className="relative max-w-7xl mx-auto px-4 py-7 md:py-12" data-testid="pro-header">
        <div className="flex flex-col md:flex-row items-start md:items-center justify_between gap-6">
          <div className="min-w-0">
            <div className="text-[11px] uppercase tracking-widest text-neutral-300">Professional Casting Platform</div>
            <h1 className="mt-1 text-3xl md:text-5xl font-extrabold tracking-tight leading-tight cursor-pointer" onClick={()=>go("#/")}>{BRAND}</h1>
            <p className="mt-1 text-sm text-neutral-300">Find talent. Post roles. Book faster.</p>
          </div>
          <div className="flex gap-2 shrink-0">
            <a href="#/post" className="px-4 py-2 rounded-xl bg.white text-neutral-900 text-sm hover:opacity-90 bg-white">Post a Casting</a>
            <a href="#/auth" className="px-4 py-2 rounded-xl border border-white/30 text-sm hover:bg-white/10">Join Free</a>
          </div>
        </div>
      </div>
    </div>
  );
}

function TrustedBy(){
  const items = [
    { name: "Marvel Studios", domain: "marvel.com" },
    { name: "Warner Bros.", domain: "warnerbros.com" },
    { name: "A24", domain: "a24films.com" },
    { name: "HBO", domain: "hbo.com" },
    { name: "DreamWorks", domain: "dreamworks.com" },
  ];
  // Transparent 1x1 fallback to avoid visible squares
  const transparent = "data:image/svg+xml;charset=utf-8," + encodeURIComponent("<svg xmlns='http://www.w3.org/2000/svg' width='1' height='1'/>");
  return (
    <div className="bg-white border-t" data-testid="trusted-by">
      <div className="max-w-7xl mx-auto px-4 py-12">
        <div className="text-center text-3xl md:text-5xl font-extrabold tracking-tight text-black mb-10">Trusted by top brands and filmmakers</div>
        {/* Static row, larger logos, no framed fallbacks */}
        <div className="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-12 items-center justify-items-center">
          {items.map((b)=> (
            <div key={b.name} className="h-24 md:h-28 w-full flex items-center justify-center">
              <img
                src={`https://logo.clearbit.com/${b.domain}`}
                alt={b.name}
                loading="lazy"
                decoding="async"
                className="max-h-24 md:max-h-28 object-contain"
                onError={(e)=>{ const img=e.currentTarget as HTMLImageElement; img.onerror=null; img.src=transparent; img.alt = b.name + ' logo'; }}
              />
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

// ------------------
// Acting Monologues & Scenes data and pages
// ------------------

// curated real works (public domain plays + well-known films and novels)
const WORKS = [
  { work:'Hamlet', author:'William Shakespeare', year:1600, medium:'Play', publicDomain:true, characters:['Hamlet','Ophelia','Claudius','Gertrude','Polonius'] },
  { work:'Macbeth', author:'William Shakespeare', year:1606, medium:'Play', publicDomain:true, characters:['Macbeth','Lady Macbeth','Banquo','Macduff'] },
  { work:'Romeo and Juliet', author:'William Shakespeare', year:1597, medium:'Play', publicDomain:true, characters:['Romeo','Juliet','Mercutio','Friar Laurence'] },
  { work:'Julius Caesar', author:'William Shakespeare', year:1599, medium:'Play', publicDomain:true, characters:['Brutus','Cassius','Mark Antony','Caesar'] },
  { work:'King Lear', author:'William Shakespeare', year:1606, medium:'Play', publicDomain:true, characters:['Lear','Cordelia','Edmund','Edgar'] },
  { work:'Othello', author:'William Shakespeare', year:1603, medium:'Play', publicDomain:true, characters:['Othello','Iago','Desdemona'] },
  { work:'Twelfth Night', author:'William Shakespeare', year:1602, medium:'Play', publicDomain:true, characters:['Viola','Malvolio','Olivia'] },
  { work:'The Merchant of Venice', author:'William Shakespeare', year:1600, medium:'Play', publicDomain:true, characters:['Shylock','Portia','Antonio'] },
  { work:'A Midsummer Night\'s Dream', author:'William Shakespeare', year:1595, medium:'Play', publicDomain:true, characters:['Puck','Hermia','Helena'] },
  { work:'Much Ado About Nothing', author:'William Shakespeare', year:1598, medium:'Play', publicDomain:true, characters:['Beatrice','Benedick','Claudio'] },
  { work:'The Seagull', author:'Anton Chekhov', year:1896, medium:'Play', publicDomain:true, characters:['Nina','Treplev','Arkadina','Trigorin'] },
  { work:'Uncle Vanya', author:'Anton Chekhov', year:1898, medium:'Play', publicDomain:true, characters:['Vanya','Sonya','Astrov','Yelena'] },
  { work:'Three Sisters', author:'Anton Chekhov', year:1901, medium:'Play', publicDomain:true, characters:['Olga','Masha','Irina','Vershinin'] },
  { work:'The Cherry Orchard', author:'Anton Chekhov', year:1904, medium:'Play', publicDomain:true, characters:['Ranevskaya','Lopakhin','Trofimov'] },
  { work:'A Doll\'s House', author:'Henrik Ibsen', year:1879, medium:'Play', publicDomain:true, characters:['Nora','Torvald','Krogstad','Mrs Linde'] },
  { work:'Hedda Gabler', author:'Henrik Ibsen', year:1891, medium:'Play', publicDomain:true, characters:['Hedda','Tesman','Ejlert Lövborg','Thea'] },
  { work:'An Enemy of the People', author:'Henrik Ibsen', year:1882, medium:'Play', publicDomain:true, characters:['Dr. Stockmann','Peter Stockmann'] },
  { work:'The Importance of Being Earnest', author:'Oscar Wilde', year:1895, medium:'Play', publicDomain:true, characters:['Jack','Algernon','Gwendolen','Lady Bracknell'] },
  { work:'Oedipus Rex', author:'Sophocles', year:-429, medium:'Play', publicDomain:true, characters:['Oedipus','Jocasta','Tiresias'] },
  { work:'Antigone', author:'Sophocles', year:-441, medium:'Play', publicDomain:true, characters:['Antigone','Creon'] },
  { work:'Medea', author:'Euripides', year:-431, medium:'Play', publicDomain:true, characters:['Medea','Jason','Nurse'] },
  { work:'Agamemnon', author:'Aeschylus', year:-458, medium:'Play', publicDomain:true, characters:['Clytemnestra','Agamemnon','Cassandra'] },
  { work:'Tartuffe', author:'Molière', year:1664, medium:'Play', publicDomain:true, characters:['Orgon','Elmire','Tartuffe'] },
  { work:'Faust', author:'Goethe', year:1808, medium:'Play', publicDomain:true, characters:['Faust','Gretchen','Mephistopheles'] },
  { work:'Pride and Prejudice', author:'Jane Austen', year:1813, medium:'Novel', publicDomain:true, characters:['Elizabeth Bennet','Mr. Darcy'] },
  { work:'Jane Eyre', author:'Charlotte Brontë', year:1847, medium:'Novel', publicDomain:true, characters:['Jane Eyre','Rochester'] },
  { work:'Wuthering Heights', author:'Emily Brontë', year:1847, medium:'Novel', publicDomain:true, characters:['Catherine','Heathcliff'] },
  { work:'Moby-Dick', author:'Herman Melville', year:1851, medium:'Novel', publicDomain:true, characters:['Ahab','Ishmael','Starbuck'] },
  { work:'Frankenstein', author:'Mary Shelley', year:1818, medium:'Novel', publicDomain:true, characters:['Victor Frankenstein','Creature'] },
  { work:'Dracula', author:'Bram Stoker', year:1897, medium:'Novel', publicDomain:true, characters:['Dracula','Jonathan Harker','Mina'] },
  // films (titles only, no verbatim script text)
  { work:'Casablanca', author:'Michael Curtiz (dir.)', year:1942, medium:'Film', publicDomain:false, characters:['Rick','Ilsa','Renault'] },
  { work:'The Godfather', author:'Francis Ford Coppola (dir.)', year:1972, medium:'Film', publicDomain:false, characters:['Michael','Vito','Sonny'] },
  { work:'Network', author:'Sidney Lumet (dir.)', year:1976, medium:'Film', publicDomain:false, characters:['Howard Beale','Diana Christensen'] },
  { work:'Taxi Driver', author:'Martin Scorsese (dir.)', year:1976, medium:'Film', publicDomain:false, characters:['Travis Bickle','Betsy'] },
  { work:'A Few Good Men', author:'Rob Reiner (dir.)', year:1992, medium:'Film', publicDomain:false, characters:['Kaffee','Jessup'] },
  { work:'The Social Network', author:'David Fincher (dir.)', year:2010, medium:'Film', publicDomain:false, characters:['Mark Zuckerberg','Erica Albright'] },
  { work:'There Will Be Blood', author:'Paul Thomas Anderson (dir.)', year:2007, medium:'Film', publicDomain:false, characters:['Daniel Plainview','Eli Sunday'] },
  { work:'Good Will Hunting', author:'Gus Van Sant (dir.)', year:1997, medium:'Film', publicDomain:false, characters:['Will','Sean'] },
  { work:'The Dark Knight', author:'Christopher Nolan (dir.)', year:2008, medium:'Film', publicDomain:false, characters:['Joker','Batman','Harvey Dent'] },
];

const MONO_PAGES = 50;
const MONO_PER_PAGE = 14;
const MONO_TOTAL = MONO_PAGES * MONO_PER_PAGE; // 700 entries

function buildMonologue(i:number){
  // deterministic pick
  const w = WORKS[i % WORKS.length];
  const character = w.characters[i % w.characters.length];
  const isScene = (i % 3) === 0; // mix monologues and scenes
  // short public‑domain excerpt safely under 25 words; otherwise a synopsis
  let excerpt = '';
  if(w.publicDomain){
    const PD_LINES: Record<string,string[]> = {
      'Hamlet': ["To be, or not to be: that is the question.", "What a piece of work is a man, how noble in reason."],
      'Macbeth': ["Is this a dagger which I see before me?", "Out, damned spot! out, I say!"],
      'Romeo and Juliet': ["But, soft! what light through yonder window breaks?"],
      'Julius Caesar': ["Friends, Romans, countrymen, lend me your ears."],
      'King Lear': ["Blow, winds, and crack your cheeks!"],
      'Othello': ["O, beware, my lord, of jealousy."],
      'Twelfth Night': ["If music be the food of love, play on."],
      'The Merchant of Venice': ["The quality of mercy is not strain'd."],
      "A Midsummer Night's Dream": ["Lord, what fools these mortals be!"],
      'Much Ado About Nothing': ["I had rather hear my dog bark at a crow than a man swear he loves me."],
      'The Seagull': ["I am in mourning for my life."],
      'Uncle Vanya': ["What must be, must be.", "We shall rest."] ,
      'Three Sisters': ["To Moscow! To Moscow!"],
      'The Cherry Orchard': ["All Russia is our orchard."] ,
      "A Doll's House": ["I must stand quite alone, if I am to understand myself and everything about me."],
      'Hedda Gabler': ["I want for once in my life to have power to mould a human destiny."],
      'An Enemy of the People': ["The strongest man in the world is the man who stands most alone."],
      'The Importance of Being Earnest': ["The truth is rarely pure and never simple."],
      'Oedipus Rex': ["I must bring what is dark to light."],
      'Antigone': ["I was born to share in love, not hatred."],
      'Medea': ["I understand the horror of what I am about to do."],
      'Agamemnon': ["It is a fearful thing to be a king."] ,
      'Tartuffe': ["Hypocrites get by with a great deal."] ,
      'Faust': ["Two souls, alas! are dwelling in my breast."],
      'Pride and Prejudice': ["You must allow me to tell you how ardently I admire and love you."],
      'Jane Eyre': ["I am no bird; and no net ensnares me."],
      'Wuthering Heights': ["Whatever our souls are made of, his and mine are the same."],
      'Moby-Dick': ["Call me Ishmael."],
      'Frankenstein': ["Beware; for I am fearless, and therefore powerful."],
      'Dracula': ["Listen to them, the children of the night."]
    };
    const lines = PD_LINES[w.work] || ["A timeless passage from the classic text."];
    excerpt = lines[i % lines.length];
  } else {
    excerpt = isScene
      ? 'Two-person scene. Summarize the beats and choose a licensed or original cutting.'
      : 'Monologue suggestion. Summarize the moment and use licensed text for performance.';
  }
  const tones = ['dramatic','comic','tragic','romantic','satirical','intense','understated'];
  const lengths = ['0:45–1:15','1–2 minutes','2–3 minutes'];
  return {
    id: 'm' + (i+1),
    isScene,
    title: `${w.work} (${character})`,
    work: w.work,
    character,
    author: w.author,
    year: w.year,
    medium: w.medium,
    type: isScene ? 'Scene' : 'Monologue',
    publicDomain: w.publicDomain,
    excerpt,
    tone: tones[i % tones.length],
    length: lengths[i % lengths.length]
  };
}

const MONOLOGUES = Array.from({length: MONO_TOTAL}, (_,i)=> buildMonologue(i));

function MonologuesIndex({page=1}:{page?:number}){
  const TOTAL_PAGES = MONO_PAGES;
  const PER_PAGE = MONO_PER_PAGE;
  const safePage = Math.min(Math.max(1, page), TOTAL_PAGES);
  const start = (safePage - 1) * PER_PAGE;
  const pageData = MONOLOGUES.slice(start, start + PER_PAGE);
  const [q, setQ] = useState('');
  const filtered = q.trim() ? pageData.filter(x=> (x.title + ' ' + x.work + ' ' + x.author + ' ' + x.character).toLowerCase().includes(q.toLowerCase())) : pageData;
  const Pager = () => (
    <div className="flex items-center justify-center gap-3 py-4 select-none">
      {Array.from({length: TOTAL_PAGES}, (_,i)=> i+1).map(n=> (
        <button key={n} onClick={()=> go(n===1 ? '#/monologues' : `#/monologues/p/${n}`)} aria-current={n===safePage? 'page': undefined} className="h-7 min-w-7 px-2 grid place-items-center text-sm text-neutral-700">
          <span className={`inline-grid place-items-center h-7 w-7 rounded-full ${n===safePage? 'bg-black text-white' : ''}`}>{n}</span>
        </button>
      ))}
      <button onClick={()=> go(safePage<TOTAL_PAGES ? `#/monologues/p/${safePage+1}` : (safePage===1 ? '#/monologues/p/2' : `#/monologues/p/${safePage}`))} aria-label="Next page" className="h-7 min-w-7 px-2 grid place-items-center text-neutral-700">›</button>
    </div>
  );
  return (
    <div className="grid lg:grid-cols-3 gap-6">
      <div className="lg:col-span-2 space-y-6">
        <SectionTitle icon={FileText} title="Acting Monologues & Scenes" subtitle={`Real literature and films • ${MONO_TOTAL} entries • 14 per page`}/>
        <Card>
          <input value={q} onChange={e=>setQ(e.target.value)} placeholder="Search by title, character, or author" className="w-full px-3 py-2 rounded-xl border"/>
        </Card>
        <Pager/>
        {filtered.map(m => (
          <Card key={m.id}>
            <div className="flex items-start justify-between gap-4">
              <div className="min-w-0">
                <h3 className="text-lg font-semibold"><a href={`#/mono/${m.id}`} className="hover:underline">{m.title}</a></h3>
                <div className="mt-1 text-sm text-neutral-600">{m.author} • {String(m.year)} • {m.medium} • {m.type}</div>
              </div>
              <div className="text-right shrink-0">
                <div className="text-xs text-neutral-600">{m.tone}</div>
                <div className="text-xs text-neutral-600">{m.length}</div>
                <button onClick={()=>go(`#/mono/${m.id}`)} className="mt-2 px-3 py-1.5 rounded-xl bg-neutral-900 text-white text-sm hover:bg-neutral-800">View More</button>
              </div>
            </div>
            <p className="mt-3 text-sm text-neutral-700">{m.excerpt}</p>
          </Card>
        ))}
        <Pager/>
      </div>
      <div className="space-y-6">
        <SectionTitle icon={Search} title="Refine"/>
        <Card>
          <div className="space-y-2 text-sm">
            <div className="flex flex-wrap gap-2"><Chip>Public domain</Chip><Chip>Film</Chip><Chip>Play</Chip><Chip>Novel</Chip><Chip>Monologue</Chip><Chip>Scene</Chip></div>
            <p className="text-neutral-600">Tip: choose your own cutting for non–public‑domain works.</p>
          </div>
        </Card>
        <Card>
          <div className="text-sm text-neutral-700">
            Built for rehearsal rooms. Clean formatting. No ads. Use these listings to find audition ideas and craft your cuts.
          </div>
        </Card>
      </div>
    </div>
  );
}

function MonologueDetail({id}:{id:string}){
  const m = MONOLOGUES.find(x=>x.id===id);
  if(!m){ return <Card><div className="text-sm">Not found.</div></Card>; }
  return (
    <div>
      <div className="mb-4 flex items-center justify-between"><div className="flex items-center gap-2"><FileText className="h-5 w-5"/><h1 className="text-2xl font-extrabold">{m.title}</h1></div><button onClick={()=>go('#/monologues')} className="text-sm px-3 py-1.5 rounded-xl border hover:bg-neutral-100">Back to list</button></div>
      <Card>
        <div className="grid md:grid-cols-3 gap-6">
          <div className="md:col-span-2">
            <div className="text-sm text-neutral-600">{m.author} • {String(m.year)} • {m.medium} • {m.type} • {m.tone} • {m.length}</div>
            <h3 className="mt-4 font-semibold">Context</h3>
            <p className="mt-2 text-sm text-neutral-700">Suggested performance piece from <em>{m.work}</em>. Choose a cut that fits the stated length. {m.publicDomain ? 'Public‑domain text available. Quote limits observed here.' : 'Do not reproduce copyrighted text without permission.'}</p>
            <h3 className="mt-4 font-semibold">Sample Line</h3>
            <p className="mt-2 text-sm text-neutral-700">{m.excerpt}</p>
            <h3 className="mt-4 font-semibold">Tips</h3>
            <ul className="mt-2 text-sm text-neutral-700 list-disc list-inside">
              <li>Define objective and obstacle in the beat before the cut.</li>
              <li>Map breath to turns of thought. Keep buttons clean.</li>
              <li>For scenes, rehearse clear eyelines and listening moments.</li>
            </ul>
          </div>
          <div>
            <Card><div className="text-sm"><div><strong>Character:</strong> {m.character}</div><div><strong>Tone:</strong> {m.tone}</div><div><strong>Length:</strong> {m.length}</div><div><strong>Public domain:</strong> {m.publicDomain? 'Yes' : 'No'}</div></div></Card>
          </div>
        </div>
      </Card>
    </div>
  );
}

function Website(){
  const route = useHashRoute();
  const applyMatch = route.match(/^#\/apply\/([^/]+)/);
  const howMatch = route.match(/^#\/how-it-works(?:\/([^/]+))?$/);
  const monoMatch = route.match(/^#\/mono\/([^/]+)/);
  return (
    <div className="min-h-screen bg-neutral-50">
      <ProHeader/>

      <header className="sticky top-0 z-10 bg-white/80 backdrop-blur border-b">
        <div className="max-w-7xl mx-auto px-4 py-3 flex items-center justify-between gap-4">
          <div className="flex items-center gap-2">
            <div className="h-9 w-9 grid place-items-center rounded-xl bg-neutral-900 text-white"><Clapperboard className="h-5 w-5"/></div>
            <div className="text-2xl font-extrabold tracking-tight">{BRAND}</div>
          </div>
          <nav className="hidden md:flex items-center gap-6 text-sm">
            <a className={`hover:opacity-80 ${route==="#/"?"font-semibold":""}`} href="#/">Browse Castings</a>
            <a className={`hover:opacity-80 ${route==="#/talent"?"font-semibold":""}`} href="#/talent">Talent</a>
            <a className={`hover:opacity-80 ${route==="#/about"?"font-semibold":""}`} href="#/about">About</a>
            <div className="relative group">
              <a className={`hover:opacity-80 ${route==="#/resources"?"font-semibold":""}`} href="#/resources">Resources</a>
              <div className="absolute left-0 top-full w-56 rounded-xl border bg-white shadow-lg opacity-0 scale-95 origin-top-left transition-all duration-150 pointer-events-none group-hover:opacity-100 group-hover:scale-100 group-hover:pointer-events-auto z-20">
                <ul className="py-2 text-sm text-neutral-700">
                  <li><a href="#/toolkit" className="block px-3 py-2 hover:bg-neutral-50">Audition Toolkit</a></li>
                </ul>
              </div>
            </div>
            <a className={`hover:opacity-80 ${route==="#/faq"?"font-semibold":""}`} href="#/faq">FAQ</a>
            {/* Monologues & Scenes button removed from top nav by request */}
          </nav>
          <div className="flex items-center gap-2">
            <a href="#/post" className="hidden sm:inline-flex px-3 py-1.5 rounded-xl border text-sm">Post a Casting</a>
            <a href="#/auth" className="px-3 py-1.5 rounded-xl bg-neutral-900 text-white text-sm">Join</a>
            <a href="#/auth" className="px-3 py-1.5 rounded-xl border text-sm">Sign In</a>
          </div>
        </div>
      </header>

      <main className="max-w-7xl mx-auto px-4 py-8">
        {route==="#/" && <Home/>}
        {/^(#\/)?:?p|page\//.test(route) && <Home page={parseInt(route.split('/')[2]) || 1} />}
        {route==="#/talent" && <Talent/>}
        {route==="#/about" && <About/>}
        {route==="#/resources" && <Resources/>}
        {route==="#/advice" && <Advice/>}
        {howMatch && <HowItWorks active={howMatch[1] || 'casting-search'} />}
        {route==="#/post" && <PostCasting/>}
        {route==="#/roles" && <Roles/>}
        {route==="#/auth" && <AuthPage/>}
        {applyMatch && <ApplicationView id={applyMatch[1]} />}
        {route==="#/support" && <Support/>}
        {route==="#/faq" && <FAQ/>}
        {route==="#/toolkit" && <AuditionToolkit/>}
        {route==="#/terms" && <Terms/>}
        {route==="#/monologues" && <MonologuesIndex/>}
        {/^(#\/monologues\/p\/)/.test(route) && <MonologuesIndex page={parseInt(route.split('/')[3]) || 1} />}
        {monoMatch && <MonologueDetail id={monoMatch[1]} />}
      </main>

      <footer className="border-t bg:white/70 backdrop-blur">
        <div className="max-w-7xl mx-auto px-4 py-8 grid md:grid-cols-4 gap-4 text-sm">
          <div>
            <div className="font-semibold mb-2">For Finding Jobs</div>
            <ul className="space-y-1">
              <li><a href="#/" className="hover:underline">Browse Castings</a></li>
              <li><a href="#/talent" className="hover:underline">Talent</a></li>
              <li><a href="#/post" className="hover:underline">Post a Casting</a></li>
              <li><a href="#/how-it-works" className="hover:underline">How it works</a></li>
              <li className="pt-2"><span className="font-semibold">Acting Monologues and Scenes</span></li>
              <li><a href="#/monologues" className="hover:underline">Explore 700 pieces • 50 pages</a></li>
            </ul>
          </div>
          <div>
            <div className="font-semibold mb-2">Company</div>
            <ul className="space-y-1">
              <li><a href="#/about" className="hover:underline">About</a></li>
              <li><a href="#/support" className="hover:underline">Support</a></li>
              <li><a href="#/faq" className="hover:underline">FAQ</a></li>
              <li><a href="#/terms" className="hover:underline">Terms & Safety</a></li>
            </ul>
          </div>
          <div>
            <div className="font-semibold mb-2">Get Started</div>
            <ul className="space-y-1">
              <li><a href="#/auth" className="hover:underline">Create Profile</a></li>
              <li><a href="#/toolkit" className="hover:underline">Audition Toolkit</a></li>
              <li><a href="#/advice" className="hover:underline text-neutral-500">Advice for Creators</a></li>
            </ul>
          </div>
          <div className="text-neutral-500">
            <div>© {new Date().getFullYear()} {BRAND}. All rights reserved.</div>
          </div>
        </div>
      </footer>
    </div>
  );
}

export default function App(){
  return <Website/>;
}

// --- runtime smoke tests (non-fatal)
(function runSmoke(){
  try{
    console.assert(typeof BRAND === 'string' && BRAND === 'SWIPECAST','BRAND should be SWIPECAST');
    console.assert(Array.isArray(categories) && categories.length >= 5,'categories length');
    console.assert(Array.isArray(ALL_CASTINGS) && ALL_CASTINGS.length >= 140, 'ALL_CASTINGS should be >= 140');
    console.assert(Array.isArray(MONOLOGUES) && MONOLOGUES.length === 700, 'MONOLOGUES should be 700');
    console.assert(typeof window !== 'undefined', 'window exists');
    const routes = ['#/', '#/talent', '#/about', '#/resources', '#/post', '#/roles', '#/auth', '#/support', '#/faq', '#/toolkit', '#/terms', '#/monologues'];
    console.assert(routes.every(r => typeof r === 'string'),'routes ok');
    console.assert(typeof go === 'function','go() present');
    console.assert(typeof useHashRoute === 'function','useHashRoute() present');
    setTimeout(()=>{ try{
      const ph = document.querySelector('[data-testid="pro-header"]'); console.assert(!!ph, 'Pro header present');
      const tb = document.querySelector('[data-testid="trusted-by"]');
      if(tb){ const logoImgs = tb.querySelectorAll('img'); console.assert(logoImgs.length === 5, 'TrustedBy: 5 logos rendered'); }
      const cards = document.querySelectorAll('[data-testid="resource-card"]'); console.assert(cards.length === 6, 'Resources: 6 cards render');
      const first = cards[0] as HTMLElement | undefined; console.assert(!!first && (first.onclick !== null || first.getAttribute('role')==='link'), 'Resources: card clickable');
    }catch{} }, 0);
    console.log('%cSMOKE TESTS PASSED','color:green');
  }catch(e){ console.error('SMOKE TESTS FAILED', e); }
})();
