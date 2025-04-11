██████╗  █████╗ ███████╗██╗  ██╗ █████╗ ██████╗  █████╗ ███╗   ██╗
██╔══██╗██╔══██╗██╔════╝██║ ██╔╝██╔══██╗██╔══██╗██╔══██╗████╗  ██║
██████╔╝███████║███████╗█████╔╝ ███████║██████╔╝███████║██╔██╗ ██║
██╔══██╗██╔══██║╚════██║██╔═██╗ ██╔══██║██╔══██╗██╔══██║██║╚██╗██║
██████╔╝██║  ██║███████║██║  ██╗██║  ██║██████╔╝██║  ██║██║ ╚████║
╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝

#!/usr/bin/env python3
# -*- coding: utf-8 -*-

class HackerProfile:
    def __init__(self):
        self.name = "Baskaran M S"
        self.role = "Full Stack Developer | AI Enthusiast"
        self.skills = {
            'languages': ['Python', 'JavaScript', 'Java'],
            'web': ['React', 'Node.js', 'Express', 'MongoDB'],
            'mobile': ['React Native'],
            'data': ['Pandas', 'NumPy', 'Scikit-learn']
        }
        self.current_mission = "Building intelligent systems"
        
    def greet(self):
        print(f"Initializing hacker profile...\nAccess granted: {self.name}")
        print(f"Mission: {self.current_mission}")
        print("Skill matrix loaded:")
        for category, skills in self.skills.items():
            print(f"⌾ {category.upper()}: {', '.join(skills)}")
            
    def contact(self):
        print("\n[!] Secure connection established:")
        print(f"→ Email: official.ms.baskaran@gmail.com")
        print(f"→ GitHub: github.com/BaskaranMS")
        print(f"→ LinkedIn: linkedin.com/in/baskaran-m-s")

# Execute profile
if __name__ == "__main__":
    profile = HackerProfile()
    profile.greet()
    profile.contact()

# SYSTEM DIAGNOSTICS
$ whoami
> baskaranms

$ uname -a
> Linux hacker-mind 5.15.0-76-generic #83-Ubuntu SMP 
> x86_64 x86_64 x86_64 GNU/Linux

$ cat /proc/skills
> MERN Stack Development: 100%
> App Development: 85% 
> Data Science: 75%
> Problem Solving: 95%

+ 〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰
+ █▀█ █▀▀ █▀█ █▀▀ █▀▀ █░█ █▀▀ █▀█ █▀▀ █▀▀ 
+ █▀▄ ██▄ █▀▀ ██▄ █▄▄ █▄█ ██▄ █▀▄ ██▄ ██▄ 
+ 〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰

$ ls -la ~/projects
drwxr-xr-x  8 root root   4096 Dec 12 12:34 CountryPedia
drwxr-xr-x 10 root root   4096 Dec 12 12:35 RecruitLink 
drwxr-xr-x  6 root root   4096 Dec 12 12:36 E-Commerce-App
drwxr-xr-x  7 root root   4096 Dec 12 12:37 School-DataHub

# PROJECT STATUS MONITOR
projects = {
    "CountryPedia": {
        "status": "Online",
        "tech": ["React", "REST API", "Tailwind CSS"],
        "url": "https://country-pedia-msb.vercel.app/"
    },
    "RecruitLink": {
        "status": "Beta",
        "tech": ["MERN Stack", "Firebase", "WebSockets"],
        "url": "https://recruitlink.vercel.app/" 
    }
}

for project, details in projects.items():
    print(f"[{details['status']}] {project}")
    print(f"Stack: {', '.join(details['tech'])}")
    print(f"URL: {details['url']}\n")


+ ╔════════════════════════════════════════════╗
+ ║                CONNECTION GRID             ║
+ ╠════════════════════════════════════════════╣
+ ║ GitHub      ████████████████████████ 100% ║  
+ ║ LinkedIn    ████████████████████░░░░ 80%  ║
+ ║ Instagram   ██████████░░░░░░░░░░░░░░ 40%  ║
+ ║ Email       ████████████████████████ 100% ║
+ ╚════════════════════════════════════════════╝

// TECH STACK ANALYSIS
const techStack = {
  languages: ["JavaScript", "Python", "Java"],
  frontend: {
    libs: ["React", "Redux", "Tailwind CSS"],
    tools: ["VS Code", "Chrome DevTools"]  
  },
  backend: {
    runtime: ["Node.js", "Express"],
    databases: ["MongoDB", "Firebase"]
  },
  mobile: ["React Native", "Expo"],
  devOps: ["Git", "GitHub", "Vercel", "Netlify"]
};

console.log("⚡ Current Tech Configuration:");
Object.entries(techStack).forEach(([category, items]) => {
  console.log(`⦿ ${category.toUpperCase()}: ${items.join(", ")}`);
});

$ neofetch
       _,met$$$$$gg,          baskaranms@hacker-terminal 
    ,g$$$$$$$$$$$$$$$P.       ------------------------- 
  ,g$$P""       """Y$$.".      OS: Ubuntu 22.04 LTS x86_64 
 ,$$P'              `$$$.      Shell: zsh 5.8.1 
',$$P       ,ggs.     `$$b:    Terminal: vs-code 
`d$$'     ,$P"'   .    $$$     CPU: Intel i7-11800H (16) @ 4.600GHz 
 $$P      d$'     ,    $$P     Memory: 16384MiB 
 $$:      $$.   -    ,d$$'     Disk: 512GB SSD
 $$;      Y$b._   _,d$P'       Packages: 1284 (npm) 
 Y$$.    `.`"Y$$$$P"'          Repositories: 24 
 `$$b      "-.__               Languages: JavaScript, Python, Java 
  `Y$$                        Frameworks: React, Node.js, Express 
   `Y$$.                      Databases: MongoDB, Firebase 
     `$$b.                    Tools: Git, Docker, Postman
       `Y$$b.                 
          `"Y$b._             
              `""""


# INITIATE CONNECTION PROTOCOL
def establish_connection():
    print("Establishing secure channel...")
    print("Encryption: AES-256")
    print("Authentication: OAuth2.0")
    print("\nConnection endpoints:")
    print("- GitHub: github.com/BaskaranMS")
    print("- LinkedIn: linkedin.com/in/baskaran-m-s")
    print("- Portfolio: baskaranms.vercel.app")
    
    if connection_successful:
        print("\n[STATUS] Connection established!")
        print("Awaiting collaboration requests...")
    else:
        print("[ERROR] Connection failed")
        print("Retrying with alternative protocols...")

establish_connection()

+ █▀▀ █▀▀ █── █▀▀ █▀▀ ▄▀▀ ▄▀▀ ▄▀▀ 
+ █── █▀▀ █── █▀▀ █── ▀▀▄ ▀▀▄ ▀▀▄ 
+ ▀▀▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀▀─ ▀▀─ ▀▀─
