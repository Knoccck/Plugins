package net.runelite.client.plugins.blackjack;

import net.runelite.client.config.Config;
import net.runelite.client.config.ConfigGroup;
import net.runelite.client.config.ConfigItem;

@ConfigGroup("blackjack")
public interface BlackjackConfig extends Config
{
	@ConfigItem(
		keyName = "pickpocketOnAggro",
		name = "Pickpocket when aggro\'d",
		description = "Switches to \"Pickpocket\" when bandit is aggro\'d. Saves food at the cost of slight xp/h.",
		position = 0
	)
	default boolean pickpocketOnAggro()
	{
		return false;
	}

	@ConfigItem(
		keyName = "random",
		name = "Randomly Miss 1 Pickpocket",
		description = "If enabled, this will randomly miss 1 pickpocket every so often." +
			"<br> Not sure why'd you want to do that, but you can.",
		position = 1
	)
	default boolean random()
	{
		return false;
	}
}
