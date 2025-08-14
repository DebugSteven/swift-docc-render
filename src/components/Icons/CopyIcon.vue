<!--
  This source file is part of the Swift.org open source project

  Copyright (c) 2025 Apple Inc. and the Swift project authors
  Licensed under Apache License v2.0 with Runtime Library Exception

  See https://swift.org/LICENSE.txt for license information
  See https://swift.org/CONTRIBUTORS.txt for Swift project authors
-->

<template>
  <svg
    class="copy-icon"
    viewBox="0 0 24 24"
  >
    <title>{{ $t('icons.copy') }}</title>
    <path d="M16 1H4c-1.1 0-2 .9-2 2v14h2V3h12V1zm3 4H8c-1.1 0-2
      .9-2 2v14c0 1.1.9 2 2 2h11c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0
      16H8V7h11v14z"/>
  </svg>
</template>

<script>
export default {
  name: 'CopyIcon',
};
</script>

<style scoped lang="scss">
.copy-icon {
  fill: currentColor;
  opacity: 0.8;
}
</style>
