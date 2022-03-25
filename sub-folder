public class Example extends JavaPlugin {
    public void onEnable() {
        File folder = new File(getDataFolder(), "exampleFolder");
        if (!path.exists()) {
            path.mkdir();
        }
        File file = new File(folder, "example.yml");
        try {
            if (!file.exists()) {
                file.createNewFile();
            }
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
}
