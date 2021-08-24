<script context="module">
	export const prerender = true;
</script>

<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;
    let eight

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">NOCO's FINEST FFL CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: General</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: League Scoring / Roster Settings</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Schedule</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: League Champion</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Losers</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Draft Order Process</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: Keepers</h3>
	
    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Section 8: Trade Review Period</h3>
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 General</h2>
    <p>The league entry fee is $150 each year, unless voted on and approved by the league before the next season.</p>
    <p>Failure to pay your league fee is immediate expulsion from the league.</p>
    <p>Collusion:</p>
    	<ul>
		<li>Collusion is working with other manager(s)/team(s) to purposefully make their team better, while making your team worse, so that they might win the league. This includes exchanging of money to one team or another, so they purposefully lose, trade you all their players, etc.</li>

		<li>Collusion will not be tolerated and if prove, you will be banned from the league.</li>
    
  <h2 class="sectionHeading" bind:this={two}>Section 2 League Scoring / Roster Settings</h2>
    <p>16 Total Players</p>
    
    <p> class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>FLEX (RB/WR)</li>
        <li>K</li>
    </ul>
    
    <p>7 Bench</p>

    <p>2 IR Spots (Player must be labeled as IR, Out, or Covid in the Sleeper App)</p>    
    
    <h2 class="sectionHeading" bind:this={two}>Section 3 Schedule</h2>
    <p>Starting in 2021, the NFL is moving from a 16 week regular season, to a 17 week regular season (the NFL season will be 18 weeks with BYE weeks included).</p> 
    <p>This means that the fantasy regular season will start week 1 and end week 14 (instead of week 1 through week 13).</p> 
    <p>The fantasy playoffs will be pushed back by 1 week. The playoffs will be week 15, 16, and championship in week 17.</p>  
    <p>The weekly schedule (who plays who) for NOCOs Finest will be randomized on the site/app before the season starts.</p>
    <p>RIVALRY WEEKS</p>
    <ul>
        <li>Weeks 12, 13 & 14 will be rivalry weeks.</li>
        <li>Week 12 will be 1v12, 2v11, 3v10, 4v9, 5v8, 6v7</li>
        <li>Weeks 13 & 14 will be 1v2, 3v4, 5v6, 7v8, 9v10, 11v12</li>
    </ul>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 League Champion</h2>
    <p>League Champion will receive a trophy & money.</p> 
    <p>Prize pool to be voted on by the playoff teams before the playoffs begin.</p> 

    <h2 class="sectionHeading" bind:this={five}>Section 5 Losers</h2>
    <p>Each year the bottom 3 teams in the league will be determined by the consolation playoff bracket.</p> 
    <p>The bottom 3 will pay for the following years draft party (beer, food, etc.)</p> 

    <h2 class="sectionHeading" bind:this={six}>Section 6 Draft Order Process</h2>
    <p>The Gauntlet will be used to determine draft order.</p> 
    <p>The Gauntlet is a series of sporting events that we will compete or bet on that take place during the off season.</p>
    <p>The events will be determined by the commissioners.</p>
    <ul>
        <li>EXAMPLE: March Madness, The Masters, Kentucky Derby, Indy 500, Olympics, NHL Playoffs, British Open, etc.</li>
    </ul>
    <p>The winner of the Gauntlet will get to choose whatever draft slot they want for the upcoming draft, followed by 2nd place in the Gauntlet, etc.</p>
 
    <h2 class="sectionHeading" bind:this={seven}>Section 7 Keepers</h2>
    <p>Starting with the 2021 fantasy season, NOCO’s Finest FFL will allow for a MAX of 2 keepers per team.</p>
    <ul>
        <li>A fantasy manager may choose to keep 0 to 2 players for the season.</li>
    </ul>
    <p>Penalty / Cost for Keepers:</p>
     <ul>
        <li>Keeping a player will result in a 1 round penalty during the draft.</li>
	<li>Managers will lose their draft pick, 1 round prior to where the keeper was drafted the year before.</li>
	     <li>EXAMPLE:</li>
		     <li>Player A was drafted in round 10, the cost to keep player A is the manager’s round 9 pick this year.</li>
	     <li>Players drafted in round 1 of a draft can be kept and will cost the manager their 1st round pick.</li>
	     <li>Players drafted in round 2 will also cost a 1st round pick.</li>
	<li>Keeping 2 players:</li>
	     <li>EXAMPLE:</li>
	     	<li>Player A was drafted in round 7 in 2020 and player B was drafted in round 10 in 2020. The cost to keep both players is a round 6 pick for Player A, and a round 9 pick for player B.</li>
	     <li>Due to the 1 round penalty, a manager CANNOT keep 2 players drafted in round 1 of the previous year’s draft, OR players drafted in the SAME round.</li>
	     <li>Also, managers CANNOT keep 1 player drafted in round 1 AND a player drafted in round 2, because the manager is already losing their 1st round pick. It is not possible to lose a 1st round pick twice.</li> 
	<li>Players drafted in the previous season, and then dropped from one team and picked back up off waivers by another team during the season, will still have a penalty associated based on where they were drafted.</li> 
	     <li>EXAMPLE:</li>
		<li>Team A drafts Player A in round 5. Team A then drops the player and Team B picks the player up off waivers. The penalty for keeping this player is still round 4 in the following years draft.</li> 
	     		<li>The same rule applies to traded players.</li>
			<li>If Team A trades Player A to Team B, Team B will have a round 4 penalty next year if the player is kept.</li>
    </ul>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 Keepers</h2>
    <p>Keeper Length</p>
    <p>Starting with the 2021 season, NOCO’s Finest managers can only keep players for a MAX of 3 years.</p> 
    <p>The commissioners will track how long a player has been kept.</p>
    <p>After 3 years of being kept by the SAME team, a player can no longer be kept by that team.</p>
    <p>If a player is traded to a NEW team, the # of years kept restarts for that new team.</p>
    <p>EXAMPLE: If I keep Alvin Kamara for 3 more years, or trade him before then, whatever team takes him at that point will get a new 3 years to keep him.</p>
	 
    <h2 class="sectionHeading" bind:this={eight}>Section 8 Trade Review Period</h2>
    <p>Starting with the 2021 season, trades will go through as soon as they are accepted on the site/app.</p> 
    <p>This means there will no longer be a 24 hour “review/veto” period on the app/site.</p>
    <p>If the trade is suspicious, a poll will be created in GroupMe, text, etc., and voted on by the league.</p>
    <p>If the trade is determined unfair based on the league vote, the commissioners can reverse the trade on the app/site.</p>
   
 },
]
