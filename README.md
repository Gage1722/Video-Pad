# Video-Pad
Video Pad is a Gorilla Tag mod that enhances the in-game experience by allowing players to change the time of day, yes sounds familiar! (Day and Night changer) Well yes thats what video pad is but not ratted and its a pad instead of a table! Video Pad brings a whole new level of creativity to Gorilla Tag.

# Why should I download?
Well no ones forcing you to download (I HOPE) But if its a genuine question well here ya go! 
You should download Video Pad because it offers ingame video experance and more awsome sauce things like that!

# What does Video Pad have?
List:
NIGHT TIME
Code: public static void NightTime()
{
    BetterDayNightManager.instance.SetTimeOfDay(0);
}
EVENINGTIME
Code:public static void EveningTime
{
    BetterDayNightManger.instance.SetTimeOfDay(7);
}
MORNING TIME
Code: public static void MorningTime()
{
    BetterDayNightManager.instance.SetTimeOfDay(1);
}
DAY TIME
Code: public static void DayTime()
{
    BetterDayNightManager.instance.SetTimeOfDay(3);
}
RAIN
Code: public static void Rain()
{
    for (int i = 1; i < BetterDayNightManager.instance.weatherCycle.Length; i++)
    {
        BetterDayNightManager.instance.weatherCycle[i] = BetterDayNightManager.WeatherType.Raining;
    }
}
NORAIN
Code: public static void NoRain()
{
    for (int i = 1; i < BetterDayNightManager.instance.weatherCycle.Length; i++)
    {
        BetterDayNightManager.instance.weatherCycle[i] = BetterDayNightManager.WeatherType.None;
    }
}

private static LightmapData[] hell = null;
internal static object keyLogs;

public static void Fullbright()
{
    hell = LightmapSettings.lightmaps;
    LightmapSettings.lightmaps = null;
}

Thank You!
