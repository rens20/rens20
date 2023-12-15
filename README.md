### Hi there 👋

const introduction = {
  name: "Rens Belga Acuña ",
  profession: "Self-taught full-stack developer",
  location: "Philippines",
  passions: ["Web Development", "Learning"],
  skills: ["HTML", "CSS", "JavaScript", "node.js", "ReactJS","boostrap","c++"],
  portfolio: "https://myprofile-blond.vercel.app/",
  github: "https://github.com/rens20",
  socialMedia: ["https://www.facebook.com/renswashie.acunabelga"],
  quote: "Programming is the art of telling a computer what to do; a skill that empowers us to transform imagination into reality through the language of code."
};

const introduceMyself = ({ name, profession, location, passions, skills, portfolio, github, socialMedia, quote }) => {
  console.log(`Hi there, I'm ${name}, a ${profession} from ${location}. My passion lies in ${passions[0]} and ${passions[1]}, and I continuously strive to expand my skillset and knowledge in ${skills.join(", ")} and other programming languages. I am proud to give back to the community by actively contributing to open-source projects through my Github profile at ${github}, and my portfolio at ${portfolio} showcases a small portion of my work. If you're interested in my personal and professional journey, feel free to connect with me on my social media accounts at ${socialMedia.join(", ")}. 

One of my favorite quotes is "${quote}", and I believe that with dedication and hard work, anything is possible. Let's connect and create something amazing together!"`);
};

introduceMyself(introduction);

