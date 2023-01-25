<template>
  <div class="content">
    <div class="content-img">
      <img src="../assets/Scarecrow.png" alt="scarecrow">
    </div>
    <div class="content-text">
      <h1 class="content-text_title">I have bad news for you</h1>
      <p class="content-text_paragraph">The page you are looking for might be removed or is temporarily unavailable</p>
      <button class="content-text_button">Back to homepage</button>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .content {
    max-width: 1244px;
    width: 100%;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;  
  }
  
  .content .content-img {
    max-width: 539.22px;
    flex: 1 1 300px;
  }

  .content .content-img img {
    width: 100%;
  }

  .content .content-text {
    max-width: 586px;

    text-align: left;
    flex: 1 1 300px;
    margin-left: 118px;
  }

  .content-text .content-text_title {
    letter-spacing: -0.035em;
    font-style: normal;
    font-weight: 700;
    font-size: 64px;
    line-height: 95px;

    margin-block: 0;
    margin-bottom: 36px;
  }

  .content-text .content-text_paragraph {
    font-style: normal;
    font-weight: 400;
    font-size: 24px;
    line-height: 36px;
    letter-spacing: -0.035em;
    width: 23.81rem;

    margin-block: 0;
    margin-bottom: 64px;
  }

  .content-text .content-text_button {
    font-family: 'Space Mono', monospace;
    text-transform: uppercase;
    font-weight: 700;
    font-size: 14px;
    width: 216px;
    height: 68px;

    color: var(--white);
    background: var(--gray-300);
  }

  @media (max-width: 1000px) {
    .content {
      width: 100%;
    }

    .content .content-img {
      width: 100%;
      padding: 3rem 0;
    }

    .content .content-text {
      width: 100%;
      margin: 0;
    }
    
    .content .content-text .content-text_title {
      font-size: 48px;
      line-height: 71px;
      letter-spacing: -0.035em;

      margin-block: 0;
      margin-bottom: 30px;
    }

    .content .content-text .content-text_paragraph {
      font-size: 18px;
      line-height: 27px;
      width: 328px;

      margin-block: 0;
      margin-bottom: 66px;
    }
  }
</style>