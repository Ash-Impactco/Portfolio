# Portfolio
 Home() {
  return (
    <main className="flex min-h-screen flex-col items-center justify-center p-12 bg-gray-50">
      <h1 className="text-5xl font-bold text-gray-800 mb-6">Hi, I'm Aswin 👋</h1>
      <p className="text-lg text-gray-600 text-center max-w-xl">
        I'M just trying out responsive websites with modern tech like Next.js and Tailwind CSS.
      </p>
    </main>
  );
}
components/Hero.tsx – for your intro
export default function Hero() {
  return (
    <section className="min-h-screen flex flex-col items-center justify-center bg-white text-center px-4">
      <h1 className="text-5xl font-bold text-gray-800 mb-4">Hey, I'm Aswin 👋</h1>
      <p className="text-lg text-gray-600 max-w-xl">
        A passionate web developer building fast, modern websites using Next.js, React & Tailwind CSS.
      </p>
    </section>
  );
}

components/About.tsx
export default function About() {
  return (
    <section className="py-20 px-4 bg-gray-100 text-gray-800">
      <div className="max-w-3xl mx-auto">
        <h2 className="text-3xl font-bold mb-4">About Me</h2>
        <p className="text-lg">
          I'm a developer with a strong focus on building clean, accessible, and high-performing websites.
          I love turning ideas into digital experiences that are both beautiful and functional.
        </p>
      </div>
    </section>
  );
}

components/Projects.tsx
export default function Projects() {
  return (
    <section className="py-20 px-4 bg-white text-gray-800">
      <div className="max-w-5xl mx-auto">
        <h2 className="text-3xl font-bold mb-8">Projects</h2>
        <div className="grid gap-8 md:grid-cols-2">
          <div className="p-6 border rounded-xl shadow-sm hover:shadow-md transition">
            <h3 className="text-xl font-semibold mb-2">Project One</h3>
            <p className="text-gray-600">A cool project description goes here.</p>
          </div>
          <div className="p-6 border rounded-xl shadow-sm hover:shadow-md transition">
            <h3 className="text-xl font-semibold mb-2">Project Two</h3>
            <p className="text-gray-600">Another awesome project description.</p>
          </div>
        </div>
      </div>
    </section>
  );
}

components/Contact.tsx
export default function Contact() {
  return (
    <section className="py-20 px-4 bg-gray-100 text-gray-800">
      <div className="max-w-xl mx-auto text-center">
        <h2 className="text-3xl font-bold mb-4">Get In Touch</h2>
        <p className="text-lg mb-6">Have a project in mind or just want to say hi? Let’s connect!</p>
        <a
          href="mailto:youremail@example.com"
          className="inline-block bg-blue-600 text-white py-3 px-6 rounded-xl hover:bg-blue-700 transition"
        >
          Say Hello
        </a>
      </div>
    </section>
  );
}

index.tsx
import Hero from "@/components/Hero";
import About from "@/components/About";
import Projects from "@/components/Projects";
import Contact from "@/components/Contact";

export default function Home() {
  return (
    <main>
      <Hero />
      <About />
      <Projects />
      <Contact />
    </main>
  );
}

