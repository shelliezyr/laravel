<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class StaticPageController extends Controller
{
    //test 1111
	public function home(){
		return view('staticpage/home');
	}
	public function help(){
		return view('staticpage/help');
	}
	public function about(){
		return view('staticpage/about');
	}

	public function store(Request $request){
		$name = $request->input('name');
		return view('staticpage/help');
	}

	public function post(Request $request){
		$name = $request->input('name');
		return view('staticpage/help');
	}

}
