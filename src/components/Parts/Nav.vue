<template>
  <nav class="level">
    <div class="level-left">
      <div class="level-item"></div>
    </div>
    <div class="level-right">
      <div class="level-item">
        <div class="social--icon">
          <a href="https://twitter.com/trytokyo" target="_blank">
            <eva-icon name="twitter" animation="pulse" fill="#3596FD"></eva-icon>
          </a>
        </div>
        <div class="social--icon">
          <a href="https://github.com/heyomar/omarrasool.com" target="_blank">
            <eva-icon name="github" animation="pulse" fill="#3596FD"></eva-icon>
          </a>
        </div>
        <a
          href="mailto:webdevromar@gmail.com?Subject=%20Hello"
          class="button"
          role="button"
        >Say Hello</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Nav"
};
</script>

<style lang="sass">
// COLORS
$prime: #3596FD
$second: #140C36

.button
  margin-top: 25px
  margin-right: 25px
  border: 2px solid $prime
  font-size: 22px
  border-radius: 100px
  font-weight: bold
  background-color: transparent
  color: $prime
  opacity: .7
  transition: all 200ms ease-in-out

  &:hover
    opacity: 1
    border: 2px solid $prime
    color: $prime

.social--icon
  padding: 30px 10px 0 5px
  opacity: .7
  &:hover
    opacity: 1
</style>