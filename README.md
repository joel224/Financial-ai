# Financial-ai
we use CNN-LSTM-Attention extractors + NN meta-regressor along an advanced ensemble technique

note this project uses ai to increase productivity and efficiency in projects 

<img width="1021" height="547" alt="image" src="https://github.com/user-attachments/assets/2ebe123f-8653-41b7-a14b-1b92ba9bd1f8" />.


Analogy for my Recruiters :) 

Imagine you bet on a race.

Buy and Hold (orange line)  : You picked a horse at the start and just hope it wins. If the horse trips and falls (market goes down), you lose.

Ensemble Strategy (blue line) : You're predicting if the horse will gain or lose ground on each lap.

If you predict the horse will fall behind on the next lap, and it does, you bet against it (go short) and you win money, even though the horse itself is doing badly.

The horse's performance (Buy and Hold) is bad, but your betting strategy based on predictions (Ensemble) is good because you correctly bet against it.

This is precisely why you see the blue line rising while the orange line is falling in many parts of your graph – the ensemble strategy is successfully making money from negative market movements by going short.

Scenario 2: When Buy and Hold Gets Better (Orange Goes Up), Prediction (Ensemble) Goes Down
This can also happen and is a sign of a prediction error by the ensemble model.

What Buy and Hold (Orange) Does: If the actual market price of the asset is rising on a particular day, then the Buy and Hold strategy naturally gains money for that day.

What Ensemble Strategy (Blue) Does When It Makes a Mistake:

Let's say the market is going to rise tomorrow.

Your Ensemble Model incorrectly predicts that the log return for tomorrow will be negative (or predicts a very small positive when a large one occurs, and doesn't capture it efficiently).

Based on this incorrect prediction, the Ensemble Strategy might decide to "go short" (betting on a decline) or not go long aggressively enough.

When the market does rise, the Buy and Hold strategy gains money, but your Ensemble Strategy loses money because it was positioned incorrectly for the actual market movement.

