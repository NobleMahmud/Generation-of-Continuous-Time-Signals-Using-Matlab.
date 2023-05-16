# Generation-of-Continuous-Time-Signals-Using-Matlab.
The Continous signal is a signal which has continuous amplitude &amp;amp; time, meaning it will have some value at every instant of time. These are some basic signals of such type:   Impulse signal  Unit step signal  Unit ramp signal  Exponential signal  Sine signal  Cosine Signal

N=16;
x=0:1:N-1;
y=[ones(1,1),zeros(1,N-1)];

subplot(3,2,1);
plot(x,y);
xlabel(&#39;x&#39;);
ylabel(&#39;y&#39;);
title(‘Impulse Signal’);
N=16;
x=0:1:N-1;
y=ones(1,N); 
subplot(3,2,2);
plot(x,y);
xlabel(‘x’);
ylabel(&#39;y&#39;);
title(‘Unit-Step Signal’);

N=16;
x=0:1:N-1;
y=x;
subplot(3,2,3);
plot(x,y);
xlabel(&#39;x&#39;);
ylabel(&#39;y&#39;);
title(‘Ramp Signal’);

N=16;
x=0:1:N-1;
y=exp(x);
subplot(3,2,4);
plot(x,y);
xlabel(&#39;x&#39;);
ylabel(&#39;y&#39;);
title(‘Exponential Signal’);
N=16;
x=0:1:N-1;
y=sin(.2*pi*x);
subplot(3,2,5);
plot(x,y);
xlabel(&#39;x&#39;);
ylabel(&#39;y&#39;);
title(‘Sine Signal’);

N=16;
x=0:1:N-1;
y=cos(.2*pi*x);
subplot(3,2,6);
plot(x,y);
xlabel(‘x’);
ylabel(‘y’);
title(‘Cosine Signal’);
