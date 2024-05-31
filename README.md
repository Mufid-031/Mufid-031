    interface dataTypes {
        biodata: {
          firstname: string;
          lastname: string;
          email: string;
          desc: string;
        };
        sosial: {
          github: string;
          instagram: string;
          twitter: string; 
        };
        skills: {
          frontend: string[];
          backend: string[];
          devtools: string[];
        };
      }


      const data: dataTypes = {
        biodata: {
          firstname: "Ahmad",
          lastname: "Mufid Risqi",
          email: "risqimufid50@gmail.com",
          desc: "Saya adalah mahasiswa teknik informatika di universitas trunojoyo madura",
        },
        sosial: {
          github: "https://github.com/Mufid-031",
          instagram: "https://www.instagram.com/damslette3",
          twitter: "https://x.com/MufidRisqi30683",
        },
        skills: {
          frontend: ["HTML", "CSS", "Javascript", "Typescript", "React", "Next.js", "Tailwind CSS"],
          backend: ["Node.js"],
          devtools: ["Git", "Github"],
        },
      };

      const main: (data: dataTypes) => void = (data: dataTypes) => {
        console.log(data);
      }

      main(data);
    
