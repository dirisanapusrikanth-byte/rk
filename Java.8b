import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.control.Label;
import javafx.scene.image.Image;
import javafx.scene.image.ImageView;
import javafx.scene.layout.VBox;
import javafx.stage.Stage;
public class DisplayTextAndImage extends Application 
{
    @Override
public void start(Stage primaryStage) 
{
        Label textLabel = new Label("Hello, JavaFX!");
        Image image = new Image("file:imagePath.jpg");
        ImageView imageView = new ImageView(image);
imageView.setFitWidth(400);  
imageView.setFitHeight(300); 
        VBox vbox = new VBox(10); 
vbox.getChildren().addAll(textLabel, imageView);
        Scene scene = new Scene(vbox, 600, 400); 
primaryStage.setTitle("Text and Image Display");
primaryStage.setScene(scene);
primaryStage.show();
    }
public static void main(String[] args) 
{
launch(args);
    }
}