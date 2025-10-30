# Guida Pratica – Come Riconoscere gli Errori nelle Clip Valorant

**Versione**: 1.0  
**Data**: 30/10/2025  
**Pubblico**: Chiunque voglia imparare a identificare errori tattici guardando clip  
**Durata lettura**: 20–30 minuti

---

## Indice

1. [Introduzione](#introduzione)
2. [Cosa Cercare in Una Clip](#cosa-cercare-in-una-clip)
3. [Errori di Posizionamento](#errori-di-posizionamento)
4. [Errori di Utility](#errori-di-utility)
5. [Errori di Economia](#errori-di-economia)
6. [Errori di Gunplay/Aim](#errori-di-gunplayaim)
7. [Errori di Decision Making](#errori-di-decision-making)
8. [Metodologia di Analisi](#metodologia-di-analisi)
9. [Checklist Rapida](#checklist-rapida)

---

## Introduzione

Gli errori nel gameplay Valorant si dividono in **due categorie**: **tattici** (decisioni sbagliate) e **meccanici** (esecuzione sbagliata). Una clip di 30–60 secondi contiene di solito **3–5 errori identificabili**.

**Tuo compito**: Imparare a riconoscerli guardando il video, fermandoti ai frame chiave e annotando cosa è andato storto.

---

## Cosa Cercare in Una Clip

### Step 1: Identifica il Contesto

Prima di cercare errori, rispondi:

- **Che round è?** (pistol, anti-eco, bonus, half buy, full buy?)
- **Che agenti sono in gioco?** (defender positions, utility disponibili?)
- **Qual è l'obiettivo?** (execute A-site, default hold, retake?)
- **Chi ha vinto?** (round outcome?)

**Esempio clip 1**:
```
Contesto:
- Round: Full buy (round 5+)
- Agenti: Jett (entry), Omen (smoke), Gekko (flash), Sage (support), Cypher (anchor)
- Obiettivo: Execute A-site Haven
- Outcome: Loss (plant bloccato)
```

### Step 2: Dividi la Clip in Fasi

Ogni round ha 4 fasi:

1. **Entry Phase (0–10s post-round)**: Attaccanti muovono e ottengono info / Difensori posizionano
2. **Mid Execute (10–20s)**: Stack utility, entry duelist, entry supporto
3. **Post-Plant (20–40s)**: Plant position, hold site, retake preparation
4. **Retake/Defense (40s+)**: Se plant planted, retake sequence / Se non piantato, pressione difensiva

**Ogni fase ha errori specifici da cercare** (vedi sezioni sotto).

---

## Errori di Posizionamento

### Errore 1: Crosshair Misplaced (Non Head-Level)

**Cosa è**: Crosshair non posizionato a livello della testa prima di peek.

**Perché è errore**: TTK (time-to-kill) aumenta drasticamente se devi aggiustare mira verticalmente. Primo colpo conta.

**Come riconoscerlo nella clip**:
1. Guarda il **crosshair** (punto centrale schermo).
2. Osserva **prima del peek**: il crosshair è al livello della testa dell'agente (o nemico previsto)?
3. Se il crosshair è **basso** (torso, gambe), è errore.

**Visual Check**:
```
❌ SBAGLIATO:
[Schermo mostra Jett che fa peek]
Crosshair è al livello del torso/ginocchia
Jett vede nemico e must aim UP per headshot
→ Extra 100ms di tempo = extra tempo nemico sparare

✅ GIUSTO:
[Schermo mostra Jett che fa peek]
Crosshair è già head-level
Jett vede nemico e ha instant headshot ready
→ 0ms extra tempo = TTK advantage
```

**Timestamp nella clip**: Guarda i **10–15 secondi prima di engagement** (pre-aim practice).

**Severity**: Medium (se uno-off event), Low (se abitudinario).

---

### Errore 2: Overpeek No Backup (Wide Peek Solo)

**Cosa è**: Agente fa peek con angolo ampio (45°+) senza ally nearby per trade-frag.

**Perché è errore**: Enemy ha 1–2 agenti entro eyeline → se tu muori, nessuno trade-kills nemico. Deficit numerico guaranteed.

**Come riconoscerlo nella clip**:

1. **Posiziona mentale gli agenti** (guarda minimap o posizioni tattiche).
2. Cerca **solo agente che fa peek** su angolo largo (es. Jett esce da corner con 45°+ sichtline).
3. Chiedi: **"C'è ally entro 5m che possa fare trade-frag istantaneo?"**
4. Se risposta è **NO** → Overpeek no backup (errore).

**Timing nella clip**: Cerca durante **entry phase (5–12 secondi)**.

**Visual Check**:
```
❌ SBAGLIATO:
[Minimap: Jett peeking A main wide angle]
[Nearby agenti]: nessuno entro 5m
[Outcome]: Jett presa, nessuno retaliation → 4v5

✅ GIUSTO (trade setup):
[Minimap: Jett peeking, Phoenix 3m behind]
[Timing]: Jett muore, Phoenix immediate counter-peek
[Outcome]: 1v1 trade → 4v4 (economia preserved)
```

**Severity**: High (causa mid-round deficit numerico).

---

### Errore 3: Predictable Lurk (Stessa Posizione Ogni Round)

**Cosa è**: Lurker usa la stessa off-map posizione ogni round, diventando prevedibile.

**Perché è errore**: Enemy può pre-pick, preparare utility counter, o ignorare completamente (no pressure).

**Come riconoscerlo nella clip**:

1. Guarda se è **lurk clip** (agente solo in area off-site, non in default stack).
2. Nota la **posizione esatta** (es. "Reyna lurk A Garage behind boxes").
3. Se è parte di una **series di round** (multi-clip), verifica: **"Lurker era nello stesso posto round precedente?"**
4. Se SÌ → Predictable lurk (errore).

**Nota**: Una singola clip di 30s non mostra prevedibilità. Errore si nota meglio su **multi-round VOD**.

**Severity**: Medium (tattica, non micro).

---

## Errori di Utility

### Errore 4: Utility Spam Early (Preventivamente)

**Cosa è**: Abilità cast lanciata troppo presto (0–5 secondi) senza timing coordinato con entry.

**Perché è errore**: 
- Smoke lanciato ora, entry fra 8 secondi → smoke scade prima entry (defender peek free).
- Ulti cooldown spreco → non disponibile quando serve per execute.

**Come riconoscerlo nella clip**:

1. Osserva **quando viene lanciata la prima utility** (smoke, molly, stun).
2. Conta **quanti secondi dopo** arriva l'entry duelist.
3. Regola di thumb:
   - Smoke dura ~15s
   - Entry dovrebbe arrivare **entro 2s dal cast** (massimo 5s)
   - Se entry arriva **dopo 8s+** dalla smoke → errore

**Visual Check**:
```
❌ SBAGLIATO:
Timeline:
0:00s - Omen cast smoke A main
0:05s - Niente happening (smoke settling)
0:10s - Jett entry (smoke almost expired)
0:12s - Jett peeked in da smoke scaduta
→ Jett accecata, no advantage

✅ GIUSTO:
Timeline:
0:00s - Omen cast smoke
0:02s - Jett dash entry immediately after smoke settle
0:03s - Jett picking defender angle
→ Jett has full smoke duration
```

**Timestamp nella clip**: Guarda i **primi 5–10 secondi post-round**.

**Severity**: Medium (utility wasted, ma no catastrophic fail).

---

### Errore 5: Utility Not Synced (Desincronizzato)

**Cosa è**: Sequenza utility lanciata non sincronizzata con timing entry duelist. Esempio: smoke lanciato DOPO che entry duelist è già entrato.

**Perché è errore**: Duelist entry accecato o senza coverage utility. Retake facile per defender.

**Come riconoscerlo nella clip**:

1. Identifica **quando entry duelist entra** (es. Jett dash entra in A main).
2. Identifica **quando smoke cast** (animazione controller).
3. **Timing check**:
   - Se smoke lanciato **prima entry di 1–3s** → Correct (smoke settles, entry ready).
   - Se smoke lanciato **durante entry (0s delta)** → Borderline (ok).
   - Se smoke lanciato **dopo entry di 1s+** → ERRORE (duelist exposed).

**Visual Check**:
```
❌ SBAGLIATO:
0:00s - Omen prepara smoke (animation start)
0:01s - Jett DASH entry (già dentro smoke area)
0:02s - Smoke particles appear (TOO LATE)
→ Jett peek in scoperto 1-2s, defender shoot

✅ GIUSTO:
0:00s - Omen smoke lanciato
0:01s - Smoke particles start settling
0:02s - Jett dash entry (in fumo, safe)
→ Jett covered
```

**Timestamp nella clip**: **5–15 secondi** (entry phase).

**Severity**: High (entry compromised).

---

### Errore 6: No Lurk Denial (Trapwire/Slow Missing)

**Cosa è**: Default setup (difesa) non ha trapwire, slow, wall, o altra utility di lurk-denial in lurk path.

**Perché è errore**: Lurker attacker avanza libero, sorprende defender da dietro, causa mid-round collapse.

**Come riconoscerlo nella clip**:

1. Identifica **lurk path attacker** (es. A Main lurk path → Garage → A site).
2. Chiedi: **"C'è trapwire, slow orb, wall, alarm, o otra utility in quel path?"**
3. Se NO → Errore.

**Problema**: Clip **difesa perspective** non mostra sempre lurk. Bisogna **inferire da outcome**:
- Se attacker lurker arrive senza warning → No lurk denial.
- Se defender muore da flanker surprise → Possibile lurk denial miss.

**Visual Check**:
```
❌ SBAGLIATO (Defender perspective):
- Nessun Cypher trapwire in A main deep lurk path
- Nessun Sage slow in A Garage
- Attacker lurker arrive from nowhere
- Defender blindsided 4v5 → collapse

✅ GIUSTO (Defender perspective):
- Cypher trapwire deep A main
- Attacker lurker trigger trapwire → stun, reveal
- Defender can rotate, prepare trade
```

**Timestamp nella clip**: **3–15 secondi** (default phase).

**Severity**: High (lurk pressure unchecked).

---

## Errori di Economia

### Errore 7: Force Buy Failed

**Cosa è**: Force buy round (crediti 1500–2200) tentato senza sufficient utility per sopravvivenza. Round perso, economia deficit seguente.

**Perché è errore**: Force buy è **high-risk high-reward**. Se fallisce, economia next round è compromessa (2 round save richiesti).

**Come riconoscerlo nella clip**:

1. **Guarda il buy round** (schermo hud: "Bonus" o crediti 1500–2200).
2. Verifica: **"Hanno armatura? Hanno utility?"**
3. Se buy è **gun only** (no armor, no util) → Ultra-risky.
4. Se round è **perso** (spike mancato/plant bloccato) e outcome **0–1 kill**: Errore confermato.

**Economia context**:
```
❌ SBAGLIATO:
Round 3: Loss, rimango 1900 crediti
Round 4 (Force): Buy Vandal + light armor, no utility
→ Perdo round 4 (0 kill)
Round 5: Rimango 600 crediti
→ Forced eco/save, deficit 2 round

✅ GIUSTO:
Round 3: Loss, rimango 1900 crediti
Round 4 (Save): 0 buy (preserve crediti)
Round 5 (Full buy): 5000+ crediti
→ Guaranteed round win
```

**Timestamp nella clip**: Generalmente non visibile in singola clip (multi-round context richiesto).

**Severity**: High (economia damage).

---

### Errore 8: Economy Break

**Cosa è**: Sequenza economia rotta: jump diretta a full buy senza proper save round, lasciando deficit.

**Perché è errore**: Economia è **long-term strategy** (3–5 round window). Un break compromette intera economy planning.

**Come riconoscerlo nella clip**:

1. Richiede **multi-round contesto** (non singola clip).
2. Pattern: "Round perso, half-buy round dopo, poi full buy subito → no 2-round save possibility."
3. Se outcome: "Lost round 6, tentato force round 7, perso nuovamente, round 8 eco" → Break confermato.

**Severity**: High (strategic error).

---

## Errori di Gunplay/Aim

### Errore 9: Wrong Weapon Distance

**Cosa è**: Arma scelta non ottimale per distanza engagement. Esempio: Phantom spray a 40m (ideal range Vandal).

**Perché è errore**: TTK aumenta drasticamente. Phantom spray a 40m ha bullet spread massimo, Vandal headshotable.

**Come riconoscerlo nella clip**:

1. Identifica **distanza engagement** (guarda le posizioni on-screen).
   - **0–8m**: Punto-blank (Phantom, Spectre ideale).
   - **8–20m**: Medio (Phantom best, Vandal ok).
   - **20–40m**: Lungo (Vandal best, Phantom weak).
   - **40m+**: Sniper range (Operator, Vandal only).

2. Identifica **arma usata** (guarda weapon model, HUD ammmo count).

3. **Match check**:
   - Se Phantom usato a **40m** → Errore (TTK too high).
   - Se Vandal usato a **5m** → Sub-optimal (Phantom è faster).

**Visual Check**:
```
❌ SBAGLIATO:
Distance: ~45m (lungo range)
Agente hold Phantom
Enemy appears at range
Agente spray Phantom, bullet spread huge
TTK ~250ms (wasted)

✅ GIUSTO:
Distance: ~45m
Agente hold Vandal (o Operator)
Enemy appears
Agente tap Vandal, 1–2 tap headshot
TTK ~150ms
```

**Timestamp nella clip**: **Ingaggio fase** (quando avviene shooting).

**Severity**: Medium (arma sub-optimal, ma non catastrophe se aim buona).

---

### Errore 10: Recoil Uncontrolled

**Cosa è**: Spray pattern erratico, colpi sparsi senza controllo recoil. Esempio: upward drift non compensato (Vandal spray).

**Perché è errore**: Accuracy cala, hit accuracy bassa, bullets miss.

**Come riconoscerlo nella clip**:

1. Osserva **spray pattern on-screen** (se visibile, alcuni clip mostrano bullet tracers).
2. Guarda **distanza tra colpi** (se irregolare, recoil uncontrolled).
3. Check **headshot vs body hit ratio** (se molti body hit, possibile recoil issue).

**Challenge**: Non sempre visibile in clip (tracers dipendono da impostazioni video).

**Visual Check**:
```
❌ SBAGLIATO:
[Vandal spray footage]
First 2 bullets: down (correct)
Bullet 3–5: spread laterale random
Bullet 6+: spray upward uncorrected
→ Agente muore, pochi hit registrati

✅ GIUSTO:
[Vandal spray footage]
Bullets 1–5: downward pattern (corrected)
Bullets 6–10: right drift compensato
→ Agente eliminate nemico
```

**Severity**: Medium (mechanical skill, not tactical).

---

## Errori di Decision Making

### Errore 11: No Info Entry (Blind Entry)

**Cosa è**: Duelist entry senza recon/flash info gathering PRIMA dell'engaggiamento. Entra accecato.

**Perché è errore**: Senza info, entry è 50-50 guess. Enemy potrebbe essere in 5 posizioni diverse. TTK advantage nemico.

**Come riconoscerlo nella clip**:

1. Cerca **recon utility PRE-ENTRY** (Paranoia, Dizzy, Trailblazer, Skye recon, etc).
2. Timeline check:
   - Se recon lanciato **2–3s PRIMA entry** → Correct.
   - Se entry lanciato **SENZA recon** → ERRORE.

**Visual Check**:
```
❌ SBAGLIATO:
Timeline:
0:00s - Jett dash entry immediate (no recon cast)
0:02s - Jett peek in blind
0:03s - Jett caught unaware (enemy in unexpected spot)
→ Jett die, entry fail

✅ GIUSTO:
Timeline:
0:00s - Gekko dizzy drone recon A main
0:02s - Dizzy report: no defender in main
0:03s - Jett dash entry (information confident)
0:05s - Jett pick defender from alternate angle
→ Entry secure
```

**Timestamp nella clip**: **3–8 secondi pre-entry** (recon window).

**Severity**: High (entry blind = 50-50).

---

### Errore 12: Retake Timing Late (Plant Defense Fail)

**Cosa è**: Retake utility sequenza lanciata DOPO che defuse ha inziato (post 11 secondi da plant). Utility sprecata.

**Perché è errore**: Defuse dura 40 secondi da plant. Se defuse attivo (>11s), retake utility non ferma defuse, solo trade setup → lose spike.

**Come riconoscerlo nella clip**:

1. Identifica **plant timestamp** (guarda spike plant animation).
2. Conta **8–11 secondi dopo** (defuse start window).
3. Osserva **quando retake utility lanciato**:
   - Se lanciato **8–10s post-plant** → Correct (pre-defuse start).
   - Se lanciato **12s+ post-plant** → ERRORE (defuse attivo).

**Visual Check**:
```
❌ SBAGLIATO:
0:00s - Spike planted
0:11s - Defuse start (attacker premono F)
0:13s - Retake smoke lanciato (TOO LATE)
0:15s - Defuse @50% still going
→ Retake smoke inutile, lose spike

✅ GIUSTO:
0:00s - Spike planted
0:09s - Retake slow lanciato (PRE-DEFUSE)
0:11s - Defuse start (attacker on slow, movement -50%)
0:13s - Team entry, trade frag
0:15s - Spike salvato
```

**Timestamp nella clip**: **Post-plant phase** (8–15 secondi dopo plant).

**Severity**: Critical (lose round).

---

### Errore 13: 1v5 Solo Entry (Clutch Bad Setup)

**Cosa è**: Scenario 1v5 (4 teammate down), agente solo entra senza utility stall/setup, muore immediate.

**Perché è errore**: 1v5 is already losing. Bisogna stall massimamente (utility-based) per chance. Entry diretto = instant death.

**Come riconoscerlo nella clip**:

1. Verifica **agenti alive count** (HUD mostra number teammate alive).
2. Se numero è **1 team vs 5 enemy** → Clutch scenario.
3. Osserva: **"Entry è cauto (utility-based stall) o aggressivo (immediate death)?"**
4. Se aggressivo senza setup → Errore.

**Visual Check**:
```
❌ SBAGLIATO (1v5):
Agente solo (4 down)
Immediate push in (no utility)
Enemy 5-man camp
Solo die in 0.5s
→ Loss

✅ GIUSTO (1v5):
Agente solo
Setup utility stall (slow, wall, smoke)
Delay enemy 5–10s
Meanwhile: hope teammate reconnect? (unlikely, ma tactic)
Or: Take 1–2 enemy down (deny eco value)
→ Acceptable clutch attempt
```

**Severity**: Medium (clutch is low-probability anyway).

---

### Errore 14: Silent Round (No Comms)

**Cosa è**: Round senza callout/comunicazione vocale dal team.

**Perché è errore**: Comms sono **multiplier** per IA tattica. Silent round = guesswork.

**Come riconoscerlo nella clip**:

1. **Ascolta audio** (se presente).
2. Se **20+ secondi** passano senza nessun voice callout → Errore.

**Challenge**: Clip spesso **mute per copyright** (Twitch/YT mute music). Difficile verificare.

**Severity**: Low (dipende from game sense, ma bad habit).

---

## Metodologia di Analisi

### Come Analizzare Una Clip Step-by-Step

#### Step 1: Guarda la Clip Senza Pausa (Full Pass)

Prima di cercare errori, **guarda la clip intera una volta** senza fermarsi. Così capisci il flusso generale e il contesto round.

**Cosa nota**:
- Agenti giocati
- Outcome (win/loss)
- Fase più interessante

---

#### Step 2: Riavvolgi e Pausa Chiave-Moment

Identifica **3–5 momenti chiave**:
1. **Entry phase (5s)**
2. **Mid execute (10s)**
3. **Ability cast moment (7s)**
4. **Engaggiamento principale (15s)**
5. **Outcome moment (20s)**

Per ogni momento, pausa e osserva.

---

#### Step 3: Analizza Per Categoria (Use Checklist Below)

Usa checklist sotto e verifica ogni categoria:
- Positioning? ✓ o ✗
- Utility timing? ✓ o ✗
- Decision making? ✓ o ✗
- Etc.

---

#### Step 4: Annota Errori Con Timestamp

Per ogni errore rilevato, annota:
```
[Timestamp] ERRORE_TIPO: Descrizione breve
Evidence: Cosa hai visto
Fix: 1-riga solution
```

**Esempio**:
```
[0:08] utility_not_synced: Smoke lanciato 1s dopo entry
Evidence: Omen smoke animation start @0:09, Jett entry @0:08 (accecata)
Fix: Stagger smoke -2s prima entry

[0:15] overpeek_no_backup: Jett wide peek senza ally nearby
Evidence: Jett 45° corner, nessun ally <5m
Fix: Position ally trade-frag 3m behind
```

---

#### Step 5: Prioritizza Errori by Severity

Sort lista per **severity** (critical, high, medium, low).

Focus su **critical + high** (rest sono minor).

---

### Timing Nella Clip

**Sapere dove cercare errori per fase**:

| Fase | Durata | Errori Comuni | Timestamp |
|------|--------|---------------|-----------|
| **Entry** | 0–10s | No info, utility spam, overpeek | 3–8s |
| **Mid Execute** | 10–20s | Utility desync, wrong positioning | 10–15s |
| **Post-Plant** | 20–40s | Wrong plant position, no retake prep | 20–30s |
| **Retake** | 40s+ | Late retake timing, utility wrong sequence | 42–50s |

---

## Checklist Rapida

### POSITIONING CHECKLIST

- [ ] **Crosshair head-level pre-peek?** (Guarda 1s prima engaging)
- [ ] **Trade setup presente?** (Ally <5m per backup?)
- [ ] **Off-angle hold?** (O predicibile corner?)
- [ ] **Peek type appropriate?** (Wide/tight/jiggle match scenario?)

### UTILITY CHECKLIST

- [ ] **Recon lanciato pre-entry?** (Minimum 1–2s before)
- [ ] **Smoke timing synced?** (Entry entro 2–5s da smoke cast)
- [ ] **Utility layering?** (2+ abilità stack o single?)
- [ ] **Lurk denial presente?** (Trapwire/slow in lurk path?)

### ECONOMY CHECKLIST

- [ ] **Buy aligned con round?** (Pistol/anti-eco/bonus/full?)
- [ ] **3-round plan visible?** (Economia flow planned?)
- [ ] **Force buy justified?** (Ok se probabilità >50%)

### GUNPLAY CHECKLIST

- [ ] **Arma match distanza?** (Phantom <30m? Vandal >20m?)
- [ ] **Spray controlled?** (Recoil pattern straight o wild?)
- [ ] **TTK reasonable?** (Engagement won/lost based on mechanics?)

### DECISION MAKING CHECKLIST

- [ ] **Info gathering?** (Pre-entry recon done?)
- [ ] **Timing decision?** (30s mid, 45s execute, 60s retake?)
- [ ] **Retake timing?** (Utility pre-defuse start?)
- [ ] **Comms active?** (Voice callout heard?)

---

## Analisi Rapida: 2-Minuto Method

Se vuoi analisi veloce (non in depth), usa questo:

1. **Guarda clip** (10s full pass)
2. **Rewind a momento critico** (5s)
3. **Chiedi 3 domande**:
   - "C'era info gathering?" (No → no_info_entry error)
   - "Utility era syncato?" (No → utility_not_synced error)
   - "Outcome era expected?" (No → decision_making error)
4. **Annota 1–3 errori principali**
5. **Done** (30s total)

---

## Riconoscimento Errori: Livelli di Profondità

### Level 1: BASIC (Errori Ovvi)

- Entry fail (defender picked first, entry dead)
- Plant difeso (spike spike defused)
- Economy collapse (0 crediti round)

**Tempo analisi**: 20 secondi

---

### Level 2: INTERMEDIATE (Errori Tattici)

- Utility desincronizzato (smoke settle post-entry)
- Overpeek no backup (wide angle solo)
- No info entry (entry accecato)

**Tempo analisi**: 1–2 minuti

---

### Level 3: ADVANCED (Micro-Tattica)

- Crosshair placement off-angle
- Lurk denial missing (specifico path)
- Economy 3-round break (multi-round context)

**Tempo analisi**: 3–5 minuti (multi-clip richiesto)

---

## Pratica: Esempio Completo Walkthrough

### Clip Esempio: Haven A-site Execute (45 secondi)

**Context**:
- Round: Full buy (round 8)
- Agenti: Jett (entry), Omen (smoke), Gekko (flash), Sage (support), Cypher (anchor)
- Obiettivo: Execute A-site
- Outcome: Loss (plant bloccato early)

**Analysis Walkthrough**:

**0:00–2s (Round Start)**
- Guarda: Team posizionamento default?
- Check: Cypher posizionato lurk denial? → Sì, trapwire deep A main ✓

**3–5s (Recon Phase)**
- Guarda: Gekko dizzy lanciato?
- Risultato: No dizzy cast visible ✗
- **Errore #1**: no_info_entry (high severity)
  - Evidence: Entry (Jett) avviene senza recon drone
  - Fix: Lanciare dizzy 2s pre-entry

**5–8s (Smoke Phase)**
- Guarda: Omen smoke cast tempo?
- Risultato: Smoke lanciato @5s
- Entry timing: Jett entra @7s (2s delta, ok) ✓

**8–12s (Entry)**
- Guarda: Jett entry wide/tight?
- Risultato: Jett peek wide corner, nessun ally nearby ✗
- **Errore #2**: overpeek_no_backup (high severity)
  - Evidence: Jett wide peek @10s, nessun ally <5m (Phoenix 8m away)
  - Fix: Position Phoenix 3–5m behind per trade setup

**12–20s (Site Control)**
- Guarda: Defender counter-push?
- Risultato: Defender counter-push A main, Jett presa (no trade)
- **Errore #3**: no_trade_setup (consequence di errore #2)

**20–30s (Plant Attempt)**
- Guarda: Plant position?
- Risultato: Plant in scoperto (no utility cover)
- **Errore #4**: wrong_plant_position (medium)
  - Evidence: Plant in open, not behind utility
  - Fix: Plant dietro box/wall, utility coverage

**30–35s (Plant Defense)**
- Guarda: Retake preparation?
- Risultato: No utility lanciato per plant defense
- **Errore #5**: no_retake_prep (high)
  - Evidence: Post-plant, nessuno utility hold, defender push libero
  - Fix: Reserve utility pre-plant, hold wall/smoke

**35–45s (Defuse Start)**
- Guarda: Retake attempt?
- Risultato: Late retake @40s (defuse @35s already active)
- **Errore #6**: retake_timing_late (critical)
  - Evidence: Retake utility lanciato @40s, defuse @35s already ticking
  - Fix: Lanciare utility @30–32s post-plant (PRE-defuse)

**Analysis Summary**:
```
Total Errors: 6
- Critical: 1 (retake_timing_late)
- High: 3 (no_info_entry, overpeek_no_backup, no_retake_prep)
- Medium: 2 (wrong_plant_position, no_trade_setup)

Top Issues:
1. Retake timing (critical) – plant not defended properly
2. Entry setup (high) – no recon, no trade backup
3. Plant position (medium) – utility exposed

Main Fix: Coordinate entry (recon + trade setup) + reserve utility post-plant
```

---

## Errori Comuni: Cheat Sheet

### "Perché" un Errore è Errore

| Errore | Perché è Sbagliato | Conseguenza |
|--------|-------------------|------------|
| No info entry | 50-50 engagge | Diventare prey |
| Utility spam early | Utility expired pre-entry | Entry exposed |
| Overpeek no backup | No trade possible | Die 1v5 deficit |
| Wrong weapon distance | TTK disadvantage | Lose fight |
| Retake timing late | Defuse attivo | Lose spike |
| Predictable lurk | Enemy pre-pick | Lurk eliminate |

---

## When to IGNORE "Errors"

Alcuni falsi-positivi che **non sono errori**:

- **Lucky enemy pick**: Enemy lucky headshot ≠ tuo error
- **Utility denied**: Se enemy destroy tuo utility, non tua fault
- **Teammate error**: Se teammate die male, not tuo error (unless tuo fault indiretto)
- **Macro loss**: Round perso per 5v4 inizio ≠ tuo error

---

## Conclusion: Roadmap Competenza

### Fase 1: Riconoscere Basic Errors (Week 1)
- Entry fail, plant block, economy crash
- **Tempo**: ~20s per clip

### Fase 2: Intermediate Errors (Week 2–3)
- Utility timing, positioning, decision-making
- **Tempo**: ~2 minuti per clip

### Fase 3: Advanced Errors (Week 4+)
- Micro-tattica, crosshair, multi-round economia
- **Tempo**: ~5 minuti per clip + multi-clip context

### Fase 4: Expert (Month 2+)
- Coaching mentality (non just identificazione, but fix proposta + drills)
- **Tempo**: 10–15 minuti per clip + personalized coaching plan

---

**Fine Guida.**

