# Customizing Terminal

## install
- iterm2
- zsh
- powerlevel10k

## theme style
![theme style image](https://github.com/2021bong/my-template/assets/49029756/b75f89b5-c7b9-4ad5-95de-2acb09f42577)

## font
MesloLGS NF

## user name
show random emoji
```
prompt_context() {
  # Custom (Random emoji)
  emojis=("⚡️" "🔥" "🥳" "👑" "😎" "🐹" "🐱" "🌈" "🦋" "💡" "🎉" "🍀" "✨" "🌙" "🍄" "💫" "💎" "💸" "🎊" "🎁" "💖" "❣️" "💕" "🌕" "🌏" "💥")
  RAND_EMOJI_N=$(( $RANDOM % ${#emojis[@]} + 1 ))
  prompt_segment black default "2021bong ${emojis[$RAND_EMOJI_N]}"
}
```

## other
- syntax-highlighting
- auto suggestion