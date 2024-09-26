from django.shortcuts import render
from django.views.generic import TemplateView


# Create your views here.

def games_platform(request):
  return render(request, 'third_task/platform.html')


def games(request):
    game_list = {
        "1": "Atomic Heart",
        "2": "Cyberpanc 2077",
        "3": "Pay Day"
    }
    return render(request, "third_task/games.html", {"game_list": game_list})


def cart(request):
    status_cart = "Извините, Ваша корзина пуста"
    return render(request, 'third_task/cart.html', {"status_cart": status_cart})
