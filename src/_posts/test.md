---
layout: post
title: Test
subtitle: test
date: 2020-10-07T04:00:00Z
thumb_img_path: "/uploads/jonas-allert-drjoeqqqnxg-unsplash.jpg"
content_img_path: ''
excerpt: ''

---
**# README**

  
**## \[optional\] Overmind**  
\- \[DarthSim/overmind: Process manager for Procfile-based applications and tmux\]([https://github.com/DarthSim/overmind](https://github.com/DarthSim/overmind "DarthSim/overmind"))- Instead of using \`yarn start\`, you can run Bridgetown inside of Overmind instead.- Make changes to \`.overmind.env\` as needed.  
**### \[wip\] Recommended Workflow**  
\- Run \`overmind start\`, which run's daemonized by default.- Connect with \`overmind connect \[webpack,serve,sync\]\`, which puts you in a tmux session that allows you to switch to the other processes or create new ones.- Restart specific parts with \`overmind restart \[webpack,serve,sync\]\`  
Ex:  
\`\`\`shcd this-repoovermind startbundle add bridgetown-feed -g bridgetown_pluginsovermind restart bridgetown-serveovermind connectovermind kill\`\`\`  
**## Ruby 3**  
Note that this project is __currently__ using Ruby 3.0.0.preview-1