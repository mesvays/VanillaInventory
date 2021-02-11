# VanillaInventory
**Enable to use Anvil and Enchantment GUI for PocketMine**


## Feature
- Enable to use Anvil and enchantment table GUI like vanilla


## How to use
Install this plugin and run your server. Place anvil or enchantment block only.


## Developer Documentation
- PlayerEnchantItemEvent

when player tries to enchant some items, this event will called

```php
//Player Who tried to enchant
public function getPlayer() : \pocketmine\Player

//Return an enchanted item
public function getItem() : \pocketmine\item\Item
```

<br>

- PlayerAnvilUseEvent

Coming Soon