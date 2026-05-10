## 2026-05-10 - ARIA Dropdown Expansion
**Learning:** Native button tags inside custom dropdowns often lack accessibility context. It's beneficial to add `role="menuitem"` to actions inside a dropdown and `role="menu"` to the container to help screen readers understand the interaction, along with `aria-expanded` and `aria-haspopup="menu"` on the trigger.
**Action:** Consistently verify custom dropdowns for proper ARIA roles and state attributes.
