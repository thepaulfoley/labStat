LabStat is going to be an Alexa Skill that can tell the user the operational status of MIT Lincoln Laboratory. The skill will be developed as a Flash Briefing skill. The Flash Briefing Skill doesn't allow for much flexibility but comes with a pre built "interaction model" which makes it much easier for first time Alexa Skill developers which I am. Also, developing a Flash Briefing Skill does not require buying any additional hosting service which is also important.

Steps:
- Add an content feed to thepaulfoley.com which grabs the lab status from the lab website and publishes it to the feed. The content feed must be RSS or JSON as that is what is supported by Flash Briefing skills 
* create alexa Flash Briefing skill that will get the latest entry from the lab status content feed on thepaulfoley.com
[https://developer.amazon.com/docs/flashbriefing/steps-to-create-a-flash-briefing-skill.html](https://developer.amazon.com/docs/flashbriefing/steps-to-create-a-flash-briefing-skill.html)
* test skill with my Echo
* test with other Echo