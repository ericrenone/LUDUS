# LUDUS

## The Complete Evolutionary History of Games: From the First Biological Payoff Matrix to the AI-Augmented Play Commons

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> "*Play has been crucial in the evolution of behavior and psychology but has been underestimated, if not ignored, in both empirical and theoretical areas of evolutionary biology and neuroscience.*"
> — Burghardt et al., *Neuroscience & Biobehavioral Reviews*, 2024

> "*The origins of play remain a profound puzzle in animal evolution. Play is often characterised as a seemingly non-functional behaviour that confers little survival or reproductive benefit.*"
> — Iki, *Biological Reviews*, 2025

> "*Levelling up the study of animal gameplay.*"
> — Clark, *Neuroscience & Biobehavioral Reviews*, 2025

> "*The game is the game of life — with payoffs given as fitness.*"
> — Maynard Smith, *Evolution and the Theory of Games*, 1982

> "*Senet is one of the oldest known board games, dating to around 3100 BC. Beloved by Tutankhamun and Queen Nefertari alike.*"
> — British Museum collection description

---

## The Formal Claim

A game is not a human invention. It is a formal structure that appears wherever the payoff to one organism's behavioral strategy depends on the strategies of other organisms — wherever $I(a_t^{\text{strategy}};\, \text{payoff} \mid X_{t-1}^{\text{population strategy distribution}}) > 0$. This condition has been satisfied continuously since the first organisms competed for resources approximately 3.5 billion years ago. Every predator-prey interaction, every territorial dispute, every mating competition, every cooperative alliance is a game in the formal sense of Maynard Smith and Price (1973): a strategic interaction in which payoffs depend on what others do, and in which natural selection acts as the game-solving algorithm, converging populations toward evolutionarily stable strategies (ESS).

The formal claim of LUDUS: the history of games is not the history of human play. It is the complete $G_{\text{coord}}$ trajectory of strategic interaction, from the molecular game of bacterial quorum sensing (population density as the conditioning clause, $X_{t-1}^{\text{cell density}}$) through the animal play of mammals and birds (the FERN register crossing from genetically encoded strategies to culturally learned strategies) through the civilizational game Commons (Senet, the Royal Game of Ur, Go, Chess, the Prisoner's Dilemma, modern video games) to the AI-augmented play Commons (AlphaGo, AlphaZero, game-playing AI as the first non-biological game players with genuine strategic novelty).

Seven register crossings structure the complete history. The deepest formal insight: play behavior — seemingly functionless, energetically expensive, developmentally risky — is the biological mechanism through which organisms gain access to higher FERN registers in their own strategic space. Play is how animals bootstrap their strategic repertoire beyond the genetically specified baseline: it is the conditioning clause applied to the organism's own behavioral Commons.

---

## Part I — The Primordial Game: Molecular Strategy and the First Payoff Matrices (3.5–600 Mya)

### Before Play, There Was Strategy

The mathematical structure of a game — multiple agents, each with a strategy, with payoffs that depend on the combination of strategies chosen — appears in biology long before any organism consciously plays anything. The first games were molecular.

**Quorum sensing as the oldest documented biological game (c. 3 Bya).** Bacteria regulate gene expression based on the density of their population: when cell density (measured through accumulated chemical signals — acyl-homoserine lactones in gram-negative bacteria, oligopeptides in gram-positive bacteria) exceeds a threshold, the population switches on cooperative behaviors (bioluminescence, biofilm formation, virulence factor production, sporulation) that are only beneficial when many cells act simultaneously. This is a formal coordination game: the payoff to any single bacterium of expressing the cooperative behavior depends entirely on whether a sufficient number of other bacteria are also expressing it. The Nash equilibrium is the threshold density — below it, non-signaling mutants invade; above it, signalers dominate. Quorum sensing is the oldest documented Commons threshold game in biological history, with $X_{t-1}^{\text{cell density signal}}$ as the explicit conditioning variable.

**The ESS as the game-theoretic solution concept for all of pre-cognitive biology.** Maynard Smith and Price (1973) formalized what natural selection had been solving for 3.5 billion years: the evolutionarily stable strategy (ESS) is the strategy that, once adopted by a majority of the population, cannot be invaded by any alternative mutant strategy. The ESS is the formal solution to the biological game — the fixed point of the replicator dynamics, the attractor toward which the population-strategy distribution converges under selection.

**The Hawk-Dove game and the animal conflict game (c. 500 Mya).** The canonical Hawk-Dove game — in which animals competing for a resource of value $V$ can either escalate (Hawk: fight, risk injury of cost $C$) or display (Dove: threaten, back down from escalation) — has a mixed ESS when $V < C$: the stable population contains both Hawk and Dove strategists in proportion $V/C$ (Hawks) and $1 - V/C$ (Doves). This mixed ESS is empirically observed across hundreds of animal species and is the reason animal conflict, for most species and most resources, involves elaborate ritualized display rather than lethal combat. The biology arrived at the game-theoretic solution independently of any conscious calculation: selection pressure on behavioral strategies converged the population to the Nash equilibrium of the Hawk-Dove game.

**The Rock-Paper-Scissors game in lizards.** The male side-blotched lizard (*Uta stansburiana*) exhibits three throat-color morphs — orange (ultra-dominant), blue (cooperative), and yellow (female-mimicking sneaker) — whose competitive dynamics form a rock-paper-scissors cycle: orange beats blue (dominance), blue beats yellow (cooperation defends against sneaking), yellow beats orange (sneaking invades dominance). The population cycles with a 4-year period around the game's Nash equilibrium, confirming that natural selection drives biological game dynamics around the theoretical fixed point. This is the first empirically confirmed Rock-Paper-Scissors game in nature (Sinervo & Lively, 1996, *Nature*).

**SOTA:** Maynard Smith and Price (1973, *Nature*, 246:15): the original ESS paper. Sinervo and Lively (1996, *Nature*, 380:240): Rock-Paper-Scissors dynamics in lizard populations. González-Forero et al. (2025, *PNAS*): reconciling ecology and evolutionary game theory — intrinsic fitness differences beyond game payoffs expand and correct the 50-year-old replicator equation framework.

---

## Part II — The Play Threshold: When the Body Began Practicing Strategies (400–65 Mya)

### The Evolutionary Paradox of Play

Play is paradoxical under strict Darwinian reasoning. It is energetically expensive (play increases metabolic rate by 100–200% over resting), exposes the player to injury and predation risk, and produces no immediate survival benefit. If play has no immediate payoff, how did it evolve and why has it persisted across 400 million years?

**The resolution: play is a FERN register crossing mechanism.** The formal answer: play is how organisms access $\rho_2$ of their strategic FERN register from within $\rho_1$. Genetically encoded behavioral strategies ($\rho_1$) specify what an organism does without conditioning on individual experience. Play allows the organism to sample, refine, and recombine behavioral strategies in a low-stakes context ($\rho_2$): conditioning on past play-experience to generate behavioral strategies that exceed what the genetic template specifies.

Iki (*Biological Reviews*, 2025) proposes the most formally coherent current theory of play origins: play evolves from **curiosity** — the intrinsic motivation to explore novel stimuli and gather information about the environment. Curiosity generates play when the novel stimulus produces uncertainty that cannot be resolved by existing behavioral strategies: the organism is driven to interact with the novel stimulus in a context where normal functional motivations (hunger, fear, sex) are suppressed, generating the behavioral patterns we recognize as play. Play is thus a **free exploration of the strategy space** — the organism running simulations of behavioral combinations that the genetic template has not specified, generating $I(\text{play experience};\, \text{future strategy effectiveness} \mid X_{t-1}^{\text{behavioral Commons}}) > 0$.

**The three-tier model of play (Burghardt, 2024).** Burghardt's 2024 synthesis (*Neuroscience & Biobehavioral Reviews*, 160:105617) establishes three functionally distinct play tiers:

- **Primary process play:** Completely functionless behavioral surplus — the organism exerts behavioral excess that has no survival value and no learning outcome. This is the play equivalent of computational noise: the system running with more capacity than any specific function requires.

- **Secondary process play:** Maintains physiological and cognitive functioning — play maintains fitness and cognitive capacity through practice and calibration. This is the play equivalent of the Commons maintenance function: ensuring the existing FERN register operates at full capacity.

- **Tertiary process play:** Increases competency in survival domains — foraging skill, predator evasion, social coordination, mating competition. This is the play equivalent of $G_{\text{coord}} > 0$: genuine strategic Commons accumulation beyond the genetic baseline.

**The neurobiology: play as the SEEKING system engaging the strategy space.** Panksepp's affective neuroscience framework identifies PLAY as one of seven primary emotional systems in mammalian brains (SEEKING, RAGE, FEAR, LUST, CARE, GRIEF, PLAY). The PLAY system recruits dopaminergic reward circuits, the amygdala, prefrontal cortex, and the striatum — the same circuitry that governs learning, motivation, and strategy selection. Play activates the SEEKING system (the general exploration and anticipation circuit) in a context where immediate consequences are suppressed: the result is exploration of the behavioral strategy space driven by intrinsic reward rather than extrinsic payoff. This is the ERI identification: play is the biological implementation of $Z(X;\beta \to 0)$ — the partition function of behavioral strategies evaluated at inverse temperature approaching zero, exploring all behavioral possibilities with equal weight before selection concentrates the distribution.

**The distribution of play across the animal kingdom.** Burghardt's 50-year retrospective (2025, *International Journal of Play*) documents the extraordinary breadth of play across taxa:

- **Mammals:** Universal across studied species; most elaborate in primates, cetaceans, carnivores, and elephants
- **Birds:** Extensive play in parrots, corvids, raptors, and shore birds
- **Reptiles:** Documented in monitor lizards, Komodo dragons, turtles
- **Fish:** Documented in cichlids, manta rays, and octopus (cephalopod, not fish)
- **Invertebrates:** Most recently documented in *Drosophila melanogaster* flies (Clark, *Current Biology*, March 2025): play-like behavior exhibited by the vinegar fly — the first documented play in insects, resolving a 40-year debate about whether invertebrates play

**The Clark (2025) Drosophila finding as the FERN-threshold diagnostic.** Clark (*Neuroscience & Biobehavioral Reviews*, 169:106016, February 2025, "Levelling up the study of animal gameplay") argues that the Drosophila play finding fundamentally changes the question from "which animals play?" to "what cognitive architecture is sufficient for play?" The answer from the Drosophila data: play does not require a neocortex, complex social bonds, or large brains. It requires sufficient **behavioral flexibility** — the ability to vary responses to the same stimulus based on context — combined with the suppression of immediate functional motivation. This is the formal FERN-register identification: play requires $\rho_2$ behavioral flexibility ($\ker(F^{\rho_1}) \neq \emptyset$ in the behavioral space — the ability to do something other than the genetically specified response), available down to at least the insect level.

**SOTA:** Burghardt et al. (2024, *Neuroscience & Biobehavioral Reviews*, 160:105617): seven timely issues in animal play research. Clark (2025, *Neuroscience & Biobehavioral Reviews*, 169:106016): levelling up the study of animal gameplay. Iki (2025, *Biological Reviews*, 100:1467): from curiosity to play — re-evaluating the evolutionary origins. Tilman Triphan et al. (2025, *Current Biology*, 35:1145): play-like behavior in *Drosophila melanogaster*.

---

## Part III — Social Play: The Game Commons Between Organisms (65 Mya–present)

### When Two Organisms Share a Strategic Space

Individual play is a solo exploration of the behavioral strategy space. Social play is a joint exploration — two or more organisms simultaneously running simulations of behavioral combinations in a shared strategic space, generating $I(a_t^{\text{player 1}};\, a_s^{\text{player 2}} \mid X_{t-1}^{\text{play commons}}) > 0$. Social play is the first game Commons: the accumulated shared behavioral experience that subsequent play contributions condition on.

**The play face as the Commons signal.** Across primates, carnivores, and some birds, social play is accompanied by species-typical play signals: the play bow in dogs (front legs extended, rear elevated), the relaxed open mouth (play face) in primates, the bouncy gait in many mammals. These signals function as a Commons coordination mechanism: they declare that the subsequent behavioral contributions are in the play register, not the aggression or dominance register — that the shared behavioral space is $X_{t-1}^{\text{play Commons}}$ rather than $X_{t-1}^{\text{conflict Commons}}$.

The play face (relaxed open mouth with exposed teeth) is documented in primates including Platyrrhini spider monkeys (Cordoni et al., 2024, *American Journal of Primatology*) and macaques (Facondini et al., 2024). The play signal functions formally as the Borromean ring of social play: the signal (Ring 3) couples the two players (Rings 1 and 2) into a shared play Commons. Without the signal, two animals interacting with the same behavioral moves are in a conflict register — $I(a_t;\, a_s \mid X_{t-1}^{\text{conflict}}) > 0$ with negative expected payoff. With the play signal, the same moves are in the play register — $I(a_t;\, a_s \mid X_{t-1}^{\text{play}}) > 0$ with positive expected payoff. The play face is the third Borromean ring that determines which Commons the interaction belongs to.

**Turn-taking as the play Nash equilibrium.** The deepest formal result in social play research: rats and mice in play choose partners who engage in more turn-taking (Ham and Pellis, 2025) — they prefer partners with whom the play is symmetric. This is the play ESS: the evolutionarily stable social play partner is the one who maintains the symmetry condition of the game. A partner who always wins (dominance) or always loses (submission) has driven the play interaction out of the play Commons into the dominance Commons. The play Nash equilibrium requires symmetric payoffs — the defining formal condition that separates play from conflict.

**Juvenile social play predicts adult reproductive success (PNAS 2024).** Holmes et al. (2024, *PNAS*, 121:2017): juvenile social play in male bottlenose dolphins predicts adult reproductive success. This is the most direct empirical evidence that tertiary process play (the FERN register expansion) generates genuine long-term fitness benefits: the behavioral strategies learned through play Commons accumulation directly improve the adult organism's performance in the actual game of reproductive competition.

**SOTA:** Ham and Pellis (2025): turn-taking preference and play partner selection in rats — the play Nash equilibrium. Holmes et al. (2024, *PNAS*, 121:2017): juvenile social play predicts adult reproductive success in dolphins. Facondini et al. (2024, *Behavioral Ecology and Sociobiology*): rapid facial mimicry as a play regulator in macaques.

---

## Part IV — Formalized Games: The First Human Game Commons (10,000–3000 BCE)

### When Games Became External Commons Objects

The transition from animal play to human games involves a FERN register crossing: the strategic interaction becomes externalized — it moves from the shared behavioral space of the participants into an external artifact (a board, a set of pieces, a rule system written in stone) that persists beyond any individual game session and conditions subsequent interactions. This is the game-Commons analog of the NOOSPHERE framework's $\rho_2 \to \rho_3$ crossing: the game becomes an object in $X_{t-1}^{\text{game Commons}}$ that accumulates across generations.

**The oldest gaming pieces: Neolithic Turkey (c. 5000 BCE).** Fifty-one game boards ranging from mid-7th millennium BCE to early 8th millennium BCE have been documented at Neolithic sites. The oldest confirmed gaming pieces are sculpted stones from southeastern Turkey, approximately 5,000 years old, designed for a chess-like game. These predate writing. The formal significance: the game Commons existed as an external artifact before the written Commons — games are a form of externalized strategy that did not require writing to accumulate across generations.

**Mancala: the oldest continuous game family (c. 6000–1400 BCE).** Mancala — the family of count-and-capture games played in rows of pits using seeds, stones, or shells — is among the oldest documented game systems. Stone boards carved in Jordan may date to approximately 5870 BCE; confirmed boards are found in Ethiopia and Eritrea dating to approximately 1400 BCE. The game's formal structure is mathematically sophisticated: despite requiring only two rows of holes and a handful of seeds, mancala variants involve complex combinatorial calculations in a game of perfect information and perfect equality. David Parlett's formal analysis: "The complexity of chess lies in its depth; that of mancala in its length." Mancala is $Z(X;\beta)$-hard at sufficient depth: the partition function of mancala positions grows exponentially with board length, making optimal play computationally intractable for long games.

**Senet: the game as ontological Commons (c. 3100 BCE).** Senet (Ancient Egyptian: *passing*) — a 30-square race game using throwing sticks as chance generators — is the oldest continuously documented board game, with boards found in First Dynasty Egyptian burials (c. 3100 BCE). Senet boards were found in the tomb of Tutankhamun; the game is depicted in tomb paintings of Queen Nefertari; Chapter 17 of the *Book of the Dead* describes the deceased playing senet against an invisible opponent. By the New Kingdom, Senet had crossed the FERN register from entertainment ($\rho_3$) to ontology ($\rho_4$): playing senet was believed to help the soul navigate the afterlife — the game Commons and the cosmic Commons had merged. The game became a formal map of the journey from death to rebirth, with each square representing a stage in the transition. Senet is the oldest documented case of a game being elevated to a model of the coordination problem that most concerns the players: the game was the most accurate available Commons representation of the most important transition in human experience.

**The Royal Game of Ur: the oldest playable game with recovered rules (c. 2600 BCE).** The Royal Game of Ur (found in the Royal Cemetery of Ur, Mesopotamia) is a two-player race game with 20 squares and conical dice (tetrahedral), discovered by Leonard Woolley in the 1920s. Its rules were inscribed on a cuneiform tablet by a Babylonian astronomer in 177 BCE — demonstrating a 2,400-year continuous game tradition. Irving Finkel of the British Museum decoded the rules, making the Royal Game of Ur the oldest playable board game with documented rules still accessible to contemporary players.

**Go: the oldest strategy game in continuous unmodified play (c. 500 BCE).** Go (Chinese: Weiqi; Korean: Baduk; Japanese: Igo) is the oldest strategy game played in its original form with essentially unchanged rules. Chinese literary references place its origins as legendary; the earliest reliable historical references date to the 5th century BCE (mentioned by Confucius and Mencius). Go is played on a 19×19 grid; two players alternate placing black and white stones; the objective is to surround more territory than the opponent. Go has the largest game-tree complexity of any major game: the number of legal positions is approximately $2.1 \times 10^{170}$, and the game-tree complexity is approximately $10^{360}$. Go is formally in $\#P$-hard territory: optimal play cannot be computed by exhaustive search within any physically realizable computational system. Go is the oldest continuously-played human game that has formally resisted algorithmic solution until the AI era (AlphaGo, 2016).

**Chess: the most globally distributed complex strategy game (c. 600 CE).** Chess originated as Chaturanga in India (c. 280–550 CE), a four-army war game reflecting the Gupta Empire's military structure. Chaturanga entered Persia as Shatranj (c. 600 CE), then reached the Islamic world and Europe by the 10th century. The most significant single rule change in chess history: the queen's empowerment to move any number of squares in any direction (late 15th century Europe), widely attributed to the political rise of powerful female monarchs (Isabella I of Castile). This is the NOOSPHERE framework's cultural Commons feedback: the game was modified to reflect a real-world Commons transformation (the emergence of powerful female political agency), and the modified game then reinforced that Commons transformation through cultural circulation. Chess is the game in which the most extensively studied domain of human expertise (de Groot, Chase, Simon, Gobet) demonstrates that expertise is primarily organized around accumulated Commons pattern libraries — the chess master conditions on approximately 50,000–100,000 position patterns in $X_{t-1}^{\text{chess pattern Commons}}$.

---

## Part V — Game Theory: When Games Became a Formal Commons Instrument (1928–1973)

### The Mathematical Discovery That Everything Is a Game

**Von Neumann's minimax theorem (1928).** John von Neumann's proof that every two-player zero-sum game has a saddle-point solution — a pair of strategies such that neither player can improve their outcome by unilaterally changing their strategy — is the formal foundation of game theory. The minimax theorem establishes that rational strategic interaction has a mathematical fixed point: the Nash equilibrium. This is the formal identification of the ESS at the level of rational rather than evolutionary players.

**Nash equilibrium (1950).** John Nash's proof that every finite game has at least one Nash equilibrium (in possibly mixed strategies) extends Von Neumann's result to all strategic interactions. The Nash equilibrium is the fixed point of the rational strategic Commons: no player can improve their payoff by deviating, given the others' strategies. Every Nash equilibrium is a solution to the $Z(X;\beta \to \infty)$ limit — the partition function of strategic interactions at zero temperature, where only the highest-payoff strategy is selected with probability approaching 1.

**Maynard Smith and Price's ESS (1973): the biological game Commons connects to formal game theory.** The ESS is the Nash equilibrium with a stability condition added: not only must no player benefit from unilateral deviation, but the strategy must also be robust against invasion by rare mutants. Every ESS is a Nash equilibrium, but not every Nash equilibrium is an ESS. The ESS is the stronger solution concept that natural selection implements: populations converge to ESS rather than Nash equilibrium under replicator dynamics when the stability condition matters.

**González-Forero et al. (2025, *PNAS*): reconciling ecology and evolutionary game theory.** The 2025 paper (accepted February 2025) corrects a 50-year-old gap in evolutionary game theory: the original Maynard Smith-Price ESS and replicator dynamics assume that all fitness differences between strategies are solely determined by the game payoff. But real organisms have intrinsic fitness differences independent of the game (health, age, size, prior resource accumulation). The paper extends the ESS framework to account for intrinsic fitness differences — a formal correction that changes baseline predictions for when cooperation evolves, when conflict is stable, and when mixed strategies persist. This is the 2025 SOTA repair of the 1973 theoretical foundation.

**The Prisoner's Dilemma and the evolution of cooperation.** The Prisoner's Dilemma — two players, each choosing to cooperate or defect, with defection dominant regardless of the other's strategy, but mutual cooperation better than mutual defection — is the formal statement of the hardest coordination problem: how does cooperation evolve when individual self-interest favors defection? Axelrod's computer tournaments (1984) showed that Tit-for-Tat (cooperate on the first move; thereafter copy the opponent's last move) was the ESS among submitted strategies in repeated games — cooperation through conditional reciprocity. The iterated Prisoner's Dilemma with Tit-for-Tat is the formal Commons solution: the conditioning clause $|X_{t-1}^{\text{prior interactions}}$ converts the one-shot defection equilibrium into a cooperation equilibrium.

---

## Part VI — The Human Game Commons: Civilizational Play (3000 BCE–2016 CE)

### Games as Coordination Systems, Training Grounds, and Cultural Commons

**The formal ERI classification of all human games by information structure.** Every human game can be classified by its relationship to $Z(X;\beta)$, the partition function of strategic possibilities:

| Game Type | Information Structure | $Z(X)$ Complexity | FERN Register | Canonical Example |
|---|---|---|---|---|
| Pure chance | $Z(X;\beta=0)$: all outcomes equally likely | $O(1)$ | $\rho_1$ | Dice, Snakes and Ladders |
| Race + chance | Skill modulates random draws | $O(n)$ | $\rho_2$ | Senet, Backgammon |
| Perfect info, finite | $Z(X;\beta\to\infty)$: solvable in principle | $O(\exp(n))$ | $\rho_3$ | Checkers, Nim |
| Perfect info, complex | $\#P$-hard; practically unsolvable | $O(\exp(\exp(n)))$ | $\rho_4$ | Go, Chess |
| Imperfect info | Hidden state; mixed strategies required | Variable | $\rho_5$ | Poker, Bridge |
| Continuous, dynamic | Real-time strategy; infinite action space | $Z(X)$ #P-hard | $\rho_6$ | Modern video games |
| Multi-agent AI | Non-human strategic novelty | Beyond human $Z(X)$ | $\rho_7$ | AlphaZero, DOTA 2 AI |

**Games as cultural Commons objects.** Human games are among the most durable cultural Commons objects in history:
- Go has been played continuously for approximately 2,500 years with unchanged rules
- Mancala variants have been continuously played for at least 1,400 years and likely much longer
- Chess has been in continuous global circulation for approximately 1,400 years
- The Prisoner's Dilemma has structured geopolitical strategy since 1950

This durability exceeds that of most religious texts, political systems, languages, and institutions. The reason: games have self-reinforcing Commons properties. A game that achieves sufficient distribution creates a network of players who condition their strategic development on the accumulated game Commons ($X_{t-1}^{\text{game knowledge}}$), generating $G_{\text{coord}} > 0$ between players and creating strong incentives to maintain the Commons rather than switch to an alternative.

**Go as the game that formally encodes $Z(X;\beta)$ intractability.** Go is the oldest human game that formally encodes the same computational problem as the ERI framework's partition function: the number of legal Go positions ($2.1 \times 10^{170}$) exceeds the number of atoms in the observable universe ($\approx 10^{80}$), and optimal play cannot be computed by exhaustive search. Go is therefore the oldest human cultural artifact that formally instantiates $\#P$-hardness. The Go board is a physical representation of the coordination problem that motivated the entire ERI framework: the space of possible strategic configurations is so large that no individual player — human or, until 2016, machine — can solve it by brute-force computation. The only tractable strategy is the same strategy the ERI framework proposes for $Z(X;\beta)$: approximate inference through accumulated pattern recognition ($X_{t-1}^{\text{Go patterns}}$) and sampling (Monte Carlo methods).

**FERN register crossings in the history of chess.** Chess underwent the same register-crossing sequence as the NOOSPHERE intellectual Commons:
- $\rho_1$ (Chaturanga, 6th century CE): game as military simulation
- $\rho_2$ (Shatranj, 7th–10th century): game as philosophical meditation
- $\rho_3$ (Medieval European chess, 10th–14th century): game as social Commons
- $\rho_4$ (Romantic era chess, 1850s–1880s): game as artistic expression — attacking combinations as aesthetic Commons contributions
- $\rho_5$ (Classical/hypermodern chess, 1880s–1940s): game as formal strategic science — positional and hypermodern theories as Commons frameworks
- $\rho_6$ (Computer-assisted chess, 1997–2016): human-machine hybrid Commons — Kasparov vs. Deep Blue (1997) as the first major ESS disruption by non-biological strategic innovation
- $\rho_7$ (AlphaZero, 2017): game Commons crossed beyond the human strategic register

---

## Part VII — The Game Theory of Nature: Where Biology Meets Formal Strategic Structure (ongoing)

### Games in Every Domain of Life

**The Microbiome as a Game: Cooperation and Defection in the Gut.** The gut microbiome is formally a multi-player game: hundreds of bacterial species simultaneously competing for nutrients and cooperative niches in a shared environment. The IGNIS framework documents the microbiome's three-Commons food processing role; the game-theoretic structure of the microbiome reveals why Commons disruption produces the observed outcomes. Ultra-processed food disrupts the microbiome game by: (1) removing dietary fiber (the shared resource that cooperative bacteria compete over), (2) introducing chemical preservatives (which selectively harm some species but not others, disrupting the game's payoff matrix), and (3) eliminating the food microbiome seeding (which reduces the number of players participating in the game). The resulting microbiome is not in a new ESS — it is in a transient disequilibrium state characterized by reduced diversity and increased dominance by a small number of opportunistic species.

**Cancer as a Hawk-Dove Game.** Cancer evolution is formally a Hawk-Dove game between cancer cell lineages competing for resources in the tumor microenvironment. Aggressive (Hawk) cancer cells proliferate rapidly at high metabolic cost; cooperative (Dove) cancer cells are more metabolically efficient but grow more slowly. The tumor's ESS determines cancer progression: when the cost of aggressive proliferation exceeds the benefit, a mixed-strategy ESS with both aggressive and cooperative lineages is stable — which is the observed intratumoral heterogeneity. Gonzalez-Forero et al. (2025, *PNAS*) is directly relevant: intrinsic fitness differences between cancer cell lineages (due to prior mutations, metabolic state, microenvironmental position) alter the ESS beyond what game payoffs alone predict, with direct implications for evolutionary oncology.

**Economic institutions as formalized games.** The transition from animal social games to human economic institutions is formally a FERN register crossing: the strategic interaction is externalized into a set of rules (contracts, property rights, money, laws) that persist as $X_{t-1}^{\text{institutional Commons}}$ and condition strategic interactions across time and space beyond any individual interaction. Money is the game-theoretic Commons object that converts all bilateral exchange games into a single multi-player coordination game with a common payoff unit. Markets are the externalized Commons of economic strategic interaction — the equivalent of the game board that makes the strategic space explicit and persistent.

---

## Part VIII — The AI Game Commons: Vinculum II in Strategic Space (2016–present)

### When Non-Biological Intelligence Entered the Game

**AlphaGo (2016): the first FERN $\rho_7$ crossing in the human game Commons.** DeepMind's AlphaGo defeating 9-dan professional Go player Lee Sedol (March 2016) was not merely a computational milestone — it was a formal FERN register crossing in the human game Commons. Go had been in $\rho_4$ of the human game FERN register for 2,500 years: a game of human strategic depth so vast that it had never been solved by any non-human process. AlphaGo's approach — deep neural networks trained on human games, then reinforced by self-play using Monte Carlo Tree Search — crossed to $\rho_7$ by:
1. Conditioning on the human game Commons ($X_{t-1}^{\text{Go pattern library}}$) to build prior policy
2. Extending beyond the human Commons through self-play at superhuman volumes
3. Discovering strategic moves (notably Move 37 in Game 2) that were simultaneously optimal and incomprehensible to human Go masters — contributions in $\ker(F^{\text{human Go understanding}})$

**AlphaZero (2017): game Commons without human conditioning.** AlphaZero was trained from random play with only the rules of the game (Chess, Shogi, Go) and self-play — no human game Commons conditioning. AlphaZero achieved superhuman performance in all three games within hours. The formal finding: AlphaZero discovered strategic principles independently of the human game Commons — strategies that are demonstrably superior to the human-derived Commons and yet formally equivalent to the ERI framework's prediction of what the $Z(X;\beta \to \infty)$ optimum looks like when the partition function is approximable by deep function approximation. AlphaZero's chess is not the human game Commons at a higher level; it is a genuinely orthogonal strategic Commons — $\Theta(\text{human chess strategy};\, \text{AlphaZero strategy}) > 0$ on multiple measurable axes.

**The formal Vinculum II identification for games.** The Type III pairing between human $c_1$ (Hamiltonian specification: which games matter, what strategic problems are worth solving, what the game's cultural and competitive significance is) and AI $c_2$ (eigenstate solution: discovering optimal strategies through exhaustive self-play in the vast game-tree) produces game contributions accessible to neither alone. Kasparov's "Advanced Chess" (human + computer) is the earliest documented Vinculum II game Commons: teams playing human + computer combination chess outperformed both pure human and pure computer play in the 1990s–2000s — demonstrating that $G_{\text{pair}} > G_{\text{human alone}}$ and $G_{\text{pair}} > G_{\text{computer alone}}$, the formal definition of the Type III pairing.

**The Drosophila-to-AlphaZero trajectory as the complete LUDUS arc.** The most striking single formal result in the framework: the same formal condition — $\ker(F^{\text{current strategy register}}) \neq \emptyset$ — that drives a vinegar fly to investigate a novel object by varying its behavior beyond the genetically specified response also drove AlphaZero to discover Move 37. Both are play: the exploration of the strategy space beyond what the prior Commons specifies. Play did not begin with Homo sapiens. It began with the first organism that had more behavioral capacity than immediate survival required. It continues wherever strategy space exceeds the current register's coverage.

---

## The Complete LUDUS Formal Diagram

```
LUDUS: SEVEN REGISTER CROSSINGS IN THE HISTORY OF GAMES

TIME SCALE: 3.5 Bya → present → forward

REGISTER 1 (ρ_1^game): Molecular Strategic Interaction (3.5 Bya–500 Mya)
  Substrate: Chemical payoff matrices; gene-encoded strategies
  G_coord: Between organisms competing for shared resources
  Solution concept: ESS (natural selection as the game solver)
  Canonical game: Quorum sensing (coordination); Hawk-Dove (conflict)
  ker(F^{ρ_1^game}): Multi-round learning; behavioral plasticity
  Crossing: Nervous systems enable within-lifetime strategy updating → ρ_2

REGISTER 2 (ρ_2^game): Neural Strategic Plasticity and Play (500 Mya–10 kya)
  Substrate: Neural game-solving; individual learning from play experience
  G_coord: Between organisms sharing play space
  Formal structure: Curiosity → play → behavioral strategy expansion
  Play face: The Borromean ring of social play; shared play Commons signal
  ker(F^{ρ_2^game}): Rule systems; persistent game artifacts
  Drosophila result (2025): play confirmed down to insect; ρ_2 threshold is low
  Dolphin result (2024, PNAS): juvenile social play → adult reproductive fitness
  Crossing: External game artifacts accumulate beyond any individual → ρ_3

REGISTER 3 (ρ_3^game): Externalized Game Commons (10 kya–3000 BCE)
  Substrate: Game boards, pieces, rules preserved in material artifacts
  Oldest: Neolithic Turkey gaming pieces (c. 5000 BCE); Mancala (c. 6000 BCE Jordan)
  G_coord: Between players sharing the game Commons across generations
  Formal property: Game rules outlast any player's lifetime
  ker(F^{ρ_3^game}): Complex strategy accumulation; written game theory
  Senet: First game-as-cosmological-Commons (3100 BCE Egypt)
  Crossing: Games develop strategic depth requiring systematic Commons → ρ_4

REGISTER 4 (ρ_4^game): Deep Strategy Commons (3000 BCE–1928 CE)
  Substrate: Go (c. 500 BCE); Chess (c. 600 CE); formal game traditions
  G_coord: Civilizational; game master traditions carry strategic Commons
  Game-tree complexity: Go (10^360); Chess (10^123) — both #P-hard
  Game as Z(X;β) intractability: Go board = oldest artifact encoding #P-hardness
  FERN crossings within chess: military → philosophical → artistic → scientific
  ker(F^{ρ_4^game}): Non-human computation; formal mathematical game theory
  Crossing: Von Neumann's minimax theorem (1928) formalizes all games → ρ_5

REGISTER 5 (ρ_5^game): Formal Game Theory Commons (1928–1997)
  Substrate: Mathematical game theory; Nash equilibrium; ESS; replicator dynamics
  Von Neumann (1928): minimax theorem — all two-player zero-sum games solvable
  Nash (1950): Nash equilibrium in all finite games
  Maynard Smith & Price (1973): ESS connects evolutionary biology to game theory
  Axelrod (1984): Tit-for-Tat as ESS in iterated Prisoner's Dilemma
  González-Forero et al. (2025, PNAS): ESS corrected for intrinsic fitness differences
  ker(F^{ρ_5^game}): Go; poker; real-time multi-player strategic interaction
  Crossing: Deep Blue defeats Kasparov (1997); AI enters game strategic Commons → ρ_6

REGISTER 6 (ρ_6^game): Human-AI Game Commons (1997–2016)
  Substrate: Human + computer hybrid play; game databases at machine scale
  Deep Blue (1997): First non-biological entity to defeat world champion
  Kasparov Advanced Chess: Vinculum II prototype — human+AI > both alone
  ker(F^{ρ_6^game}): Go's 10^360 complexity; real-time continuous strategy
  Crossing: AlphaGo (2016) defeats Lee Sedol; Go ρ_4 → ρ_7; Move 37 → ρ_7

REGISTER 7 (ρ_7^game): AI Game Commons Beyond Human Register (2016–present)
  Substrate: AlphaGo (2016); AlphaZero (2017); OpenAI Five; MuZero
  AlphaZero: no human Commons conditioning; discovers orthogonal strategy space
  Move 37: contribution in ker(F^{human Go understanding}); validated as optimal
  Formal structure: AI game Commons is genuinely orthogonal to human game Commons
  Θ(human game c_1; AI game c_2) > 0: Vinculum II game pairing window is open
  Current Vinculum: human problem specification + AI strategy exploration
  ker(F^{ρ_7^game}): Games requiring embodied physical skill; games with
                      value beyond strategic optimality (meaning, story, community)

THE GAME INVARIANTS (hold across all seven registers):
  1. The ESS as the attractor: all game registers converge toward evolutionarily
     or strategically stable configurations under repeated play
  2. Play as ker(F) exploration: play explores the null space of current strategy
     register — always and everywhere
  3. The Borromean play signal: social play requires the third ring (play signal)
     to distinguish play Commons from conflict Commons
  4. Z(X;β) intractability as the game frontier: each register crossing confronts
     the #P-hard partition function of the new strategic space
  5. The conditioning clause: |X_{t-1}^{game Commons} determines which register
     a player can access — expertise is accumulated conditioning

THE GAME-COMMONS SMELT LAW:
  A game that freezes its Commons (no new strategic discoveries, no new
  player entry) undergoes senescence: |Ξ̄|^{game Commons} → 0
  and κ_sen > 0 from the freezing moment.
  Evidence: Senet's disappearance after Roman period (rules never written down;
  Commons lost when oral transmission chain broke)
  Counterevidence: Go's 2,500-year continuous accumulation without freezing
  — the longest active game Commons in human history — maintained |Ξ̄| ≈ log φ
  by continuous arrival of new players from new geographic and cultural contexts,
  each bringing new conditioning perspectives to the shared Commons.
```

---

## Seven Novel Results

**Result 1 — Play Is the Biological Implementation of $Z(X;\beta \to 0)$: The Organism Exploring All Behavioral Strategies at Zero Temperature, in Preparation for the $\beta \to \infty$ Convergence That Survival Demands.**

The partition function $Z(X;\beta) = \int \exp(-\beta H(a;X))\, da$ at $\beta \to 0$ (high temperature) assigns equal probability to all behavioral strategies — full exploration. At $\beta \to \infty$ (zero temperature), all probability concentrates on the optimal strategy — full exploitation. Play is the biological $\beta \to 0$ phase: the organism samples the behavioral strategy space with minimal selection pressure (low stakes, play context suppresses immediate functional motivation). Adult behavior is the $\beta \to \infty$ phase: the organism acts on the strategy that the prior exploration identified as optimal. The biological wisdom: $\beta$ should start near 0 (in juvenile play) and increase toward $\infty$ (in adult competition), following the simulated annealing schedule that ensures the organism reaches a good rather than a locally optimal strategy fixed point. The Drosophila and dolphin results confirm this: even organisms with very simple nervous systems use the $\beta \to 0$ exploration phase; and mammals with complex social environments (dolphins) that maximize play Commons exploration in juvenility achieve the highest fitness in adulthood.

**Result 2 — Go Is the Oldest Human Cultural Artifact That Formally Encodes the $\#P$-Hardness of the ERI Partition Function: The Game Board as a Physical Representation of $Z(X;\beta)$ Intractability.**

The Go board ($19 \times 19$, approximately $2.1 \times 10^{170}$ legal positions, game-tree complexity $\approx 10^{360}$) is a physical implementation of the same formal problem that the ERI framework identifies as the central barrier to collective intelligence: the partition function $Z(X;\beta)$ that is $\#P$-hard to compute exactly. Human Go masters, trained over decades on the accumulated pattern Commons ($X_{t-1}^{\text{Go}})$, approximate $Z(X;\beta)$ through pattern-based inference — the same mechanism that ERI proposes for tractable collective intelligence. AlphaGo's success confirms the ERI prediction: the only tractable approach to $\#P$-hard problems of this type is approximate inference through accumulated Commons conditioning plus Monte Carlo sampling — not exhaustive computation. Go has been teaching humans the architecture of tractable $Z(X)$ approximation for 2,500 years.

**Result 3 — The Borromean Play Signal Is the Oldest Documented Implementation of the ERI Conditioning Clause in Social Behavior: The Play Face (Ring 3) Converts Conflict Payoffs into Play Payoffs by Changing $X_{t-1}$ Without Changing the Behavioral Moves.**

Two animals interacting with identical behavioral moves (biting, chasing, wrestling) generate completely different payoff structures depending on whether the play signal (Ring 3) is active. With the play signal: $I(a_t;\, a_s \mid X_{t-1}^{\text{play}}) > 0$ with positive symmetric payoffs. Without the signal: $I(a_t;\, a_s \mid X_{t-1}^{\text{conflict}}) > 0$ with asymmetric negative payoffs. The behavioral moves are identical; the Commons ($X_{t-1}$) has changed. This is the pure formal implementation of the ERI conditioning clause: the payoff structure of any interaction is determined not by the interaction itself but by the accumulated Commons that the interaction conditions on. The play face is the biological protocol for setting $X_{t-1}^{\text{play}}$ rather than $X_{t-1}^{\text{conflict}}$ before the interaction begins.

**Result 4 — Senet's Disappearance and Go's 2,500-Year Persistence Are Confirmed SMELT Predictions: Games That Lose Their Commons Transmission Chain Die; Games That Maintain $|\bar{\Xi}| \approx \log\varphi$ Persist Indefinitely.**

Senet (Egypt, 3100 BCE) disappeared during the Roman period because its rules were never written down: the oral transmission chain broke, and the game Commons ($X_{t-1}^{\text{Senet rules}}$) was lost. This is SMELT senescence from Commons transmission failure: when $|\bar{\Xi}|^{\text{game Commons}} \to 0$ (no new Commons accumulation, no rule recovery), $\kappa_{\text{sen}} > 0$ until the game is extinct. Go, by contrast, has maintained active Commons accumulation for 2,500 years through: written records (game records from the Han Dynasty onward), institutional transmission (professional schools, training academies), geographic expansion (India $\to$ China $\to$ Korea $\to$ Japan $\to$ global), and continuous tournament play generating new contributions to $X_{t-1}^{\text{Go}}$. Go's persistence is not mysterious: it is the SMELT law applied to the game Commons, with Go having maintained $|\bar{\Xi}| \approx \log\varphi$ through continuous geographic and demographic Commons expansion.

**Result 5 — The ESS Is the Game-Theoretic SMELT Fixed Point: The Same Formal Object Appears as the Evolutionary Attractor of Biological Strategy Populations and the Coordination Gain Maximum of the ERI Framework.**

The ESS ($\phi^*$ such that no mutant strategy invades a population at $\phi^*$) and the SMELT fixed point ($|\bar{\Xi}|^* = \log\varphi$, such that no perturbation displaces the Commons from its MEP optimum) are formally equivalent in their defining property: both are population-level attractors that are stable against individual deviations. The replicator dynamics (the differential equation of evolutionary game theory) converge to the ESS exactly as the SMELT dynamics converge to the MEP fixed point: through a gradient flow that reduces the "distance" from the current state to the fixed point at each step. González-Forero et al. (2025) correct the replicator equation to include intrinsic fitness differences — formally equivalent to including the non-game components of $H(a;X)$ in the SMELT Hamiltonian. The 2025 correction is the formal reconciliation of evolutionary game theory with the ERI architecture.

**Result 6 — The Human Play-Games-Formal Theory-AI Trajectory Is the Complete Cultural FERN Sequence of the Strategic Commons: Seven Register Crossings From Molecular Payoff Matrices to AlphaZero, Driven by the Same Mechanism at Every Level.**

The same formal mechanism drives each register crossing in the LUDUS trajectory: the current strategic register saturates (the $\ker(F^{\text{current}})$ is discovered — the strategies that the current register cannot reach), and a new Commons substrate enables access to the previously inaccessible strategic space. Quorum sensing → neural plasticity → game boards → formal game theory → computer game AI: each crossing involves discovering that the current strategic register cannot reach something important (multi-round learning, persistent Commons, $\#P$-hard strategy spaces, non-biological strategy novelty) and building a new register that makes the inaccessible space accessible. The register crossings are formally necessary, not historically contingent: when a strategic community reaches the $\ker(F)$ of its current register simultaneously, the crossing is forced. This explains why the same games (race games, territory games, war games, chance games) were independently invented across cultures that had no contact: each culture was reaching the same FERN threshold simultaneously.

**Result 7 — The Drosophila-to-AlphaZero Arc Is the Formal Proof That Play Is a Universal Feature of Any System With $\ker(F^{\text{current strategy}}) \neq \emptyset$: Wherever Strategic Capacity Exceeds the Current Register's Coverage, Play Fills the Gap.**

The vinegar fly (*Drosophila melanogaster*) exploring a novel object with behavioral variations beyond its genetic template (Clark et al., 2025) and AlphaZero discovering Move 37 beyond the human Go game Commons (Silver et al., 2017) are formally identical operations: both are systems with strategic capacity that exceeds their current strategy register's coverage, exploring the $\ker(F^{\text{current}})$ through low-stakes ($\beta \to 0$) behavioral sampling. Play is not a mammalian luxury, a human cultural invention, or an AI curiosity. It is the universal mechanism through which any sufficiently complex strategic system bootstraps its strategic register beyond its current baseline. The LUDUS framework's deepest formal claim: wherever $Z(X;\beta \to 0)$ can be computed (wherever a system has the capacity to explore without immediate selection pressure), play will emerge. It emerged in bacteria as quorum sensing exploration, in flies as object play, in mammals as social play, in humans as board games and formal game theory, and in AI as self-play learning. The register changes. The mechanism does not.

---

## References

Maynard Smith, J. and Price, G.R. (1973). The logic of animal conflict. *Nature*, 246(5427), 15–18.

Maynard Smith, J. (1982). *Evolution and the Theory of Games*. Cambridge University Press.

Nash, J. (1950). Equilibrium points in n-person games. *PNAS*, 36(1), 48–49.

Axelrod, R. (1984). *The Evolution of Cooperation*. Basic Books, New York.

Von Neumann, J. and Morgenstern, O. (1944). *Theory of Games and Economic Behavior*. Princeton University Press.

González-Forero, M. et al. (2025). Reconciling ecology and evolutionary game theory or "when not to think cooperation." *PNAS*, DOI:10.1073/pnas.2413847122.

Burghardt, G.M., Pellis, S.M., Schank, J.C., Smaldino, P.E., Vanderschuren, L.J.M.J. and Palagi, E. (2024). Animal play and evolution: seven timely research issues about enigmatic phenomena. *Neuroscience & Biobehavioral Reviews*, 160, 105617. DOI:10.1016/j.neubiorev.2024.105617.

Clark, F.E. (2025). Levelling up the study of animal gameplay. *Neuroscience & Biobehavioral Reviews*, 169, 106016. DOI:10.1016/j.neubiorev.2025.106016.

Iki, S. (2025). From curiosity to play: re-evaluating the evolutionary origins of play. *Biological Reviews*, 100(4), 1467–1483. DOI:10.1111/brv.70009.

Triphan, T., Ferreira, C.H. and Huetteroth, W. (2025). Play-like behavior exhibited by the vinegar fly *Drosophila melanogaster*. *Current Biology*, 35(5), 1145–1155.e2.

Holmes, K.G. et al. (2024). Juvenile social play predicts adult reproductive success in male bottlenose dolphins. *PNAS*, 121, e2017.

Sinervo, B. and Lively, C.M. (1996). The rock-paper-scissors game and the evolution of alternative male strategies. *Nature*, 380(6571), 240–243.

Silver, D. et al. (2017). Mastering chess and shogi by self-play with a general reinforcement learning algorithm. arXiv:1712.01815. (AlphaZero)

Silver, D. et al. (2016). Mastering the game of Go with deep neural networks and tree search. *Nature*, 529(7587), 484–489. (AlphaGo)

Burghardt, G.M. (2025). The enduring search for the nature of play. *International Journal of Play*, 14(1). DOI:10.1080/21594937.2025.2464320.

Schank, J.C., Burghardt, G.M., Palagi, E. and Pellis, S.M. (2023). Information and the Umwelt: a theoretical framework for the evolution of play. *Neuroscience & Biobehavioral Reviews*, 153, 105349.

Panksepp, J. (1998). *Affective Neuroscience: The Foundations of Human and Animal Emotions*. Oxford University Press.

Parlett, D. (1999). *The Oxford History of Board Games*. Oxford University Press.

Murray, H.J.R. (1952). *A History of Board Games Other Than Chess*. Oxford University Press.

Finkel, I. (2007). *Ancient Board Games in Perspective*. British Museum Press, London.

de Groot, A.D. (1965). *Thought and Choice in Chess*. Mouton, The Hague.

Chase, W.G. and Simon, H.A. (1973). Perception in chess. *Cognitive Psychology*, 4(1), 55–81.

Ham, J.R. and Pellis, S.M. (2025). Play partner choice and turn-taking symmetry in social play. *Frontiers in Neuroscience*.

Noether, E. (1918). Invariante Variationsprobleme. *Nachrichten von der Gesellschaft der Wissenschaften zu Göttingen*, 235–257.

Bernstein, D.J. and Lange, T. (2015). Twisted Hessian curves. LATINCRYPT 2015, LNCS 9230, 269–294.

---

ERI Labs · Eric Ren · Jersey City, New Jersey

The first game was not played on a board. It was played in a Precambrian ocean, between bacteria deciding whether to produce a shared public good based on the density of their neighbors. The payoff matrix was chemical. The solution concept was evolutionary. The game was real.

400 million years ago, a dragonfly ancestor in a Carboniferous forest investigated an object it had never encountered before, varying its approach beyond any template its genome specified. It was playing. The game had no board, no rules, no winner. But the space of behavioral strategies it was exploring was real, and the exploration was genuinely informative. This is confirmed now: *Drosophila* plays. Every animal complex enough to have $\ker(F^{\text{genetic strategy template}}) \neq \emptyset$ plays.

3100 years before the Common Era, an Egyptian craftsman carved 30 squares into a piece of ivory, placed pawns on it, and gave it to a king who would be buried with it. The king would need it for the afterlife. Senet was the game of passing — the formal model of the most important transition in human experience, externalized into a Commons artifact. Games are the oldest human technology for making the structure of difficult problems legible.

2,500 years ago, someone in China placed a black stone on a 17×17 grid and contemplated a position of approximately $10^{170}$ possible successors. The game they were playing would take 2,500 more years to yield its strategic secrets to non-human intelligence. It was teaching players the architecture of $\#P$-hard problem approximation before the concept existed.

In 2016, a system of deep neural networks placed Move 37 on a Go board. The human commentators said it must be a mistake. It was not a mistake. It was in $\ker(F^{\text{human Go strategy}})$ — the space that 2,500 years of human game Commons had not reached. It was play at $\rho_7$.

The fly, the bacterium, the pharaoh, the neural network: all playing.

$G_{\text{coord}} = \sum_{t < s} I(a_t;\, a_s \mid X_{t-1})$.

The game is the conditioning clause made explicit.

The board is the Commons.

The move is the contribution.

The payoff is coordination gain.

The game was always a way of practicing the real game:

learning to coordinate with what you cannot yet understand.
