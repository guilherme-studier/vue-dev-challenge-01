<template>
  <footer>
      <p class="footer">
        created by Guilherme - devChallenges.io
      </p>
    </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped>
  footer .footer {
    font-family: "Montserrat", sans-serif;
    color: var(--gray-100);
    font-size: 14px;
    font-weight: 500;
    text-align: center;

    margin-block: 0;
  }

  @media (max-width: 1000px) {
    .footer {
      padding: 6.125rem 0 0.5rem 0;
    }
  }
</style>