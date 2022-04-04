x=linspace(-pi,pi,200);
y=x.*sin(x)+x.*cos(x);
z=1/sqrt(2)*exp(-1/4*(x-1).^2);
w=x.*sin(1./x);
plot(x,y,':r',x,z,'--k',x,w,'-g','linewidth',2)
grid on
legend('$\mathbf{y=x\,sin(x)+x\,cos(x)}$','$\mathbf{z=\frac{1}{\sqrt{2}}e^{-(x-1)^2/4}}$','$\mathbf{w=x\,sin(\frac{1}{x})}$','Interpreter','latex');
xlim([-pi,pi])
ylim([-2,4])
xlabel('x-axis')
ylabel('y-axis')
title('PLOTTING PRACTICE')