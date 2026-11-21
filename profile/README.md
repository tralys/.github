C# libraries for games, built so the hot path allocates nothing.

| Library | What it is |
|---|---|
| [Tralys.Ui](https://github.com/tralys/Tralys.Ui) | UI for .NET game clients: C# components rendered through bgfx. A warm frame allocates nothing. [Live gallery](https://tralys.github.io/Tralys.Ui/) |
| [Tralys.BehaviorTree](https://github.com/tralys/Tralys.BehaviorTree) | Behavior trees for game servers that run thousands of agents. A tick allocates nothing. |
| [Tralys.Analyzers](https://github.com/tralys/Tralys.Analyzers) | Roslyn analyzers that keep the compiler's null checks switched on. |
