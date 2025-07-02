<div class="fix">
  <div class="wrapper">
    <div class="block"></div>
    <div class="text-top">
      <div>Shin-hyabusasun. </div>
      <div>Shin-hyabusasun. </div>
    </div>
    <div class="block-tile"></div>
    <div class="block-tile1"></div>
   
  </div>
</div>

<style>
.wrapper {
  margin-top: 400px;
  padding-bottom: 100px;
  overflow: hidden;
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.block {
  position: absolute;
  top: 0;
  left: 0;
  margin-left: 100px;
  width: 300px;
  height: 500px;
  background-color: rgb(252, 4, 4);
  z-index: 0;
}
.text-top {
  white-space: nowrap;
  display: flex;
  flex-direction: row;
  font-size: 150px;
  font-weight: bold;
  z-index: 1;
  color: rgb(0, 0, 0);
  position: relative;
  margin-top: 110px;
  text-align: left;
  animation: marquee 10s linear infinite;
}
.text-bottom {
  margin-left: 100px;
  font-size: 170px;
  font-weight: normal;
  color: rgb(3, 3, 3);
  z-index: 1;
  margin-top: 0px;
  text-align: left;
}
@keyframes marquee {
  0% { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}
.background-video {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  object-fit: cover;
  z-index: -1;
  opacity: 0.2;
}








[![trophy](https://github-profile-trophy.vercel.app/?username=shin-hayabusasun&thema=dracula&margin-w=15&column=7&title=MultiLanguage,Followers,Commits,PullRequest,Repositories,Issues,Experience)](https://github.com/ryo-ma/github-profile-trophy)
