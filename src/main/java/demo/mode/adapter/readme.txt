适配器模式
适配器模式是为了平衡需求和客观存在的差异，使得需求的接口与现有的接口能够协同工作。
Target是目标需求，Target中需要的是targetMethod方法。
Adaptee是客观现有的类，Adaptee中现有的方法specialMethod。
Adapter是适配器，适配器继承自Target并包含Adaptee对象，在重写targetMethod时通过Adaptee对象来调用specialMethod来实现。