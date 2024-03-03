public class AntiCheatBanSystem {
    public static void main(String[] args) {
        boolean hasAimBot = true;
        boolean gets500MillionInOneSecond = true;
        boolean getsMaxLevelInOneSecond = true;
        boolean hasWallhack = true;
        boolean hasGodMode = true;
        boolean hasUltimateAmmo = true;
        boolean isInvisibilityMode = true;

        if (hasAimBot || gets500MillionInOneSecond || getsMaxLevelInOneSecond || hasWallhack || hasGodMode || hasUltimateAmmo || isInvisibilityMode) {
            System.out.println("Player banned from the server for cheating!");
        } else {
            System.out.println("Player is clean.");
        }
    }
}

