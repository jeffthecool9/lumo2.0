gsap.registerPlugin(ScrollTrigger);

// HERO
gsap.from(".hero-title", {
  opacity: 0,
  y: 40,
  duration: 1,
  ease: "power3.out"
});

gsap.from(".hero-subtitle", {
  opacity: 0,
  y: 30,
  duration: 1,
  delay: 0.2,
  ease: "power3.out"
});

gsap.from(".btn-primary", {
  opacity: 0,
  scale: 0.9,
  duration: 0.8,
  delay: 0.4,
  ease: "power3.out"
});

// FEATURE VISUAL
gsap.from(".visual-box", {
  scrollTrigger: {
    trigger: ".feature-visual",
    start: "top 70%"
  },
  opacity: 0,
  y: 60,
  duration: 1
});

gsap.from(".visual-text", {
  scrollTrigger: {
    trigger: ".feature-visual",
    start: "top 70%"
  },
  opacity: 0,
  y: 40,
  duration: 1,
  delay: 0.2
});

// FEATURES
gsap.from(".feature-card", {
  scrollTrigger: {
    trigger: ".features",
    start: "top 75%"
  },
  opacity: 0,
  y: 40,
  stagger: 0.15,
  duration: 0.8
});

// PROCESS
gsap.from(".step", {
  scrollTrigger: {
    trigger: ".process",
    start: "top 75%"
  },
  opacity: 0,
  y: 30,
  stagger: 0.2,
  duration: 0.8
});
