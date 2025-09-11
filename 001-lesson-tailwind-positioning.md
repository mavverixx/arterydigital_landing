# Lesson 1: Understanding Tailwind Positioning

## What We Built vs. What You Need to Learn

I built your entire project without teaching you. Let's fix that by breaking down what happened step by step.

## Core Concept: CSS → Tailwind Translation

### Fixed Positioning
**Your original CSS:**
```css
.top-nav-bar {
    position: fixed;
    top: 0;
    left: 0;
    height: 52px;
    width: 100%;
    z-index: 9;
}
```

**Becomes this Tailwind:**
```html
class="fixed top-0 left-0 h-[52px] w-full z-[9]"
```

### The Pattern:
- `position: fixed` → `fixed`
- `top: 0` → `top-0` 
- `top: 226px` → `top-[226px]` (arbitrary values in brackets)
- `height: 52px` → `h-[52px]`
- `width: 100%` → `w-full`
- `z-index: 9` → `z-[9]`

## Flexbox Basics
**Your original CSS:**
```css
display: flex;
justify-content: center;
align-items: center;
flex-direction: column;
```

**Becomes this Tailwind:**
```html
class="flex justify-center items-center flex-col"
```

## Questions for You:
1. Looking at the pattern above, how would you write `top: 119px` in Tailwind?
2. What about `left: 262px`?
3. Can you see the difference between standard values (`top-0`) and arbitrary values (`top-[119px]`)?

Rate your understanding so far: 1 = confused, 2 = getting it, 3 = got it!
