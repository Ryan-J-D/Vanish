**Vanish** allows players with permission to become completely invisible. Players, turrets, helicopters, NPCs, etc. will not be able to see, hear, or touch you!

**Note:** While vanished, you can hear players but they will be unable to hear you. You are invisible to them and essentially do not exist to them. Even if they walk right through you they *DO NOT* know of your existence.

## Permissions

- **vanish.use** -- Required to go invisible
- **vanish.damage.buildings** -- Allows player to damage buildings
- **vanish.damage.animals** -- Allows player to hurt animals while vanished
- **vanish.damage.players** -- Allows player to hurt players while vanished
- **vanish.abilities.invulnerable** -- Makes player invulnerable while vanished
- **vanish.abilities.teleport** -- Allows player to teleport while vanished

## Commands

- **vanish** -- Toggle player's invisibility on/off

## Configuration

```json
{
  "Play sound effect (true/false)": true,
  "Show visual indicator (true/false)": true,
  "Show visual overlay (true/false)": false,
  "Vanish timeout (seconds, 0 to disable)": 0,
  "Visible to admin (true/false)": false
}
```

## Localization

The default messages are in the `Vanish.json` file under the `oxide/lang/en` directory. To add support for another language, create a new language folder (ex. de for German) if not already created, copy the default language file to the new folder, and then customize the messages.

## Credits

- **Nogrod**, for all the help along the way. Cheers!
- **Jake_Rich**, for helping maintain the plugin
- **dcode**, for the awesome icon
