<template>
  <StyledDiv>
    <img src="../public/banner.png" />
    <AboutMe>
      <StyledH2>〉 about me</StyledH2>
      <StyledList>
        <li>🦾 <strong>full stack</strong> developer</li>
        <li>
          ⭐ currently working on <strong>web and mobile development</strong>
        </li>
        <li>💀 a lot of <strong>private repositories</strong></li>
        <li>🕹️ a <strong>freelance</strong> working his way around things</li>
        <li>👾 love <strong>pixel</strong></li>
      </StyledList>
    </AboutMe>

    <Skills>
      <StyledH2>〉 current skills</StyledH2>

      <StyledH4>languages</StyledH4>
      <SkillsRow>
        <img
          src="https://img.shields.io/badge/JavaScript-black?style=for-the-badge&logo=javascript&logoColor=F7DF1E"
          alt="js"
        />
        <img
          src="https://img.shields.io/badge/TypeScript-black?style=for-the-badge&logo=typescript&logoColor=blue"
          alt="ts"
        />
        <img
          src="https://img.shields.io/badge/HTML5-black?style=for-the-badge&logo=html5&logoColor=orange"
          alt="html"
        />
        <img
          src="https://img.shields.io/badge/CSS3-black?style=for-the-badge&logo=css3&logoColor=blue"
          alt="css"
        />
        <img
          src="https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white"
          alt="markdown"
        />
      </SkillsRow>

      <StyledH4>database</StyledH4>
      <SkillsRow>
        <img
          src="https://img.shields.io/badge/MongoDB-black?style=for-the-badge&logo=mongodb&logoColor=green"
          alt="mongodb"
        />
      </SkillsRow>

      <StyledH4>frameworks & libraries</StyledH4>
      <SkillsRow>
        <img
          src="https://img.shields.io/badge/react-black?style=for-the-badge&logo=react&logoColor=%2361DAFB"
          alt="react"
        />
        <img
          src="https://img.shields.io/badge/react_native-black?style=for-the-badge&logo=react&logoColor=%2361DAFB"
          alt="react-native"
        />
        <img
          src="https://img.shields.io/badge/express.js-black?style=for-the-badge&logo=express&logoColor=%2361DAFB"
          alt="expressjs"
        />
        <img
          src="https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101"
          alt="socket-io"
        />
        <img
          src="https://img.shields.io/badge/expo-black?style=for-the-badge&logo=expo&logoColor=#D04A37"
          alt="expo"
        />
        <img
          src="https://img.shields.io/badge/next.js-black?style=for-the-badge&logo=next.js&logoColor=white"
          alt="nextjs"
        />
      </SkillsRow>

      <StyledH4>hosting</StyledH4>

      <SkillsRow>
        <img
          src="https://img.shields.io/badge/vercel-black?style=for-the-badge&logo=vercel&logoColor=white"
          alt="vercel"
        />
        <img
          src="https://img.shields.io/badge/DigitalOcean-black?style=for-the-badge&logo=digitalOcean&logoColor=blue"
          alt="digital-ocean"
        />
        <img
          src="https://img.shields.io/badge/ovh-black?style=for-the-badge&logo=ovh&logoColor=lightblue"
          alt="ovh"
        />
      </SkillsRow>

      <StyledH4>designing tools</StyledH4>
      <SkillsRow>
        <img
          src="https://img.shields.io/badge/adobe%20photoshop-black?style=for-the-badge&logo=adobe%20photoshop&logoColor=cyan"
          alt="photoshop"
        />
        <img
          src="https://img.shields.io/badge/figma-black?style=for-the-badge&logo=figma&logoColor=violet"
          alt="figma"
        />
      </SkillsRow>
    </Skills>

    <StyledH4>music</StyledH4>

    <SkillsRow>
      <a href="https://www.soundcloud.com/sbigz" target="_blank"
        ><img
          src="https://img.shields.io/badge/sound%20cloud-black?style=for-the-badge&logo=soundcloud&logoColor=orange"
          alt="soundcloud"
      /></a>
      <a
        href="https://open.spotify.com/artist/0ggEZfElbLKckqn4O5vbcP"
        target="_blank"
        ><img
          src="https://img.shields.io/badge/Spotify-black?style=for-the-badge&logo=spotify&logoColor=green"
          alt="spotify"
      /></a>
      <a
        href="https://music.apple.com/fr/artist/sbigz/1540002649"
        target="_blank"
        ><img
          src="https://img.shields.io/badge/Apple_Music-black?style=for-the-badge&logo=apple-music&logoColor=fc3c44"
          alt="apple"
      /></a>
      <a href="https://www.deezer.com/fr/artist/113167382" target="_blank"
        ><img
          src="https://img.shields.io/badge/Deezer-black?style=for-the-badge&logo=deezer&logoColor=blue"
          alt="deezer"
      /></a>
    </SkillsRow>
    <Visitors>
      <img
        align="right"
        src="https://komarev.com/ghpvc/?username=SBigz&label=Visitors_👀&color=lightgray&style=flat-square"
        alt="SBigz"
      />
    </Visitors>

    <Socials>
      <a href="https://www.linkedin.com/company/93264941/" target="_blank"
        ><img
          src="https://img.shields.io/badge/-CodeSacha-blue?logo=linkedin&style=flat-square"
          alt="linkedin"
      /></a>
      <a href="https://www.linkedin.com/in/sacha-bigou" target="_blank"
        ><img
          src="https://img.shields.io/badge/-Sacha_Bigou-blue?logo=linkedin&style=flat-square"
          alt="linkedin"
      /></a>
    </Socials>
  </StyledDiv>
</template>

<script>
import styled from "vue-styled-components";

const StyledDiv = styled.div`
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  min-width: 100vw;
  background-color: black;
  color: white;
`;

const AboutMe = styled.div`
  display: flex;
  flex-direction: column;
  align-items: center;
`;

const StyledList = styled.ul`
  display: flex;
  flex-direction: column;
  align-items: center;
  list-style: none;
  padding: 0;
`;

const Skills = styled.div`
  display: flex;
  flex: 1;
  flex-direction: column;
`;

const SkillsRow = styled.div`
  display: flex;
  flex: 1;
  flex-direction: row;
  align-items: flex-start;
  align-self: center;
`;

const StyledH2 = styled.h2`
  color: lime;
  text-align: center;
`;

const StyledH4 = styled.h4`
  color: green;
  text-align: center;
`;

const Visitors = styled.div`
  display: flex;
  flex: 1;
  flex-direction: column;
  align-items: center;
`;

const Socials = styled.div`
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
`;

export default {
  name: "IndexPage",
  components: {
    StyledDiv,
    AboutMe,
    StyledList,
    Skills,
    SkillsRow,
    StyledH2,
    StyledH4,
    Visitors,
    Socials,
  },
};
</script>
