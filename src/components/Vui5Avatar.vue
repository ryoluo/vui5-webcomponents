<template>
  <ui5-avatar></ui5-avatar>
</template>
<script lang="ts">
import "@ui5/webcomponents/dist/Avatar.js";

interface AvatarProps {
  disable: boolean;
  interactive: boolean;
  icon?: string;
  fallbackIcon: string;
  initials?: string;
  shape: "Circle" | "Square";
  size: "XS" | "S" | "M" | "L" | "XL";
  colorScheme:
    | "Accent1"
    | "Accent2"
    | "Accent3"
    | "Accent4"
    | "Accent5"
    | "Accent6"
    | "Accent7"
    | "Accent8"
    | "Accent9"
    | "Accent10"
    | "Placeholder";
}
</script>
