import javafx.fxml.FXML;
import javafx.scene.control.Label;
import javafx.scene.control.TextField;

public class TipCalculatorController {
    @FXML
private TextField billAmountField;

    @FXML
private TextField tipPercentageField;

    @FXML
private Label tipAmountLabel;

    @FXML
private Label errorMessageLabel;

    @FXML
private void calculateTip() {
try {
double billAmount = Double.parseDouble(billAmountField.getText());
double tipPercentage = Double.parseDouble(tipPercentageField.getText());

double tipAmount = billAmount * (tipPercentage / 100);
tipAmountLabel.setText(String.format("Tip Amount: $%.2f", tipAmount));
errorMessageLabel.setText("");
        } catch (NumberFormatException e) {
errorMessageLabel.setText("Error: Invalid input. Please enter numbers.");
        }
    }

    @FXML
private void reset() {
billAmountField.clear();
tipPercentageField.clear();
tipAmountLabel.setText("");
errorMessageLabel.setText("");
    }
}